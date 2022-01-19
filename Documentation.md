

# Corpus "Rᴇᴅᴇᴡɪᴇᴅᴇʀɢᴀʙᴇ" 
```
License: CC BY-NC-SA 4.0 

DOI: 10.5281/zenodo.3739239
```

A historical German-language corpus (1840-1920) of fictional and non-fictional texts, annotated for speech, thought and writing representation 

The corpus was created by the DFG-funded project "Redewiedergabe - eine literatur- und sprachwissenschaftliche Korpusanalyse" (Leibniz Institute for the German Language / University of Würzburg). Homepage: www.redewiedergabe.de

Please cite the following publication, if you use the corpus: 

[Brunner, Annelen / Engelberg, Stefan / Jannidis, Fotis / Tu, Ngoc Duyen Tanja / Weimer, Lukas (2020): Corpus REDEWIEDERGABE, *Proceedings of The 12th Language Resources and Evaluation Conference*, Marseille, pp. 796‑805.](https://www.aclweb.org/anthology/2020.lrec-1.100.pdf)


Project Redewiedergabe also provides [automatic taggers for German STWR](https://github.com/redewiedergabe/tagger), trained (mostly) on this corpus.

# Available Data
## Core corpus

|                            | Samples | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Main corpus](data/main)                | 838     | 489,459 | 12,123         |  [Detailed statistical data](#main-release-statistics)                                                      |
## Additional Material
This is a collection of several types of additional annotated material produced by project Redewiedergabe. The material generally follows the same annotation guidelines and is available in the same formats as the main corpus, but has some idiosyncracies and less quality control. For additional information about the different corpus parts follow the links in the table.    

|                            | Files | Tokens  | STWR instances | Notes                                                   |
|----------------------------|---------|---------|----------------|---------------------------------------------------------|
| [Single-annotated samples](resources/docs/single_annotated_samples.md) |  258    | 150,162 | 4,395          |  Annotations only by a single annotator 
| [Single-annotated full texts (fictional)](resources/docs/full_texts.md) |   18   | 235,493|   6,232        |  Annotations only by a single annotator; **Note:** Annotation guidelines differ slightly with respect to *speaker*   
| [Single-annotated full texts (non-fictional)](resources/docs/full_texts.md) |  15    | 84,769 |   1,472        | Annotations only by a single annotator 
| [Indirect full texts](resources/docs/indirect-corpus.md)| 16| 51,864 | 272 | Only instances of *indirect* STWR with a simplified annotation system
| [Free indirect full texts (fictional)](resources/docs/freeindirect-corpus.md) | 142 | 2,647,924 | 2,136 | Only instances of *free indirect* STWR with a simplified annotation system; semi-automated annotation
| [Primary annotations of the core corpus](resources/docs/primary-annotations_main-corpus.md) | 1,704 | 989,384 | 27,297 | Collection of all individual annotations of the core corpus


# Format
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

# Publications

Most recent publication: [Brunner, Annelen/Engelberg, Stefan/Jannidis, Fotis/Tu, Ngoc Duyen Tanja/Weimer, Lukas (2020): Corpus REDEWIEDERGABE, *Proceedings of The 12th Language Resources and Evaluation Conference*, Marseille.](https://www.aclweb.org/anthology/2020.lrec-1.100.pdf)

A complete list of all publications can be found [here](resources/docs/publications.md).

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

Each sample of the main corpus was annotated independently by two different people. The final annotation was created by a third person on the basis of those annotations. The underlying first annotations are also available under "additional material".

The detailed annotation guidelines are available at [redewiedergabe.de/richtlinien/richtlinien.html](http://redewiedergabe.de/richtlinien/richtlinien.html) (in German). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2634995.svg)](https://doi.org/10.5281/zenodo.2634995)

An overview over the structure of the annotations is available at [Annotation structure](resources/docs/annotation_structure.md).


# Main release statistics

The following statistics are for the main release of the "Redewiedergabe" corpus. Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de) (see also [Column-based text format](column_based_text_format.md)).

## Samples and tokens

In total, the corpus contains 838 samples and 489,459 tokens.

| Decade | fictional (samples) | fictional (tokens) | non-fictional (samples) | non-fictional (tokens) | all samples | all tokens |
|--------|---------------------|--------------------|---------------------------|--------------------------|----------------|---------------|
| 1840   | 49                  | 30,728             | 55                        | 30,233                   | 104             | 60,961        |
| 1850   | 50                  | 30,258             | 57                        | 30,426                   | 107             | 60,684        |
| 1860   | 50                  | 31,058             | 54                        | 31,420                   | 104             | 62,478        |
| 1870   | 50                  | 30,436             | 53                        | 30,568                   | 103             | 61,004        |
| 1880   | 48                  | 30,251             | 56                        | 30,678                   | 104             | 60,929        |
| 1890   | 49                  | 30,963             | 55                        | 30,273                   | 104             | 61,236        |
| 1900   | 50                  | 30,567             | 54                        | 30,272                   | 104             | 60,839        |
| 1910   | 49                  | 30,430             | 59                        | 30,898                   | 108             | 61,477        |
| total | 395                 | 244,691            | 443                       | 244,768                  | 838            | 489,459       |

## STWR instances
The following tables list the number of annotated STWR instances in the corpus. These instances vary greatly in length, between one token (possible for STWR types direct and reported) and several sentences (possible for STWR types direct, freeIndirect and indirect/freeIndirect.)

Note that there are also samples that do not contain any instances. These samples were not excluded to guarantee representativity.

### STWR types
| Type                    | Number of instances | Percent of all annotated STWR instances|
|------------------------|--------|---------|
| direct                 | 4166   | 33.2%   |
| indirect               | 2669   | 21.3%   |
| free indirect          |  136   | 1.1%    |
| reported               | 5431   | 43.3%   |
| indirect/free indirect |  131   | 1.0%    |
| total                 | 12,533  |         |

### STWR medium
| Medium  | Number of instances | Percent of all annotated STWR instances |
|---------|--------|---------|
| speech  | 8077   | 64.4%   |
| thought | 2917   | 23.3%   |
| writing | 1129   | 9.0%    |
| ambig   | 410    | 3.3%    |
| total  | 12,533   |         |

### Average length of instances, in relation to STWR type and fictionality

|                    | number of instances | average length of instances | number of instances | average length of instances |
|--------------------|---------------------|-----------------------------|---------------------|-----------------------------|
|                    | fictional           | fictional                   | non-fictional       | non-fictional               |
| direct             | 3527                | 22.2                        | 639                 | 39.5                        |
| indirect           | 1424                | 12.4                        | 1245                | 18.4                        |
| free ind           | 132                 | 26.4                        | 4                   | 14.0                        |
| indirect/ free ind | 65                  | 32.8                        | 66                  | 31.7                        |
| reported           | 2778                | 8.0                         | 2653                | 11.2                        |

The average length varies between ST&WR types and between fictional vs. non-fictional texts. While _free indirect_ and _indirect/free indirect_ are too infrequent to draw robust conclusions, it is interesting to note that for the three remaining types the instances in non-fictional texts are longer on average. 

### STWR token percentages

The graphics show the distribution of types and media in fictional vs. non-fictional samples, based on tokens.

#### STWR types

![rw_Types](/resources/docs/img/rw_type.png)

Direct and free indirect ST&WR are clearly more common in fictional texts. Free indirect even occurs almost exclusively there, but is very infrequent in general, due to the historical nature of our corpus. Indirect and reported ST&WR on the other hand are more frequent in non-fictional texts, though the difference is not as pronounced.

#### STWR medium

![rw_Media](/resources/docs/img/rw_medium.png)

The graphic only shows the most frequent ambiguous category "speech/writing" (ambiguous between speech and writing). The other ambiguous combinations are much less frequent.

Speech representation is dominant in fictional texts and writing in non-fictional ones. The latter is due to book reviews and to written communication often being a topic in news stories. The high percentage of speech/writing also indicates that the medium tends to be underspecified and probably considered less important than the represented content in non-fiction.  

## Text types

![text types](/resources/docs/img/text_type.png)

The graphic shows the distribution of the text types within the samples drawn from MKHZ and ‘Die Grenzboten’. Note the high number of narratives found in these sources. 13.2% of our fictional samples originate from newspapers and magazines where fiction was part of the feuilleton.

# Single-annotated samples

Folder: [data/additional/single_annotated/samples](../../data/additional/single_annotated/samples)

This is a collection of fictional and non-fictional samples that follow the same guidelines as the samples of the main corpus. The only difference is that the annotation was performed by only one annotator with no additional quality control. 

The collection is roughly balanced for fictional vs. non-fictional as well as for decades. 

Click the following links to get familiar with the [annotation structure](annotation_structure.md), [metadata](metadata.md) and the different formats available ([column-based text format](column_based_text_format.md),  [xml-format](xml_format.md),  [xmi-format](xmi_format.md)).

## Statistics

| decade | samples | tokens | instances |
|--------|---------|--------|-----------|
| 1840   | 47      | 24,729 |  |
| 1850   | 35      | 19,273 |  |
| 1860   | 44      | 26,487 |  |
| 1870   | 33      | 19,263 |  |
| 1880   | 20      | 12,347 |  |
| 1890   | 23      | 14,243 |  |
| 1900   | 34      | 20,481 |  |
| 1910   | 22      | 13,339 |  |
| total  | 258     | 150,162| 4,395 |

# Single-annotated full texts
This is a collection of fictional and non-fictional complete texts, annotated according to the guidelines of the project Redewiedergabe (with some caveats regarding full texts, see below). The annotation was performed by only one annotator with no additional quality control. 

In total, this collection consists of 33 files with 320,262 tokens.

Click the following links to get familiar with the [annotation structure](annotation_structure.md), [metadata](metadata.md) and the different formats available ([column-based text format](column_based_text_format.md),  [xml-format](xml_format.md),  [xmi-format](xmi_format.md)).

## Fictional full texts
Folder: [data/additional/single_annotated/full_fict](../../data/additional/single_annotated/full_fict)

This collection consists of complete narrative texts. The source was [Digitale Bibliothek](https://textgrid.de/digitale-bibliothek).

**NOTE**: The annotation guidelines regarding the **speaker** annotation have been adjusted for some of the texts in the following way: For the forms *direct* and *indirect* only real character names (or other content words unambigously refering to a character) were annotated as *speaker*, even if they were far away from the corresponding ST&WR instance. This change was made to be able to assign the direct and indirect representations more precisely to a character and thus allow for evaluations of the character's representation in the text. 

This change affected only the following texts: *Der Gefangene*, *Die Doppelgängerin*, *Die Judenbuche*, *Der arme Spielmann*, *Das Erdbeerimareili*, *Bergmilch*, *Phosphorus Hollunder*, *Die schwarze Galeere*, *Die zwölf Apostel*, *Eine Malerarbeit* and *Der Leuchtturm von Livorno*.

### Statistics
(Titles in bold indicate adjusted **speaker** annotation)

| filename | author | title | year | tokens |
|----------|--------|-------|------|--------|
| rwz_full_digbib_5004 | Malsberg, Otto Freiherr von der | **Der Gefangene** | 1822 | 10,754 |
| rwz_full_digbib_5007 | Ungern-Sternberg, Alexander von | **Die Doppelgängerin** | 1834 | 9,685 |
| rwz_full_digbib_2473 | Poe, Edgar Allan | Hinab in den Maelström | 1841 | 7,288 |
| rwz_full_digbib_1136 | Droste-Hülshoff, Annette von | **Die Judenbuche** | 1842 | 20,124 |
| rwz_full_digbib_1199 | Grillparzer, Franz | **Der arme Spielmann** | 1847 | 17,966 |
| rwz_full_digbib_3228 | Wildermuth, Ottilie | Aus dem Leben einer Hausfrau der neuen Zeit | 1847 | 8,125 |
| rwz_full_digbib_5002 | Gotthelf, Jeremias | **Das Erdbeerimareili** | 1850 | 18,447 |
| rwz_full_digbib_5006 | Stifter, Adalbert | **Bergmilch** | 1853 | 11,429 |
| rwz_full_digbib_5001 | François, Louise von | **Phosphorus Hollunder** | 1857 | 16,798 |
| rwz_full_digbib_5005 | Raabe, Wilhelm | **Die schwarze Galeere** | 1861 | 19,008 |
| rwz_full_digbib_2649 | Riehl, Wilhelm Heinrich von | Amphion | 1862 | 9,640 |
| rwz_full_digbib_5003 | Marlitt, E. | **Die zwölf Apostel** | 1865 | 23,856 |
| rwz_full_digbib_3153 | Storm, Theodor | **Eine Malerarbeit** | 1867 | 11,447 |
| rwz_full_digbib_5000 | Eckstein, Ernst | **Der Leuchtturm von Livorno** | 1871 | 10,809 |
| rwz_full_digbib_3152 | Storm, Theodor | Eine Halligfahrt | 1871 | 10,075 |
| rwz_full_digbib_1340 | Keller, Gottfried | Kleider machen Leute | 1874 | 16,553 |
| rwz_full_digbib_1208 | Heyking, Elisabeth von | Gewesen | 1905 | 6,423 |
| rwz_full_digbib_2632 | Reventlow, Franziska Gräfin zu | Das Logierhaus "Zur schwankenden Weltkugel" | 1917 | 7,066 |
| **total** | **18 files** |  |  | **235,493** |



## Non-fictional full texts
Folder: [data/additional/single_annotated/full_nonfict](../../data/additional/single_annotated/full_nonfict)

This collection consists of complete magazine and newspaper articles. The sources were the journal ['Die Grenzboten'](http://www.deutschestextarchiv.de/doku/textquellen#grenzboten) and different periodicals from the [Mannheimer Korpus Historischer Zeitungen und Zeitschriften](http://www.deutschestextarchiv.de/doku/textquellen#mkhz). 

### Statistics

| filename | title | periodical | year | tokens |
|----------|-------|------------|------|--------|
| rwz_full_grenz_13 | Der Musikunterricht in Elementarschulen in Deutschland und Frankreich | Die Grenzboten | 1842 | 9,240 |
| rwz_full_mkhz_599 | - | Allgemeine Auswanderungs-Zeitung | 1847 | 4,514 |
| rwz_full_mkhz_336 | - | Allgemeine Auswanderungs-Zeitung | 1848 | 3,368 |
| rwz_full_mkhz_1098 | Die deutsche Kolonie Santa Cruz in der Provinz Rio Grande do Sul in Brasilien | Deutsche Auswanderer-Zeitung | 1852 | 3,175 |
| rwz_full_grenz_3721 | Regierung und Volk in Neapel | Die Grenzboten | 1856 | 7,041 |
| rwz_full_grenz_6595 | Die Petrussagen | Die Grenzboten | 1867 | 5,833 |
| rwz_full_grenz_7300 | Polnischer Monatsbericht | Die Grenzboten | 1869 | 7,071 |
| rwz_full_mkhz_5884 | - | Social-Politische Blätter | 1873 | 5,118 |
| rwz_full_grenz_10479 | Die Tragik in Werken der hellenischen Plastik | Die Grenzboten | 1880 | 6,609 |
| rwz_full_mkhz_10107 | Die Versammlung der deutschen Vertrauensmänner in Brünn | Mährisches Tageblatt | 1887 | 6,418 |
| rwz_full_mkhz_10440 | Die 15. Hauptversammlung des Deutschen Schulvereins | Mährisches Tageblatt | 1895 | 6,257 |
| rwz_full_grenz_18399 | Musikalische Zeitfragen | Die Grenzboten | 1902 | 7,195 |
| rwz_full_mkhz_2733 | Zur Beurteilung der jüngsten Schulkonflikte | Europa. Wochenschrift für Kultur und Politik | 1905 | 3,356 |
| rwz_full_grenz_20389 | Goethe und die Boisserée | Die Grenzboten | 1907 | 4,483 |
| rwz_full_grenz_23110 | Die Stellung Belgiens zum alten Reiche | Die Grenzboten | 1915 | 5,091 |
| **total** | **15 files** | - | - | **84,769** |


# Indirect corpus

This subcorpus was created to generate training data for our recognizers, especially for **indirect STWR**. The annotation system is strongly reduced, *only* specifying the type indirect (without medium or attributes).  Frame, intExpr and speaker are not annotated.

To create this corpus, the texts were  tagged by one of our automatic indirect recognizers. The annotation was then corrected by humans, who checked the whole texts, so false negatives were corrected as well. Annotation quality should therefore be comparable to the [single-annotated files](/data/additional/single_annotated).

The indirect corpus is only available in [column-based text format](/resources/docs/column_based_text_format.md) in a reduced form (only tokens and category).

## Statistics

This corpus consists of **16 files**, containing **51,864 tokens** with	**272 instances** of indirect STWR.

A list of all texts including author, title, year of publication and information on fictionality be found [here](/data/additional/simplified/indirect/txt/metadata_indirect.tsv).

# Free indirect corpus

folder: [/data/additional/simplified/free_indirect](/data/additional/simplified/free_indirect)

This subcorpus was created to generate training data training data for our recognizers specifically for **free indirect STWR**. The annotation system is strongly reduced, *only* specifying the type free indirect (without medium or attributes). Frame, intExpr and speaker are not annotated.

The annotations were generated semi-automatically: The texts were  tagged by one of our automatic free indirect recognizers. The annotations and their immediate environment were then checked by humans, who, if necessary, deleted, corrected or extended the annotations. 

**NOTE:** As instances of free indirect that were not detected by the automatic recognizer were never presented to the humans, this data most likely contains **false negatives** (unlabled free indirect instances)!

## Statistics

This corpus consists of **142 files**, containing **2,647,924 tokens** with	**2,136 instances** of free indirect STWR.


A list of all texts including author, title and year of publicationcan be found [here](/data/additional/simplified/free_indirect/txt/metadata_fi.tsv).

# Primary annotations of the main corpus

folder: [/data/additional/primary](/data/additional/primary)

 Each sample of the [main corpus](/data/main) was annotated independently by two different people. Then, a third person created a consens annotation on this basis - these are the annotations you find in the main corpus. 
 
 In this collection, we share all single-person annotations for the main corpus samples that were produced over the course of our project. Most of them are the two annotations that served as the basis of the consens annotation, but some are additional annotations that were created to study annotator agreement. Each annotation was created independently.
  
 A total of 9 different annotators were involved in this project. The files in this collection are organized in sub-folders, each containing the work of one person. The names of the planets of our solar system (plus Pluto!) serve as pseudonyms. You can also find these same pseudonyms in the metadata of [single-annotated files](/data/additional/single_annotated) and the [free indirect sub-corpus](/data/additional/simplified/free_indirect).
 
 We provide a list ([tsv](/data/additional/primary/rwk1_list.tsv) and [xlsx](/data/additional/primary/rwk1_list.xlsx) format that lists the available single-person annotations for all main corpus samples. For 3 samples (rwk_digbib_1134-1, rwk_digbib_1299-1, rwk_digbib_935-1), we can only provide one primary annotation. 
 
 
 **Note**: As the CAB Tokenization is not available for the early primary annotations, we decided to use the OpenNLP Tokenizer for all files in this collection. This should ensure that the files (particularly in tsv and xmi format) can be aligned to calculate annotator agreement scores. CABTokens are still available in many of the XMI files. 
 In the folder [consens](/data/additional/primary/consens),  we also provide an alternative tsv version of the consens annotated main corpus, tokenized with the OpenNLP Tokenizer, that can be aligned with these files. The xmi files of the main corpus contain OpenNLP Tokens as well (Annotation "Token"). 
 
 
Click the following links to get familiar with the [annotation structure](annotation_structure.md), [metadata](metadata.md) and the different formats available ([column-based text format](column_based_text_format.md),  [xml-format](xml_format.md),  [xmi-format](xmi_format.md)).

 In the folder [resources_xmi](/data/additional/primary/resources_xmi) you find an extended typesystem for the XMI version of these files.

## Annotator agreement
The following table lists the annotator agreement scores for 834 samples of the main corpus (4 samples are missing in this calculation). If more than two primary annotation was available, two were chosen at random. 

| annotations   | Fleiss’ Kappa |               |
|---------------|---------------|---------------|
|               | type          | type & medium |
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

Instances of STWR-types per annotator

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

+12 ambiguous STWR-types


# Annotation structure

This is a short overview over the annotations used in the "Redewiedergabe" corpus, their structure and names.

**NOTE**: This page only explains the technical structure of the annotation. To really understand the meaning and proper usage of these categories, we strongly recommend consulting the [detailed annotation guidelines](http://redewiedergabe.de/richtlinien/richtlinien.html) on our project homepage (in German). 

Spelling and formatting of the attribute names differ slightly in the output formats [column-based text format](column_based_text_format.md) and [XML format](xml_format.md) (cf. documentation of these formats), but this page explains the general structure and caveats.

This visualization can give you a first impression.

A standard case:

![example1, Marie von Ebner-Eschenbach: Agave (1903)](/resources/docs/img/example_easy.png)

A case of embedded STWR:

![example2, Louise von François: Phosphorus Hollunder (1881)](/resources/docs/img/example_embedding.png)

## Note (Footnote text)
The samples of the "Redewiedergabe" corpus sometimes contain footnote text that interrupts the main text. Those are marked with the annotation **note**. This structural annotation was copied from the original full texts in order to ensure that the footnote text can be separated from the main text if necessary.

_Warning:_ Footnote text can interrupt sentences! Sentence splitting information (in the column-based format) is not correct in these cases.

## Annotation STWR (Speech, Thought, Writing Representation)
### Main attributes
These attributes are obligatory for each STWR annotation.

| Attribute | Values                                   | Possible combined values                                                | Description                                                                                                                                                                   |
|----------|------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| type     | direct, freeIndirect, indirect, reported | indirect_freeIndirect                                                   | STWR type                                                                                                                                                                     |
| medium   | speech, thought, writing                 | speech_thought, speech_writing, thought_writing, speech_thought_writing | STWR medium                                                                                                                                                                        |
| id       | _Number_                                 |                                                                         | ID; refers to the IDs of frame, speaker and intExpr and can also link discontinuous STWR annotations (e.g. a direct STWR that is separated by a frame).|
| level    | _Number_ (starts with 1)                 |                                                                         | nesting depth of this STWR annotation; value=1 means highest level                                                                                                            |

_Note:_ The combined values are separated by `_` in the column-based format, but by whitespace in the XML format.

### Secondary attributes
These attributes are optional.

| Attribute | Values                 | Description                                                                      |
|----------|------------------------|----------------------------------------------------------------------------------|
| non-fact | yes                    | non-factual STWR, e.g. negated                                                   |
| border   | state, percept, unspec | borderline cases of STWR (typically for thought representation), e.g. perceptions |
| prag     | yes                    | STWR with a different pragmatic function, e.g. rhetorical figures                  |
| metaph   | yes                    | metaphorical STWR                                                                |

## Annotations frame, speaker and intExpr

| Attribute | Values          | Description                                                                                                                    |
|-----------|-----------------|--------------------------------------------------------------------------------------------------------------------------------|
| id        | _Number_        | ID; links the annotations to each other as well as to one or more STWR annotations; may have the value 0 for frame/speaker/intExpr annotations without corresponding STWR annotations (this may occur at the end of a sample)                    |
| pos       | start, mid, end | only for frame: position of the frame relative to its STWR; start=before the STWR, mid=interrupts the STWR, end=after the STWR |

In rare cases, frame annotations can appear without a linked STWR, if they are positioned at the end of a sample. In these cases, the ID has value zero.

Speaker annotations can have more than one ID, if they are associated with several different STWR annotations. 

Frame annotations can only be linked to STWR annotations with the types *direct* or *indirect*. IntExpr annotations can additionally be linked to STWR annotations with the type *reported*. Speaker annotations can be linked to STWR annotations of any type.

IntExpr annotations only appear within frame annotations or within STWR annotations of the type reported.

Generally, each frame annotation is linked to one IntExpr and one Speaker annotation. However, there are exceptions to this rule:
* There can be several IntExpr annotations for one frame annotation. These are either coordinated elements ("er _bat_ und _bettelte_") or parts of a phrase or a complex verb that are separated ("er _rief_ laut _aus_").
* There can be several Speaker annotations for one frame annotation. These are coordinated elements (e.g. several different people).
* There may be frame annotations that have neither Speaker nor IntExpr (if those could not be identified).

## Additional structural remarks
* STWR annotations are often nested. The maximum nesting depth is level=5, which is very rare.
* In rare cases, Frame annotations can also be nested.

# Column based text format 

## General remarks

Folder: [data/main/txt](../../data/main/txt)

Corpus metadata is available in the file **metadata** ([tsv format](../../data/main/txt/metadata.tsv) or [Excel format](../../data/main/txt/metadata.xlsx))

The corpus consists of UTF-8 coded files with the file ending "tsv" (tab-separated values). Each file contains a sample in a column-based format. The columns are separated by tabstops and each line corresponds to one token of the sample (Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de)).

In addition to the annotations added by the project Redewiedergabe, the files also contain morpho-syntactic annotations produced by automatic tools that were not developed by the project Redewiedergabe.

For a more detailed explanation of the annotation structure see [Annotation structure](annotation_structure.md). 

### References:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)

## Columns

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

## Structure of the main STWR annotation
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

## Structure of the annotations frame, speaker and intexpr
These annotations each consist of a name (frame, speaker, intexpr), the character `.` (dot), and the corresponding ID.

Speaker can have multiple IDs, which are separated by the character `_` (low dash).

Example:

`speaker.12_19`

This token is annotated as speaker with two IDs: 12 and 19 (i.e. this speaker is associated with the STWR annotation with ID=12 as well as the STWR annotation with ID=19).


# XML

Folder: [data/xml](../../data/main/xml)

This version of the corpus consists of TEI compliant XML files. Each file contains the text of one sample and the annotations of the project Redewiedergabe.

For a more detailed explanation of the annotation structure see [Annotation structure](annotation_structure.md).

## Structure of a sample file
* TEI header with general information
* `<fs>` tag with metadata in the format defined by the Redewiedergabe project (see [Metadata](metadata.md))
* The sample text contains the following XML tags: `<said>` (STWR annotation), `<seg>` (frame/speaker/intExpr annotation), `<note>` (footnote text), `<p>` (paragraph; always covers the full sample text)

## Project-specific TEI extensions
We created a RELAX-NG syntax schema that adapts the TEI Module for Linguistic corpora to the annotation schema of the project Redewiedergabe. The following paragraph lists the extensions we defined.

Schema and Documentation: [data/xml/resources](../../data/main/xml/resources)

### Extensions of the TEI element `<said>`

| Attribute | Values                                                                                    | Description                                              |
|----------|------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| id       | _number_                                                                                     | ID                                                      |
| mode     | direct, freeIndirect, indirect, reported, indirect freeIndirect | STWR type                                                      |
| content  | speech, thought, writing (and combinations, separated by whitespace)                 | STWR medium                                                             |
| level    | _number_ (starts with 1)                                                                                     | nesting depth of this STWR annotation                          |
| nonFact  | yes/no                                                                                   | non-factual STWR, e.g. negated |
| prag     | yes/no                                                                                   | STWR with a different pragmatic function, e.g. rhetorical figures       |
| metaph   | yes/no                                                                                   | metaphorical STWR                                           |
| border   | unspec/state/percept                                                                     | borderline cases of STWR (typically for thought representation), e.g. perceptions                            |
| stwrnote | _raw text_                                                                               | text input field for additional comments                    |

### Extensions of the TEI element `<seg>`
| Attribute | Values | Description                                     |
|----------|-------------------------|-----------------------------------------------------------|
| id       | _number_                    | ID                                             |
| pos      | start, mid, end         | if type=frame: position of the frame relative to its STWR |

The attribute `type` of the `<seg>` tag is used to specify which information the tag is used for. Options are: frame, speaker, intExpr.

# XMI

## General remarks
Folder: [data/main/xmi](../../data/main/xmi)

Typesystem: [data/main/xmi/resources](../../data/main/xmi/resources)

This version of the corpus consists of XMI files. Each file contains the text of one sample. XMI was the working format of the project Redewiedergabe and the basis for the [XML](xml_format.md) and [text](column_based_text_format.md) formats. The files contain the following types of annotations:
* **STWR, Frame, IntExpr, Speaker, Metadata**: Annotations specific to the project Redewiedergabe. For a more detailed explanation of these annotations see [Annotation structure](annotation_structure.md) and [Metadata](metadata.md).
* **Text**: Structural marker. The relevant text of the sample is enclosed in this annotation.
* **CabToken, Sentence**: Additional morpho-syntactic annotation produced by automatic tools that were not developed by the project Redewiedergabe (CAB, RFTagger, references see below). 
* **TeiType**: Additional XML tags coded as XMI annotations. In the workflow of the project Redewiedergabe, samples were pulled from TEI complient XML files, then annotated with the CAB tool in XML mode and finally converted to XMI. The annotation **TeiType** preserves all XML annotations that were detected in the input documents. These annotations are diverse and have not been standardized in any way. They are provided as optional information for anyone who is interested in the relationship of the Redewiedergabe annotations to original TEI markers.

NOTE: Some XMI files contain textual metadata information at the beginning of the document. This information should be ignored by *only* processing the Annotation element **Text**. The correct metadata is stored in the annotation **Metadata**.  

The XMI files are compatible with the anntotation tool [ATHEN](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen) (developed by Markus Krug in the [Kallimachos project](http://kallimachos.de)) and its [STWR view](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/Athen/blob/master/de.uniwue.mk.athen/releng/de.uniwue.mk.athen.docu/STWRView.md) (developed by Tanja Tu) which have been used in the project Redewiedergabe. This tool is freely available for download.  

### References for the additional tools:  
* **CAB ("Cascaded Analysis Broker" for error-tolerant linguistic analysis)**: Jurish, B. Finite-state Canonicalization Techniques for Historical German. PhD thesis, Universität Potsdam, 2012 (defended 2011). `URN urn:nbn:de:kobv:517-opus-55789`. [Documentation](http://odo.dwds.de/~moocow/software/DTA-CAB)    
* **RF-Tagger**: Helmut Schmid and Florian Laws: Estimation of Conditional Probabilities with Decision Trees and an Application to Fine-Grained POS Tagging, COLING 2008, Manchester, Great Britain. [Documentation](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)

## Types

| Type| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| CabToken      | String                                                                      | token (tokenization by CAB) |
| Frame| String                                         | frame of the STWR            |
| IntExpression     | String                                                                       | word/s introducing the STWR            |
| Metadata       | String                                                   | metadata of the sample          |
| Sentence     | String                                          | sentence (sentence splitting by CAB)           |
| Speaker | String | speaker/source of the STWR         |
| Stwr       | String                                                      | main STWR annotation|
| TeiType     | String                                                                             | addition XML tags from the  the source material |
| Text | String | textual content of the sample |
## Features

### Features of the type **CabToken**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Id      | String                                                                      | token id |
| Xlit| String                                         | ortographically normalized token (provided by CAB)           |
| Canon     | String                                                                       | canonical form of token (provided by CAB)           |
| Pos       | String                                                   | morphological information (provided by CAB)        |
| Lemma     | String                                          | lemma (provided by CAB)         |
| RfPos | String | morphological information (provided by RF-Tagger)         |

### Features of the type **Frame**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Frame     | String                                                                      | surface |
| FrameID      | String                                                                      | frame id |
| Pos| start, mid, end                                         |  position of the frame relative to its STWR        |

### Features of the type **IntExpression**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| IntExpression      | String                                                                      | surface|
| IntExpressionID      | String                                                                      | intExpression id |

### Features of the type **Metadata**

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
| Dialect | yes, yes_DS (dialect in direct speech), no | information on dialect        |
| Perspective | first, first_plural, third, unsure | predominant perspective        |
| Quotes | german, chevron, chevorn_single, ascii, dash, none, other, undef | predominantly used quotation marks         |

### Features of the type **Sentence**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Id      | String                                                                      | sentence id |


### Features of the type **Speaker**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Speaker      | String                                                                      | surface|
| SpeakerID      | String                                                                      | speaker id |

### Features of the type **Stwr**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| Medium      | speech, thought, writing (and combinations, separated by whitespace)                                                                       | STWR medium   |
| RType| direct, freeIndirect, indirect, reported, indirect freeIndirect                                          | STWR type         |
| Level       | starts with 1                                                   | nesting depth of this STWR annotation      |
| NonFact     | nonFact, *empty String*                                         | non-factual STWR, e.g. negated     |
| Prag | prag, *empty String* |STWR with a different pragmatic function, e.g. rhetorical figures     |
| Border | unspec, state, percept, *empty String* | borderline cases of STWR (typically for thought representation), e.g. perceptions         |
| Metaph | metaph, *empty String*| metaphorical STWR       |
| Stwr | String | surface        |
| StwrID | String | stwr id        |

### Features of the type **TeiType**

| Feature| Value                                                                                        | Description                      |
|-----------|-----------------------------------------------------------------------------------------------------|---------------------------|
| TagName      | String                                                                       | tag name of the xml element  |
| Attributes| String                                         | attributes of the xml element  |

# Metadata
## Corpus files

The corpus consists of several samples. Each sample is a randomly drawn excerpt from a text.

The file names are structured as follows:

`rwk_source_textid_samplenumber`

or 

`rwk_source_textid_short`

Example: `rwk_digbib_123_2` means this is the second excerpt drawn from a text with the (project-internal) ID 123. The text comes from the source digbib (Digitale Bibliothek). The ending `short` can only appear for the newspaper sources (mkhz and grenz) and marks files that contain full articles (rather than excerpts) which are shorter than 500 tokens.

 
## Metadata table
| Metadatum | Values                                                                                                     | Description                                                                                                                                                      |
|-----------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| year      | _Number between 1840 and 1919_                                                                               | publication year of the text (for digBib texts: year of first publication, if available)                                                                            |
| decade    | _Number in steps of 10_                                                                                    | publication decade of the text                                                                                                                                     |
| source    | digbib, grenz, mkhz                                                                                       | source of the text; for mkhz the shorthand for the periodical is added after a dot.                                                                         |
| title     | _String_, Undefined                                                                                         | Title of the text, if available                                                                                                                                   |
| author    | _String_, Undefined                                                                                         | Author of the text, if available                                                                                                                                  |
| fictional | yes, no                                                                                                   | Is the text sample fictional?                                                                                                                                |
| text_type | Erzähltext, Kommentar, Anzeige, Reportage, Nachrichten, Biographie, Rezension, Reisebericht/Brief, unsure | Type of the text; if a sample contains several different texts (e.g. Kommentar and Anzeige), the dominant type is used for classification or the value is set to 'unsure' |
| filename    | _String_                                                     | Name of the source file this sample was pulled from. **Note**: We do not guarantee that these file names remain stable in the text sources.            |
| dialect     | yes, no, yes_DS (only in direct speech)                    | Information whether this sample contains a significant amount of non-standard German                                                              |
| perspective | first, first_plural ('we'), third                          | Predominant narrative perspective of the sample                                                                                                   |
| quotes      | dash, german,  chevron, chevron_single, none, other, undef | Quotation marks predominantly used in this sample; may contain more than one value if more than one type is used (e.g. "chevron chevron_single")) |

### Shorthands for the quotation marks

| Label          | Example  |
|----------------|----------|
| dash           | - Hello! |
| german         | „Hello!“ |
| none           | Hello!   |
| chevron        | »Hello!« |
| chevron_single | ›Hello!‹ |

### Shorthands for periodicals of source mkhz
Example: `mkhz.badener` means: This sample comes from Badener Zeitung.

The shorthands correspond to the shorthands used for the newspapers/magazines in the [DTA archive](http://www.deutschestextarchiv.de/doku/textquellen#mkhz).

| Periodical | Shorthand          |
|------------------------------------------------------------------------------------------------------------|--------------------|
| Badener Zeitung                                                                                            | badener            |
| Czernowitzer Allg. Zeitung                                                                                 | czernowitzer       |
| Mährisches Tagblatt                                                                                        | maehrisches        |
| Marburger Zeitung                                                                                          | marburger          |
| Reichspost                                                                                                 | reichspost         |
| St. Galler Volksblatt                                                                                      | stgaller           |
| Arbeitgeber. Archiv für die gesammte Volkswirtschaft, Central-Anzeiger für Stellen- und Arbeitgebergesuche | arbeitgeber        |
| Allgemeine Zeitung                                                                                         | augsburg           |
| Allgemeine Auswanderungs-Zeitung                                                                           | auswanderer        |
| Deutsche Auswanderer-Zeitung                                                                               | auswandererzeitung |
| Die Bayerische Presse                                                                                      | bayerische         |
| Bayreuther Zeitungen                                                                                       | bayreuther         |
| Berlinische Nachrichten von Staats- und gelehrten Sachen                                                   | berlin             |
| Berlinische Privilegierte Zeitung                                                                          | berlinpz           |
| Tübinger Chronik                                                                                           | chronik            |
| Conversations-Blatt zur Unterhaltung und Belehrung für alle Stände                                         | conversationsblatt |
| Europa. Wochenschrift für Kultur und Politik                                                               | europa             |
| Das Heller-Blatt oder Magazin zur Verbreitung gemeinnütziger Kenntnisse                                    | heller             |
| Märkische Blätter. Wochenblatt für belehrende und angenehme Unterhaltung                                   | maerkische         |
| Mainzer Journal                                                                                            | mainzerjournal     |
| Morgenblatt für gebildete Leser                                                                            | morgenblatt        |
| Das wohlfeilste Panorama des Universums zur erheiternden Belehrung für Jedermann und alle Länder           | panorama           |
| Das Pfennig-Magazin für Belehrung und Unterhaltung                                                         | pfennig            |
| Social-politische Blätter                                                                                  | social             |
| Sonntags-Blatt                                                                                             | sonntagsblatt      |
| Der allerneuesten Europäischen Welt- und Staats-Geschichte II. Theil                                       | weltgeschichte     |
| Wiener Zeitung                                                                                             | wiener             |


# Publications of project "Redewiedergabe"

Publications in chronological order; newest first

- Brunner/Engelberg/Jannids/Tu/Weimer: Corpus REDEWIEDERGABE, *LREC-Conference* Marseille, May 11th-16th 2020.

- Weimer: Stilometrische Untersuchung von Figurenreden in realistischen Erzähltexten, *DHd-Conference* Paderborn 2020, pp. 365-367. [Link](https://zenodo.org/record/3666690#.Xmdl8nsxlaQ)

- Brunner/Jannidis/Tu/Weimer: Redewiedergabe in Heftromanen und Hochliteratur, *DHd-Conference* Paderborn 2020, pp. 190-194. [Link](https://zenodo.org/record/3666690#.Xmdl8nsxlaQ)

- Tu/Engelberg/Weimer: *Was für Enthüllungen! heulte die wohlgekleidete respektable Menge.* - Eine korpus-linguistische Untersuchung zur lexikalitschen Vielfalt von Redeeinleitern, *Linguistische Berichte* Sonderheft 27/2019, S. 13-53.

- Brunner/Tu/Weimer/Jannidis: Deep learning for Free Indirect Representation, *KONVENS* Erlangen 2019, pp. 241-245. [Link](https://corpora.linguistik.uni-erlangen.de/data/konvens/proceedings/papers/KONVENS2019_paper_27.pdf)

- Weimer/Brunner/Engelberg/Jannidis/Tu: Das Redewiedergabe-Korpus - Eine Ressource für empirisch-linguistische Fragestellungen, *GAL-Sektionentagung* Halle (Saale) 2019.

- Tu: How sentimental are quotation expressions? A sentiment analysis, *2nd Heidelberg Summer School of Computational Humanitites* 2019.

- Weimer/Brunner/Tu: The "Redewiedergabe-Korpus", *2nd Heidelberg Summer School of Computational Humanitites* 2019.

- Tu/Krug/Brunner: Automatic recognition of direct speech without quotation marks. A rule-based approach, *DHd-Conference* Mainz/Frankfurt am Main 2019, pp. 87-89. [Link](https://zenodo.org/record/2596095#.XmdlAHsxlaQ)

- Brunner/Weimer/Tu/Engelberg/Jannidis: Das Redewiedergabe-Korpus, *DHd-Conference* Mainz/Frankfurt am Main 2019, pp. 103-106. [Link](https://zenodo.org/record/2596095#.XmdlAHsxlaQ)

- Brunner/Engelberg/Jannidis/Tu/Weimer: Annotieren, Rechnen, Analysieren - Redewiedergabe als Anwendungsfall der Digital Humanities, *GAL-Congress* Essen 2018.

- Brunner/Jannidis/Tu/Weimer: Redewiedergabe, *DARIAH-DE Grand Tour* Darmstadt 2018.

- Brunner/Weimer: Redewiedergabe - eine literatur- und sprachwissenschaftliche Korpusanalyse, *DGfS-Conference* Stuttgart 2018.

- Engelberg/Tu: Redeeinleiter, *DGfS-Conference* Stuttgart 2018.

- Brunner/Engelberg/Jannidis/Tu/Weimer: Projektvorstellung - Redewiedergabe. Eine literatur- und sprachwissenschaftliche Korpusanalyse, *DHd-Conference* Cologne 2018, pp. 19-21. [Link](http://dhd2018.uni-koeln.de/wp-content/uploads/boa-DHd2018-web-ISBN.pdf)

- Krug/Tu/Weimer/Reger/Konle/Jannidis/Puppe: Annotation and beyond - Using ATHEN, *DHd-Conference* Cologne 2018, pp. 458-460. [Link](http://dhd2018.uni-koeln.de/wp-content/uploads/boa-DHd2018-web-ISBN.pdf)

- Brunner: Automatische Erkennung von Redewiedergabe. Ein Beitrag zur quantitativen Narratologie, 2015.
