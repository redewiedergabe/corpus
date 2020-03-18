# Primary annotations of the main corpus

 Each sample of the [main corpus](/data/main) was annotated independently by two different people. Then, a third person created a consens annotation on this basis - these are the annotations you find in the main corpus. 
 
 In this collection, we share all single-person annotations for the main corpus samples that were produced over the course of our project. Most of them are the two annotations that served as the basis of the consens annotation, but some are additional annotations that were created to study annotator agreement. Each annotation was created independently.
  
 A total of 9 different annotators were involved in this project. The files in this collection are organized in sub-folders, each containing the work of one person. The names of the planets of our solar system (plus Pluto!) serve as pseudonyms. You can also find these same pseudonyms in the metadata of [single-annotated files](/data/additional/single_annotated) and the [free indirect sub-corpus](/data/additional/simplified/freee_indirect).
 
 We provide a list ([tsv](/data/additional/primary/rwk1_list.tsv) and [xlsx](/data/additional/primary/rwk1_list.xlsx) format that lists the available single-person annotation for all main corpus samples. For 3 samples (rwk_digbib_1134-1, rwk_digbib_1299-1, rwk_digbib_935-1), we can only provide one primary annotation. 
 
 
 **Note**: As the CAB Tokenization is not available for the early primary annotations, we decided to use the OpenNLP Tokenizer for all files in this collection. This should ensure that the files (particularly in tsv and xmi format) can be aligned to calculate annotator agreement scores. CABTokens are still available in many of the XMI files. 
 In the folder [consens](/data/additional/primary/consens),  we also provide an alternative tsv version of the consens annotated main corpus, tokenized with the OpenNLP Tokenizer, that can be aligned with these files. The xmi files of the main corpus contain OpenNLP Tokens as well (Annotation "Token"). 
 
Click the following links to get familiar with the [annotation structure](annotation_structure.md), [metadata](metadata.md) and the different formats available ([column-based text format](column_based_text_format.md),  [xml-format](xml_format.md),  [xmi-format](xmi_format.md)).

## Annotator agreement
The following table lists the annotation agreement scores for 834 samples of the main corpus. If more than two primary annotation was available, two were chosen at random. 4 samples are missing in this calculation.

| annotations   | Fleiss’ Kappa |               |
|---------------|---------------|---------------|
|               | type          | type & medium |
| all types     | 0,73          | 0.72          |
| only direct   | 0,92          | 0.89          |
| only indirect | 0,73          | 0.68          |
| only reported | 0,49          | 0.47          | 


## Statistics

**coming soon**