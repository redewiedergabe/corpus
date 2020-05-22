## Data for the models described in the KONVENS 2020 paper 

[Data download](../../data/additional/data_konvens-paper-2020.zip) 
(zip, ~15.5 MB)

This download contains the exact training, validation and test corpora used to train and evaluate the taggers 
for direct, indirect and reported STWR described in

**Brunner, Annelen / Tu, Ngoc Duyen Tanja / Weimer, Lukas / Jannidis, Fotis (2020): To BERT or
not to BERT – Comparing contextual embeddings in a deep learning architecture for the automatic
recognition of four types of speech, thought and writing representation, Proceedings of the 5th 
SwissText & 16th KONVENS Joint Conference.** *(to appear in June 2020)*

The resulting models are available via our [Tagger page](https://github.com/redewiedergabe/tagger).

The data is concatenated into a single file for each corpus. The value 'EOF' in the token column 
marks the end of a file. The corpora for direct, indirect and reported contain the same data, but 
have different labels (according to their STWR type).

All data in these files is part of corpus REDEWIEDERGABE (main corpus & additional material).
There might be some slight discrepancies in the file names and annotations, as these files were
created before the final cleanup of corpus REDEWIEDERGABE. The annotation is 
simplified to just STWR type in this version of the data.

Unfortunately we cannot provide the exact data for the free indirect model due  to copyright restrictions 
on the modern texts. The historical data used for the free indirect model ist available [here](../../data/additional/simplified/free_indirect).

**NOTE:** We provide this version of the data to allow you to recreate the research described in the KONVENS 2020 paper. 
If you are a researcher working on STWR recognition, we strongly encourage you to take a look at the original files of [corpus REDEWIEDERGABE](../../README.md), as they offer a richer annotation and opportunities to develop recognizers that can deal with additional aspects of STWR, such as framing phrases, speaker and detecting the medium of the STWR (speech, thought or writing).
