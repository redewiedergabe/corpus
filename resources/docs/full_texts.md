# Single-annotated full texts
This is a collection of fictional and non-fictional complete texts, annotated according to the guidelines of the project Redewiedergabe (with some caveats regarding full texts, see below). The annotation was performed by only one annotator with no additional quality control. 

In total, this collection consists of 29 files with 280,203 tokens.

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
| rwz_full_digbib_5004 | Malsberg, Otto Freiherr von der | **Der Gefangene** | 1822 |  |
| rwz_full_digbib_5007 | Ungern-Sternberg, Alexander von | **Die Doppelgängerin** | 1834 |  |
| rwz_full_digbib_2473 | Poe, Edgar Allan | Hinab in den Maelström | 1841 |  |
| rwz_full_digbib_1136 | Droste-Hülshoff, Annette von | **Die Judenbuche** | 1842 |  |
| rwz_full_digbib_1199 | Grillparzer, Franz | **Der arme Spielmann** | 1847 |  |
| rwz_full_digbib_3228 | Wildermuth, Ottilie | Aus dem Leben einer Hausfrau der neuen Zeit | 1847 |  |
| rwz_full_digbib_5002 | Gotthelf, Jeremias | **Das Erdbeerimareili** | 1850 |  |
| rwz_full_digbib_5006 | Stifter, Adalbert | **Bergmilch** | 1853 |  |
| rwz_full_digbib_5001 | François, Louise von | **Phosphorus Hollunder** | 1857 |  |
| rwz_full_digbib_5005 | Raabe, Wilhelm | **Die schwarze Galeere** | 1861 |  |
| rwz_full_digbib_2649 | Riehl, Wilhelm Heinrich von | Amphion | 1862 |  |
| rwz_full_digbib_5003 | Marlitt, E. | **Die zwölf Apostel** | 1865 |  |
| rwz_full_digbib_3153 | Storm, Theodor | **Eine Malerarbeit** | 1867 |  |
| rwz_full_digbib_5000 | Eckstein, Ernst | **Der Leuchtturm von Livorno** | 1871 |  |
| rwz_full_digbib_3152 | Storm, Theodor | Eine Halligfahrt | 1871 |  |
|  | Keller, Gottfried | Kleider machen Leute | 1874 |  |
| rwz_full_digbib_1208 | Heyking, Elisabeth von | Gewesen | 1905 |  |
| rwz_full_digbib_2632 | Reventlow, Franziska Gräfin zu | Das Logierhaus "Zur schwankenden Weltkugel" | 1917 |  |
| **total** | **18 files** |  |  | **218,940** (+) |



## Non-fictional full texts
Folder: [data/additional/single_annotated/full_nonfict](../../data/additional/single_annotated/full_nonfict)

This collection consists of complete magazine and newspaper articles. The sources were the journal ['Die Grenzboten'](http://www.deutschestextarchiv.de/doku/textquellen#grenzboten) and different periodicals from the [Mannheimer Korpus Historischer Zeitungen und Zeitschriften](http://www.deutschestextarchiv.de/doku/textquellen#mkhz). 

### Statistics

| filename | title | periodical | year | tokens |
|----------|-------|------------|------|--------|
| rwz_full_mkhz_599 | - | Allgemeine Auswanderungs-Zeitung | 1847 | 4,514 |
| rwz_full_mkhz_336 | - | Allgemeine Auswanderungs-Zeitung | 1848 | 3,368 |
| rwz_full_mkhz_1098 | Die deutsche Kolonie Santa Cruz in der Provinz Rio Grande do Sul in Brasilien | Deutsche Auswanderer-Zeitung | 1852 | 3,175 |
| rwz_full_grenz_3721 | Regierung und Volk in Neapel | Die Grenzboten | 1856 | 7,041 |
| rwz_full_grenz_6595 | Die Petrussagen | Die Grenzboten | 1867 | 5,833 |
| rwz_full_mkhz_5884 | - | Social-Politische Blätter | 1873 | 5,118 |
| rwz_full_grenz_10479 | Die Tragik in Werken der hellenischen Plastik | Die Grenzboten | 1880 | 6,609 |
| rwz_full_mkhz_10107 | Die Versammlung der deutschen Vertrauensmänner in Brünn | Mährisches Tageblatt | 1887 | 6,418 |
| rwz_full_mkhz_10440 | Die 15. Hauptversammlung des Deutschen Schulvereins | Mährisches Tageblatt | 1895 | 6,257 |
| rwz_full_mkhz_2733 | Zur Beurteilung der jüngsten Schulkonflikte | Europa. Wochenschrift für Kultur und Politik | 1905 | 3,356 |
| rwz_full_grenz_20389 | Goethe und die Boisserée | Die Grenzboten | 1907 | 4,483 |
| rwz_full_grenz_23110 | Die Stellung Belgiens zum alten Reiche | Die Grenzboten | 1915 | 5,091 |
| **total** | **12 files** | - | - | **61,263** |


