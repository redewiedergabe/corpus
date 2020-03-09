

# Corpus "Rᴇᴅᴇᴡɪᴇᴅᴇʀɢᴀʙᴇ" 


 [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

A historical German-language corpus (1840-1920) of fictional and non-fictional texts, annotated for speech, thought and writing representation 

The corpus was created by the DFG-funded project "Redewiedergabe - eine literatur- und sprachwissenschaftliche Korpusanalyse" (Leibniz Institute for the German Language / University of Würzburg). Homepage: www.redewiedergabe.de

If you encounter any issues or have any questions, please use [Github's Issues tracker](https://github.com/redewiedergabe/corpus/issues).

## Available Data

|                            | Samples | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Main corpus](data/main)                | 838     | 489,459 | 12,123         | [Detailed statistical data](resources/docs/main_release_statistics.md)                                                      |
| [Main corpus (Beta release)](data/beta-release) | 619     | 360,974 | 9,451          |   [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2635192.svg)](https://doi.org/10.5281/zenodo.2635192)  [Detailed statistical data](resources/docs/beta_release_statistics.md); [Differences to the final release](resources/docs/differences-main-beta.md)|

### Additional Material
This is a collection of several types of additional annotated material produced by project Redewiedergabe. The material generally follows the same annotation guidelines and is available in the same formats as the main corpus, but has some idiosyncracies and less quality control. For additional information about the different corpus parts follow the links in the table.    

|                            | Files | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Single-annotated samples](data/additional/single_annotated/samples) |  256    | 149,133 | 4,353          |   [Description](resources/docs/single_annotated_samples.md)
| [Single-annotated full texts (fictional)](data/additional/single_annotated/full_fict) |   17   | 218,940|   5,931        |[Description](resources/docs/full_texts.md) **Note**: Annotation guidelines differ slightly with respect to *speaker*   
| [Single-annotated full texts (non-fictional)](data/additional/single_annotated/full_nonfict) |  12    | 61,263|   1,233        |  [Description](resources/docs/full_texts.md)
| [Single-annotated free indirect full texts (fictional)](TODO) | 142 |  |  | [Description](resources/docs/free-indirect_corpus.md)

More additional material will be added in the future.

## Format
The corpus is available in three different formats:
* [Column-based text format](resources/docs/column_based_text_format.md)
* [XML format](resources/docs/xml_format.md)
* [XMI format](resources/docs/xmi_format.md) (Not available for the Beta release)

NOTE: The XMI files are compatible with the free anntotation tool [ATHEN](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen) (developed by Markus Krug in the [Kallimachos project](http://kallimachos.de)) and its [STWR view](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen/blob/master/de.uniwue.mk.athen/releng/de.uniwue.mk.athen.docu/STWRView.md) (developed by Tanja Tu).

# Project
The "Redewiedergabe" corpus is created by the DFG-funded project "Redewiedergabe. Eine literatur- und sprachwissenschaftliche Korpusanalyse" in a cooperation between [Leibniz-Institut für Deutsche Sprache, Mannheim](http://www1.ids-mannheim.de/lexik/home.html) ([Abteilung Lexik](http://www1.ids-mannheim.de/lexik/home.html)) and [Universität Würzburg](https://www.uni-wuerzburg.de) ([Lehrstuhl für Computerphilologie und Neuere Deutsche Literaturgeschichte](https://www.germanistik.uni-wuerzburg.de/no_cache/lehrstuehle/computerphilologie)). 

Project members: [Annelen Brunner](http://www1.ids-mannheim.de/lexik/personal/brunner.html) (IDS Mannheim), [Stefan Engelberg](http://www1.ids-mannheim.de/lexik/personal/engelberg.html) (IDS Mannheim), [Fotis Jannidis](http://www.jannidis.de/person.html) (Universität Würzburg), [Ngoc Duyen Tanja Tu](https://perso.ids-mannheim.de/seiten/tu.html) (IDS Mannheim), [Lukas Weimer](https://www.germanistik.uni-wuerzburg.de/lehrstuehle/computerphilologie/mitarbeiter/weimer/) (Universität Würzburg).

In addition, the following people participated in the annotation: Sarah Gorke, Anna Hartmann, Janne Lorenzen, Christoph Peterek, Laura Schäfer, Lisa Sergel and Theresa Valta.

Project homepage: [www.redewiedergabe.de](http://www.redewiedergabe.de)

# License

The "Redewiedergabe" corpus is available under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

We ask you to mention [project "Redewiedergabe"](http://www.redewiedergabe.de) regarding the annotation, and [project TextGrid](https://textgrid.de/digitale-bibliothek), [Deutsches Textarchiv](http://www.deutschestextarchiv.de), [Leibniz-Institut für Deutsche Sprache](http://www1.ids-mannheim.de) and [Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de) regarding the texts.

# Text sources
The "Redewiedergabe" corpus is a historical corpus of fictional and non-fictional texts. These texts were published between 1840-1920 and were compiled from the following three sources: 
* Narrative texts from the 'Digitalen Bibliothek', converted to TEI format by [project TextGrid](https://textgrid.de/digitale-bibliothek)
* Texts from the magazine "Die Grenzboten", digitized by [Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de/grenzboten) (Source: Die Grenzboten: Zeitschrift für Politik, Literatur und Kunst. Berlin: Dt. Verl, 1841-1922. Staats- und Universitätsbibliothek Bremen, Ac 7155 Public Domain Mark 1.0), TEI structuring by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#grenzboten) and OCR correction by project "Redewiedergabe".
* Texts from the "Mannheimer Korpus Historischer Zeitungen und Zeitschriften" (Mannheim corpus of historical newspapers and magazines), collected by the [Leibniz-Institute für Deutsche Sprache](https://repos.ids-mannheim.de/mkhz-beschreibung.html) and converted by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#mkhz).

The corpus does not consist of complete texts but of text samples. The sample length is at least 500 tokens for texts from the Digitale Bibliothek and at least 200 tokens for newspaper/magazine texts. The samples are drawn randomly from the available material with following additional rules: For the texts from the Digitale Bibliothek, it was enforced that material by each author was considered evenly within a decade. Accordingly, for the texts from MKHZ it was enforced that the different newspapers/magazines were considered evenly. Thus we prevented authors or newspapers with little material from dropping out entirely during the sampling process.
 
Each sample contains metadata with information about the publication time, text type, fictionality status and author and title if available (more information: [Metadata](resources/docs/metadata.md)).  

# Annotation
The corpus contains detailed annotation of instances of speech, thought and writing representation (STWR). We distiguish four main types: direct STWR (_Er sagte: "Ich bin hungrig."_), indirect STWR (_Er sagte, er sei hungrig._), free indirect STWR (_Wo sollte er jetzt etwas zu Essen herbekommen?_) and reported STWR (_Er sprach über Restaurants._), as well as the main media speech, thought and writing. In addition to that, we annotate attributes like embedding level, non-factual STWR, borderline cases, pragmatic and metaphoric use, as well as frames, introductory expressions and speakers. 

Each sample of the main corpus was annotated independently by two different people. The final annotation was created by a third person on the basis of those annotations. 

The detailed annotation guidelines are available at [redewiedergabe.de/richtlinien/richtlinien.html](http://redewiedergabe.de/richtlinien/richtlinien.html) (in German). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2634995.svg)](https://doi.org/10.5281/zenodo.2634995)

An overview over the structure of the annotations is available at [Annotation structure](resources/docs/annotation_structure.md).


