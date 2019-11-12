# Column based text format 

# General remarks

Folder: [data/txt](https://github.com/redewiedergabe/corpus/tree/master/data/txt)

Corpus metadata is available in the file **rw_corpus_metadata** ([tsv format](https://github.com/redewiedergabe/corpus/blob/master/data/txt/rw_corpus_metadata.tsv) or [Excel format](https://github.com/redewiedergabe/corpus/blob/master/data/txt/rw_corpus_metadata.xlsx))

The corpus consists of separated UTF-8 coded files with the file ending "tsv" (tab-separated values). Each file contains a sample in a column-based format. The columns are separated by tabstops and each line corresponds to one token of the sample (Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de)).

In addition to the annotations added by the Redewiedergabe project, the files also contain morpho-syntactic annotation produced by automatic tools that were not developed by the Redewiedergabe project.

For a more detailed explanation of the annotation structure see [Annotation structure](https://github.com/redewiedergabe/corpus/wiki/Annotation-structure). 

## References:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)

# Columns

| Column | Description                                                                                        | Typ                       |
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

* The character `|` (vertical line) is used as separator, if a token has several annotations of different levels (nested STWR). The first annotation can be interpreted as level=1, the second annotation as level=2 etc. (Maximum nesting depth is 5 in the beta release)
* The character `.` (dot) is used to separate the attributes of a single STWR annotation. The following order is used: **Typ**, **Medium**, **ID**, Nonfact, Border, Prag, Metaph. The three bolded attributes are obligatory, the other four may be missing, if the corresponding attributes are not relevant.
* The attribute border is further specified by a value after the character `=` (equals sign) (e.g. border=state)
* Alternative values are separated by the character `_` (low dash). This can happen for the attributes type (e.g. indirect_freeIndirect) und medium (e.g. speech_thought).

Example:

`direct.speech_writing.3|reported.thought.6.nonfact.border=state`

This token has two overlapping annotations:
* At level 1: direct STWR with ID=3, medium is ambigous between speech and writing
* At level 2: reported thought with ID=6 and attributes "nonfact" and "border" with the value "state".

# Structure of the annotations frame, speaker and intexpr
These annotations each consist of a name (frame, speaker, intexpr), the character `.` (dot), and the corresponding ID.

Speaker can have multiple IDs, which are separated by the character `_` (low dash).

Example:

`speaker.12_19`

This token is annotated as speaker with two IDs: 12 and 19 (i.e. this speaker is associated with the STWR annotation with ID=12 as well as the STWR annotation with ID=19).



