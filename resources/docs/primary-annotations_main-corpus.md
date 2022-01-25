# Primary annotations of the main corpus

folder: [/data/additional/primary](/data/additional/primary)

 Each sample of the [main corpus](/data/main) was annotated independently by two different people. Then, a third person created a consensus annotation on this basis - these are the annotations you find in the main corpus. 
 
 In this collection, we share all single-person annotations for the main corpus samples that were produced over the course of our project. Most of them are the two annotations that served as the basis of the consensus annotation, but some are additional annotations that were created to study annotator agreement. Each annotation was created independently.
  
 A total of 9 different annotators were involved in this project. The files in this collection are organized in sub-folders, each containing the work of one person. The names of the planets of our solar system (plus Pluto!) serve as pseudonyms. You can also find these same pseudonyms in the metadata of [single-annotated files](/data/additional/single_annotated) and the [free indirect sub-corpus](/data/additional/simplified/free_indirect).
 
 In the folder [resources_xml](/data/additional/primary/resources_xml) you find the RELAX-NG syntax and its documentation for the XML version of these files.

 In the folder [resources_xmi](/data/additional/primary/resources_xmi) you find an extended type system for the XMI version of these files.
 
 We provide an overview 'annotators per file' (in [tsv](/data/additional/primary/annotators_per_file.tsv) and [xlsx](/data/additional/primary/annotators_per_file.xlsx) format) that lists the available single-person annotations for all main corpus samples. For 3 samples (rwk_digbib_1134-1, rwk_digbib_1299-1, rwk_digbib_935-1), we can only provide one primary annotation (the second annotation existed during corpus creation, but in an outdated format). 
 
 
 **NOTE**: As the CAB Tokenization is not available for the early primary annotations, we decided to use the [OpenNLP](https://opennlp.apache.org/) Tokenizer for all files in this collection. This should ensure that the files (particularly in tsv and xmi format) can be aligned to calculate annotator agreement scores. CABTokens are still available in many of the XMI files. 
 In the folder [consensus](/data/additional/primary/consensus),  we also provide an alternative tsv version of the main corpus (which contains the consensus annotaion), tokenized with the OpenNLP Tokenizer, that can be aligned with these files. The xmi files of the main corpus contain OpenNLP Tokens as well (Annotation "Token"), so they can also be used for alignment. 
 
 
Click the following links to get familiar with the [annotation structure](annotation_structure.md), [metadata](metadata.md) and the different formats available ([column-based text format](column_based_text_format.md),  [xml-format](xml_format.md),  [xmi-format](xmi_format.md)).


## Annotator agreement
The following table lists the annotator agreement scores for 834 samples of the main corpus (4 samples are missing in this calculation). If more than two primary annotations were available, two were chosen at random. 

| annotations   | Fleiss’ Kappa (type)|  Fleiss’ Kappa (type & medium)           |
|---------------|---------------|---------------|
| all types     | 0.73          | 0.72          |
| only direct   | 0.92          | 0.89          |
| only indirect | 0.73          | 0.68          |
| only reported | 0.49          | 0.47          | 

*There are no scores provided for the types free indirect and indirect free indirect, as those were too infrequent to calculate meaningful scores.*

## Statistics
Distribution of annotators

| annotator | files | tokens | instances |
|-----------|-------|--------|-----------|
| mercury | 188 | 109,029 | 2,508 |
| venus | 68 | 40,149 | 949 |
| earth | 108 | 69,250 | 2,006 |
| mars | 335 | 190,293| 4,646 |
| jupiter | 406 | 237,276 | 8,554 |
| saturn | 344 | 196,622 | 4,908 |
| uranus | 243 | 139,609 | 3,515 |
| neptune | 6 | 3,578 | 109 |
| pluto | 6 | 3,578 | 102 |
| *total* | *1,704* | *989,384* | *27,297* |

Instances of STWR types per annotator

| annotator | direct | indirect | free indirect | indirect/free indirect | reported |
|-----------|--------|----------|---------------|------------------------|----------|
| mercury | 906 | 442 | 47 | 7 | 1,105 |
| venus | 362 | 148 | 28 | 5 | 406 |
| earth | 518 | 339 | 10 | 0 | 1,134 |
| mars | 1,601 | 1,045 | 32 | 28 | 1,940 |
| jupiter | 1,979 | 1,453 | 72 | 8 | 5,042 |
| saturn | 1,715 | 1,199 | 74 | 63 | 1,852 |
| uranus | 1,141 | 736 | 34 | 9 | 1,594 |
| neptune | 18 | 28 | 2 | 1 | 60 |
| pluto | 16 | 34 | 0 | 3 | 49 |
| *total* | *8,256* | *5,424* | *299* | *124* | *13,182* |

