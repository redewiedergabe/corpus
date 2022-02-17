This folder contains a collection of all individual annotations of the text samples of core corpus REDEWIEDERGABE (data/main) by different annotators. The material can be used for studying annotator agreement.

A total of 9 different annotators were involved in project REDEWIEDERGABE. The files in this collection are organized in subfolders, each containing the work of one person. The names of the planets of our solar system (plus Pluto!) serve as pseudonyms for the annotators. You can also find these same pseudonyms in the metadata of single-annotated files (data/additional/single_annotated).
For technical reasons, these files were tokenized with a different tool than the core corpus (OpenNLP).

Folders "mercury", "venus", "earth", "mars", "jupiter", "saturn", uranus", "neptune" and "pluto" each contain the text samples annotated by a specific annotator.
Folder "consensus" contains the same text samples and consensus annotation as the core corpus (data/main). In contrast to the core corpus, the text samples are tokenized with OpenNLP so that they can be aligned with the annotations in the planet folders. (NOTE: The xmi files of the main corpus (data/main/xmi) contain OpenNLP Tokens as well (Annotation "Token"), so they can also be used for alignment.)
Folder "resources_xmi" contains the type systems needed to process the XMI files in the "xmi" subfolders of the "consensus" folder and the planet folders.
Folder "resources_xml" contains the RELAX-NG syntax schema that adapts the TEI Module for Linguistic corpora to the annotation schema of project REDEWIEDERGABE and its documentation. It relates to the files in the "xml" subfolders of the "consensus" folder and the planet folders.
"annotators_per_file.tsv" lists the available single-person annotations for all core corpus samples.

For more detailed information please consult the documentation.
