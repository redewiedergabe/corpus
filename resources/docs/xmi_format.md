# XMI

Folder: [data/xmi](../../data/main/xmi)

This version of the corpus consists of XMI files. Each file contains the text of one sample and the annotations of the project Redewiedergabe. In addition to the annotations added by the project Redewiedergabe, the files also contain morpho-syntactic annotations produced by automatic tools that were not developed by the project Redewiedergabe.

For a more detailed explanation of the annotation structure see [Annotation structure](annotation_structure.md).

# Typesystem
Typesystem: [data/xmi/resources](../../data/main/xmi/resources)

### Types

| Type| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| CabToken      | String                                                                      | token (tokenization by CAB) |
| Frame| String                                         | frame of the STWR            |
| IntExpression     | String                                                                       | word/s introducing the STWR             |
| Metadata       | String                                                   | metadata of the sample          |
| Sentence     | String                                          | sentence (sentence splitting by CAB)           |
| Speaker | String | speaker/source of the STWR         |
| Stwr       | String                                                      | main STWR annotation|
| TeiType     | String                                                                             | structural information |

### Features

* Features of the type **CabToken**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Id      | String                                                                      | token id |
| Xlit| String                                         | ortographically normalized token (provided by CAB)           |
| Canon     | String                                                                       | canonical form of token (provided by CAB)           |
| Pos       | String                                                   | morphological information (provided by CAB)        |
| Lemma     | String                                          | lemma (provided by CAB)         |
| RfPos | String | morphological information (provided by RF-Tagger)         |

* Features of the type **Frame**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Frame     | String                                                                      | surface |
| FrameID      | String                                                                      | frame id |
| Pos| start, mid, end                                         |  position of the frame relative to its STWR        |

* Features of the type **IntExpression**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| IntExpression      | String                                                                      | surface|
| IntExpressionID      | String                                                                      | intExpression id |

* Features of the type **Metadata**

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
| Periodical | String | periodical of the samples from mkhz       |
| Dialect | yes, yes_DS (dialect in direct speech), no | information on dialect        |
| Perspective | first, first_plural, third, unsure | predominant perspective        |
| Quotes | german, chevron, chevorn_single, ascii, dash, none, other, undef | predominantly used quotation marks         |

## References:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)
