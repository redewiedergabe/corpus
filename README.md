

# Corpus "Rᴇᴅᴇᴡɪᴇᴅᴇʀɢᴀʙᴇ" 


 [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3739239.svg)](https://doi.org/10.5281/zenodo.3739239)

A historical German-language corpus (1840-1919) of fictional and non-fictional texts, annotated for speech, thought and writing representation (STWR). 

The corpus was created by the DFG-funded project "Redewiedergabe - eine literatur- und sprachwissenschaftliche Korpusanalyse" (Leibniz Institute for the German Language / University of Würzburg). Homepage: www.redewiedergabe.de

The following publication complements this technical description with in-depth discussion of corpus design and annotation. Please cite it when using the corpus: 

[Brunner, Annelen / Engelberg, Stefan / Jannidis, Fotis / Tu, Ngoc Duyen Tanja / Weimer, Lukas (2020): Corpus REDEWIEDERGABE, *Proceedings of The 12th Language Resources and Evaluation Conference*, Marseille, pp. 803‑812.](https://www.aclweb.org/anthology/2020.lrec-1.100.pdf)


If you encounter any issues or have any questions, please use [Github's Issues tracker](https://github.com/redewiedergabe/corpus/issues).

Project Redewiedergabe also provides [automatic taggers for German STWR](https://github.com/redewiedergabe/tagger), trained (mostly) on this corpus.

## License

The corpus "Redewiedergabe" is available under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

We ask you to mention [project "Redewiedergabe"](http://www.redewiedergabe.de) regarding the annotation, and [project TextGrid](https://textgrid.de/digitale-bibliothek), [Deutsches Textarchiv](http://www.deutschestextarchiv.de), [Leibniz-Institut für Deutsche Sprache](http://www1.ids-mannheim.de) and [Staats- und Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de) regarding the texts.

## Available Data
### Core corpus

|                            | Samples | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Main corpus](data/main)                | 838     | 489,459 | 12,123         | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3739239.svg)](https://doi.org/10.5281/zenodo.3739239) [Detailed statistical data](resources/docs/main_release_statistics.md)                                                      |
| [Main corpus (Beta release)](data/beta-release) | 619     | 360,974 | 9,451          |   [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2635192.svg)](https://doi.org/10.5281/zenodo.2635192)  [Detailed statistical data](resources/docs/beta_release_statistics.md); [Differences to the final release](resources/docs/differences-main-beta.md)|

### Additional Material
This is a collection of several types of additional annotated material produced by project Redewiedergabe. The material generally follows the same annotation guidelines and is available in the same formats as the main corpus, but has some idiosyncrasies and less quality control. For additional information about the different corpus parts follow the links in the table.    

|                            | Files | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Single-annotated samples](resources/docs/single_annotated_samples.md) |  258    | 150,162 | 4,395          |  Annotations only by a single annotator 
| [Single-annotated full texts (fictional)](resources/docs/full_texts.md) |   18   | 235,493|   6,232        |  Annotations only by a single annotator; **NOTE:** Annotation guidelines differ slightly with respect to *speaker*   
| [Single-annotated full texts (non-fictional)](resources/docs/full_texts.md) |  15    | 84,769 |   1,472        | Annotations only by a single annotator 
| [Indirect full texts](resources/docs/indirect-corpus.md)| 16| 51,864 | 272 | Only instances of *indirect* STWR with a simplified annotation system
| [Free indirect full texts (fictional)](resources/docs/freeindirect-corpus.md) | 142 | 2,647,924 | 2,136 | Only instances of *free indirect* STWR with a simplified annotation system; semi-automated annotation
| [Primary annotations of the core corpus](resources/docs/primary-annotations_main-corpus.md) | 1,704 | 989,384 | 27,297 | Collection of all individual annotations of the core corpus
| [KONVENS 2020 data](resources/docs/data_konvens-paper-2020.md) | | | | Data splits used for the [STWR taggers](https://github.com/redewiedergabe/tagger), as described in the KONVENS 2020 paper 


## Format
The corpus is available in three different formats:
* [Column-based text format](resources/docs/column_based_text_format.md)
* [XML format](resources/docs/xml_format.md)
* [XMI format](resources/docs/xmi_format.md) (Not available for the Beta release)

NOTE: The XMI files are compatible with the free annotation tool [ATHEN](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen) (developed by Markus Krug in the [Kallimachos project](http://kallimachos.de)) and its [STWR view](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen/blob/master/de.uniwue.mk.athen/releng/de.uniwue.mk.athen.docu/STWRView.md) (developed by Tanja Tu).

## Project
The corpus "Redewiedergabe" is created by the DFG-funded project "Redewiedergabe. Eine literatur- und sprachwissenschaftliche Korpusanalyse" in a cooperation between [Leibniz-Institut für Deutsche Sprache, Mannheim](http://www1.ids-mannheim.de/lexik/home.html) ([Abteilung Lexik](http://www1.ids-mannheim.de/lexik/home.html)) and [Universität Würzburg](https://www.uni-wuerzburg.de) ([Lehrstuhl für Computerphilologie und Neuere Deutsche Literaturgeschichte](https://www.germanistik.uni-wuerzburg.de/lehrstuehle/computerphilologie)). 

Project members: [Annelen Brunner](http://www1.ids-mannheim.de/lexik/personal/brunner.html) (IDS Mannheim), [Stefan Engelberg](http://www1.ids-mannheim.de/lexik/personal/engelberg.html) (IDS Mannheim), [Fotis Jannidis](http://www.jannidis.de/person.html) (Universität Würzburg), [Ngoc Duyen Tanja Tu](https://perso.ids-mannheim.de/seiten/tu.html) (IDS Mannheim), [Lukas Weimer](https://www.germanistik.uni-wuerzburg.de/lehrstuehle/computerphilologie/mitarbeiter/weimer/) (Universität Würzburg).

In addition, the following people participated in the annotation: Sarah Gorke, Anna Hartmann, Janne Lorenzen, Christoph Peterek, Laura Schäfer, Lisa Sergel and Theresa Valta.

Project homepage: [www.redewiedergabe.de](http://www.redewiedergabe.de)

A list of all publications can be found [here](resources/docs/publications.md).

## Text sources
The corpus "Redewiedergabe" is a historical corpus of fictional and non-fictional texts. These texts were published between 1840-1919 and were compiled from the following three sources: 
* Narrative texts from the 'Digitalen Bibliothek', converted to TEI format by [project TextGrid](https://textgrid.de/digitale-bibliothek)
* Texts from the magazine "Die Grenzboten", digitized by [Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de/grenzboten) (Source: Die Grenzboten: Zeitschrift für Politik, Literatur und Kunst. Berlin: Dt. Verl, 1841-1922. Staats- und Universitätsbibliothek Bremen, Ac 7155 Public Domain Mark 1.0), TEI structuring by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#grenzboten) and OCR correction by project "Redewiedergabe".
* Texts from the "Mannheimer Korpus Historischer Zeitungen und Zeitschriften" (Mannheim corpus of historical newspapers and magazines), collected by the [Leibniz-Institut für Deutsche Sprache](https://repos.ids-mannheim.de/mkhz-beschreibung.html) and converted by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#mkhz).

The corpus does not consist of complete texts but of text samples. The sample length is at least 500 tokens for texts from the Digitale Bibliothek and at least 200 tokens for newspaper/magazine texts. The samples are drawn randomly from the available material with following additional rules: For the texts from the Digitale Bibliothek, it was enforced that material by each author was considered evenly within a decade. Accordingly, for the texts from MKHZ it was enforced that the different newspapers/magazines were considered evenly. Thus we prevented authors or newspapers with little material from dropping out entirely during the sampling process.
 
Each sample contains metadata with information about the publication time, text type, fictionality status. Author and title are provided if available (more information: [Metadata](resources/docs/metadata.md)).  

## Annotation
The corpus contains detailed annotation of instances of speech, thought and writing representation (STWR). We distinguish four main types: direct STWR (_Er sagte: "Ich bin hungrig."_), indirect STWR (_Er sagte, er sei hungrig._), free indirect STWR (_Wo sollte er jetzt etwas zu essen herbekommen?_) and reported STWR (_Er sprach über Restaurants._), as well as the main media speech, thought and writing. In addition to that, we annotate attributes like embedding level, non-factual STWR, borderline cases, pragmatic and metaphoric use, as well as frames, introductory expressions and speakers. 

Each sample of the main corpus was annotated independently by two different people. The final annotation was created by a third person on the basis of those annotations. The underlying first annotations are also available (see [primary annotations](resources/docs/primary-annotations_main-corpus.md)).

The detailed annotation guidelines are available at [redewiedergabe.de/richtlinien/richtlinien.html](http://redewiedergabe.de/richtlinien/richtlinien.html) (in German). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2634994.svg)](https://doi.org/10.5281/zenodo.2634994)

An overview over the structure of the annotations is available at [Annotation structure](resources/docs/annotation_structure.md).
