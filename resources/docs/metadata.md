# Corpus files

The corpus consists of several samples. Each sample is a randomly drawn excerpt from a text.

The file names are structured as follows:
`rwk_source_textid_samplenumber`

Example: `rwk_digbib_123_2` means: This is the second excerpt drawn from a text with the (project-internal) ID 123. The text comes from the source digbib (Digitale Bibliothek). 
 
# Metadata table
| Metadatum | Values                                                                                                     | Description                                                                                                                                                      |
|-----------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| year      | _Number between 1840 and 1919_                                                                               | publication year of the text (for digBib texts: year of first publication, if available)                                                                            |
| decade    | _Number in steps of 10_                                                                                    | publication decade of the text                                                                                                                                     |
| source    | digbib, grenz, mkhz                                                                                       | source of the text; for mkhz the shorthand for the periodical is added after a dot.                                                                         |
| title     | _String_, Undefined                                                                                         | Title of the text, if available                                                                                                                                   |
| author    | _String_, Undefined                                                                                         | Author of the text, if available                                                                                                                                  |
| fictional | yes, no                                                                                                   | Is the text sample fictional?                                                                                                                                |
| text_type | Erzähltext, Kommentar, Anzeige, Reportage, Nachrichten, Biographie, Rezension, Reisebericht/Brief, unsure | Type of the text; if a sample contains several different texts (e.g. Kommentar and Anzeige), the dominant type is used for classification or the value is set to 'unsure' |

## Shorthands for periodicals of source mkhz
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
