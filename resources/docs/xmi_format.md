# XMI

## General remarks
Folder: [data/main/xmi](../../data/main/xmi)
Typesystem: [data/main/xmi/resources](../../data/main/xmi/resources)

This version of the corpus consists of XMI files. Each file contains the text of one sample. XMI was the working format of the project Redewiedergabe and the basis for the [XML](xml_format.md) and [text](column_based_text_format.md) formats. The files contain the following types of annotations:
* **STWR, Frame, IntExpr, Speaker, Metadata**: Annotations specific to the project Redewiedergabe. For a more detailed explanation of these annotations see [Annotation structure](annotation_structure.md) and [Metadata](metadata.md).
* **Text**: Structural marker. The relevant text of the sample is enclosed in this annotation.
* **CabToken, Sentence**: Additional morpho-syntactic annotation produced by automatic tools that were not developed by the project Redewiedergabe (CAB, RFTagger, references see below). 
* **TeiType**: Additional XML tags coded as XMI annotations. In the workflow of the project Redewiedergabe, samples were pulled from TEI complient XML files, then annotated with the CAB tool in XML mode and finally converted to XMI. The annotation **TeiType** preserves all XML annotations that were detected in the input documents. These annotations are diverse and have not been standardized in any way. They are provided as optional information for anyone who is interested in the relationship of the Redewiedergabe annotations to original TEI markers.

NOTE: Some XMI files contain textual metadata information at the beginning of the document. This information should be ignored by *only* processing the Annotation element **Text**. The correct metadata is stored in the annotation **Metadata**.  

The XMI files are compatible with the anntotation tool [ATHEN](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen) (developed by Markus Krug in the [Kallimachos project](http://kallimachos.de)) and its [STWR view](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen/blob/master/de.uniwue.mk.athen/releng/de.uniwue.mk.athen.docu/STWRView.md) (developed by Tanja Tu) which have been used in the project Redewiedergabe. This tool is freely available for download.  

### References for the additional tools:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)

## Types

| Type| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| CabToken      | String                                                                      | token (tokenization by CAB) |
| Frame| String                                         | frame of the STWR            |
| IntExpression     | String                                                                       | word/s introducing the STWR            |
| Metadata       | String                                                   | metadata of the sample          |
| Sentence     | String                                          | sentence (sentence splitting by CAB)           |
| Speaker | String | speaker/source of the STWR         |
| Stwr       | String                                                      | main STWR annotation|
| TeiType     | String                                                                             | addition XML tags from the  the source material |
| Text | String | textual content of the sample |
## Features

### Features of the type **CabToken**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Id      | String                                                                      | token id |
| Xlit| String                                         | ortographically normalized token (provided by CAB)           |
| Canon     | String                                                                       | canonical form of token (provided by CAB)           |
| Pos       | String                                                   | morphological information (provided by CAB)        |
| Lemma     | String                                          | lemma (provided by CAB)         |
| RfPos | String | morphological information (provided by RF-Tagger)         |

### Features of the type **Frame**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Frame     | String                                                                      | surface |
| FrameID      | String                                                                      | frame id |
| Pos| start, mid, end                                         |  position of the frame relative to its STWR        |

### Features of the type **IntExpression**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| IntExpression      | String                                                                      | surface|
| IntExpressionID      | String                                                                      | intExpression id |

### Features of the type **Metadata**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Name      | String                                                                     | the (anonymized) name of the annotator  |
| Source| digBib, grenz, mkhz (mkhz has subtypes for periodicals)                                         | text source         |
| OrigFile       | String                                                   | name of the source file the sample was pulled from      |
| Year     | between 1840 to 1919                                          | year of first publication     |
| Decade | 1840 to 1910 |decade of first publication     |
| Title | String | title, if available         |
| Author | String | author, if available       |
| Fictional | yes, no, unsure | information on fictionality        |
| Sample | String | starting by 1, if another sample is drawn from the same text, the value of Sample increases        |
| Narrative | yes, no, unsure | information on narrativity         |
| TextType | Anzeige, Biographie, Erzähltext, Kommentar, Nachrichten, Reisebericht/Brief, Reportage, Rezension, Unsure | predominant text type         |
| Dialect | yes, yes_DS (dialect in direct speech), no | information on dialect        |
| Perspective | first, first_plural, third, unsure | predominant perspective        |
| Quotes | german, chevron, chevorn_single, ascii, dash, none, other, undef | predominantly used quotation marks         |

### Features of the type **Sentence**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Id      | String                                                                      | sentence id |


### Features of the type **Speaker**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Speaker      | String                                                                      | surface|
| SpeakerID      | String                                                                      | speaker id |

### Features of the type **Stwr**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Medium      | speech, thought, writing (and combinations, separated by whitespace)                                                                       | STWR medium   |
| RType| direct, freeIndirect, indirect, reported, indirect freeIndirect                                          | STWR type         |
| Level       | starts with 1                                                   | nesting depth of this STWR annotation      |
| NonFact     | nonFact, *empty String*                                         | non-factual STWR, e.g. negated     |
| Prag | prag, *empty String* |STWR with a different pragmatic function, e.g. rhetorical figures     |
| Border | unspec, state, percept, *empty String* | borderline cases of STWR (typically for thought representation), e.g. perceptions         |
| Metaph | metaph, *empty String*| metaphorical STWR       |
| Stwr | String | surface        |
| StwrID | String | stwr id        |

### Features of the type **TeiType**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| TagName      | String                                                                       | tag name of the xml element  |
| Attributes| String                                         | attributes of the xml element  |


