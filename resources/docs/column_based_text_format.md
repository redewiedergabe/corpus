# Column based text format 

# General remarks

Folder: [data/txt](../../data/main/txt)

Corpus metadata is available in the file **metadata** ([tsv format](../../data/main/txt/metadata.tsv) or [Excel format](../../data/main/txt/metadata.xlsx))

The corpus consists of UTF-8 coded files with the file ending "tsv" (tab-separated values). Each file contains a sample in a column-based format. The columns are separated by tabstops and each line corresponds to one token of the sample (Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de)).

In addition to the annotations added by the project Redewiedergabe, the files also contain morpho-syntactic annotations produced by automatic tools that were not developed by the project Redewiedergabe.

For a more detailed explanation of the annotation structure see [Annotation structure](annotation_structure.md). 

## References:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)

# Columns

| Column | Description                                                                                        | Type                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| tok       | token (tokenization by CAB)                                                                        | surface |
| normtok   | ortographically normalized token (provided by CAB)                                           | NLP information           |
| lemma     | lemma (provided by CAB)                                                                        | NLP information           |
| pos       | morphological information (provided by CAB)                                                   | NLP information           |
| rfpos     | morphological information (provided by RF-Tagger)                                             | NLP information           |
| sentstart | information, whether the token appears at the beginning of a sentence; values: yes/no (sentence splitting by CAB) | NLP information           |
| stwr      | main STWR annotation                                                       | STWR annotation|
| frame     | frame of the STWR                                                                               | STWR annotation |
| speaker   | speaker/source of the STWR| STWR annotation |
| intexpr   | word/s introducing the STWR                                                                         | STWR annotation |
| note | information whether the words are part of a footnote; values: note/-                                                                        | structural annotation |

# Structure of the main STWR annotation
The STWR annotation can have many attributes and can be nested. Because of this, the column **stwr** contains complex values.

* The character `|` (vertical line) is used as separator, if a token has several annotations of different levels (nested STWR). The first annotation can be interpreted as level=1, the second annotation as level=2 etc. (Maximum nesting depth is 5)
* The character `.` (dot) is used to separate the attributes of a single STWR annotation. The following order is used: **Type**, **Medium**, **ID**, Nonfact, Border, Prag, Metaph. The three bolded attributes are obligatory, the other four may be missing, if the corresponding attributes are not relevant.
* The attribute border is further specified by a value after the character `=` (equals sign) (e.g. border=state)
* Alternative values are separated by the character `_` (low dash). This can happen for the attributes **Type** (e.g. indirect_freeIndirect) und **Medium** (e.g. speech_thought).

Example:

`direct.speech_writing.3|reported.thought.6.nonfact.border=state`

This token has two overlapping annotations:
* At level 1: direct STWR with ID=3, medium is ambiguous between speech and writing
* At level 2: reported thought with ID=6 and attributes "nonfact" and "border" with the value "state".

# Structure of the annotations frame, speaker and intexpr
These annotations each consist of a name (frame, speaker, intexpr), the character `.` (dot), and the corresponding ID.

Speaker can have multiple IDs, which are separated by the character `_` (low dash).

Example:

`speaker.12_19`

This token is annotated as speaker with two IDs: 12 and 19 (i.e. this speaker is associated with the STWR annotation with ID=12 as well as the STWR annotation with ID=19).



