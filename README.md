

# Corpus "Rᴇᴅᴇᴡɪᴇᴅᴇʀɢᴀʙᴇ" <img src="resources/docs/redewiedergabe_logo.png" width="40" height="40"/>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2635192.svg)](https://doi.org/10.5281/zenodo.2635192)
 [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

A corpus annotated for speech, thought and writing representation by the DFG-funded project "Redewiedergabe - eine literatur- und sprachwissenschaftliche Korpusanalyse" (Leibniz Institute for the German Language / University of Würzburg). 

Homepage: www.redewiedergabe.de

Detailed information about the corpus can be found in the [Wiki](https://github.com/redewiedergabe/corpus/wiki/The-%22Redewiedergabe%22-corpus).

**Note**: The corpus is currently on its beta release and will be extended in the future. If you encounter any issues or have any questions, please use [Github's Issues tracker](https://github.com/redewiedergabe/corpus/issues).


# Project
The "Redewiedergabe" corpus is created by the DFG-funded project "Redewiedergabe. Eine literatur- und sprachwissenschaftliche Korpusanalyse" in a cooperation between [Leibniz-Institut für Deutsche Sprache, Mannheim](http://www1.ids-mannheim.de/lexik/home.html) ([Abteilung Lexik](http://www1.ids-mannheim.de/lexik/home.html)) and [Universität Würzburg](https://www.uni-wuerzburg.de) ([Lehrstuhl für Computerphilologie und Neuere Deutsche Literaturgeschichte](https://www.germanistik.uni-wuerzburg.de/no_cache/lehrstuehle/computerphilologie)). 

Project members: [Annelen Brunner](http://www1.ids-mannheim.de/lexik/personal/brunner.html) (IDS Mannheim), [Stefan Engelberg](http://www1.ids-mannheim.de/lexik/personal/engelberg.html) (IDS Mannheim), [Fotis Jannidis](http://www.jannidis.de/person.html) (Universität Würzburg), [Ngoc Duyen Tanja Tu](https://perso.ids-mannheim.de/seiten/tu.html) (IDS Mannheim), [Lukas Weimer](https://www.germanistik.uni-wuerzburg.de/lehrstuehle/computerphilologie/mitarbeiter/weimer/) (Universität Würzburg).

In addition, the following people participated in the annotation: Sarah Gorke, Anna Hartmann, Janne Lorenzen, Christoph Peterek, Laura Schäfer, Lisa Sergel and Theresa Valta.

Project homepage: [www.redewiedergabe.de](http://www.redewiedergabe.de)

# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />The "Redewiedergabe" corpus is available under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

We ask you to mention [project "Redewiedergabe"](http://www.redewiedergabe.de) regarding the annotation, and [project TextGrid](https://textgrid.de/digitale-bibliothek), [Deutsches Textarchiv](http://www.deutschestextarchiv.de), [Leibniz-Institut für Deutsche Sprache](http://www1.ids-mannheim.de) and [Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de) regarding the texts.

# Text sources
The "Redewiedergabe" corpus is a historical corpus of fictional and non-fictional texts. These texts were published between 1840-1920 and were compiled from the following three sources: 
* Narrative texts from the 'Digitalen Bibliothek', converted to TEI format by [project TextGrid](https://textgrid.de/digitale-bibliothek)
* Texts from the magazine "Die Grenzboten", digitized by [Universitätsbibliothek Bremen](http://brema.suub.uni-bremen.de/grenzboten) (Source: Die Grenzboten: Zeitschrift für Politik, Literatur und Kunst. Berlin: Dt. Verl, 1841-1922. Staats- und Universitätsbibliothek Bremen, Ac 7155 Public Domain Mark 1.0), TEI structuring by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#grenzboten) and OCR correction by project "Redewiedergabe".
* Texts from the "Mannheimer Korpus Historischer Zeitungen und Zeitschriften" (Mannheim corpus of historical newspapers and magazines), collected by the [Leibniz-Institute für Deutsche Sprache](https://repos.ids-mannheim.de/mkhz-beschreibung.html) and converted by [Deutsches Textarchiv](http://www.deutschestextarchiv.de/doku/textquellen#mkhz).

The corpus does not consist of complete texts but of text samples. The sample length is at least 500 tokens for texts from the Digitale Bibliothek and at least 200 tokens for newspaper/magazine texts. The samples are drawn randomly from the available material with following additional rules: For the texts from the Digitale Bibliothek, it was enforced that material by each author was considered evenly within a decade. Accordingly, for the texts from MKHZ it was enforced that the different newspapers/magazines were considered evenly. Thus we prevented authors or newspapers with little material from dropping out entirely during the sampling process.
 
Each sample contains metadata with information about the publication time, text type, fictionality status and author and title if available (more information: [Metadata](https://github.com/redewiedergabe/corpus/blob/master/resources/docs/metadata.md).  

# Annotation
The corpus contains detailed annotation of instances of speech, thought and writing representation (STWR). We distiguish four main types: direct STWR (_Er sagte: "Ich bin hungrig."_), indirect STWR (_Er sagte, er sei hungrig._), free indirect STWR (_Wo sollte er jetzt etwas zu Essen herbekommen?_) and reported STWR (_Er sprach über Restaurants._), as well as the main media speech, thought and writing. In addition to that, we annotate attributes like embedding level, non-factual STWR, borderline cases, pragmatic and metaphoric use, as well as frames, introductory expressions and speakers. 

Each corpus sample was annotated independently by two different people. The final annotation was created by a third person on the basis of those annotations. 

The detailed annotation guidelines are available at [redewiedergabe.de/richtlinien/richtlinien.html](http://redewiedergabe.de/richtlinien/richtlinien.html) (in German).

An overview over the structure of the annotations is available at [Annotation structure](https://github.com/redewiedergabe/corpus/blob/master/resources/docs/annotation_structure.md).

# Size
At the moment, the beta release of the corpus is available. At the end of the project (spring 2020), the corpus will be extended and additional annotated material will be made available.

The beta release includes 619 samples and 360,974 tokens. 9,451 STWR instances have been annotated, as well as additional information like frames, introductory expressions and speakers. 

[Detailed statistical data](https://github.com/redewiedergabe/corpus/wiki/Beta-release-statistics)

# Format
The corpus is available in two different formats:
* [Column-based text format](https://github.com/redewiedergabe/corpus/wiki/Column-based-text-format)
* [XML format](https://github.com/redewiedergabe/corpus/wiki/XML)

