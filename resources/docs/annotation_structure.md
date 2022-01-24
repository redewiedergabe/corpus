# Annotation structure

This is a short overview over the annotations used in the "Redewiedergabe" corpus, their structure and names.

**NOTE**: This page only explains the technical structure of the annotation. To really understand the meaning and proper usage of these categories, we strongly recommend consulting the detailed annotation guidelines (in German) at [redewiedergabe.de/richtlinien/richtlinien.html](http://redewiedergabe.de/richtlinien/richtlinien.html). [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2634994.svg)](https://doi.org/10.5281/zenodo.2634994).

Spelling and formatting of the attribute names differ slightly in the output formats [column-based text format](column_based_text_format.md) and [XML format](xml_format.md) (cf. documentation of these formats), but this page explains the general structure and caveats.

The following visualizations can give you a first impression.

A standard case:

![example1, Marie von Ebner-Eschenbach: Agave (1903)](/resources/docs/img/example_easy.png)

A case of embedded STWR:

![example2, Louise von François: Phosphorus Hollunder (1881)](/resources/docs/img/example_embedding.png)

# Note (Footnote text)
The samples of the "Redewiedergabe" corpus sometimes contain footnote text that interrupts the main text. Those are marked with the annotation **note**. This structural annotation was copied from the original texts in order to ensure that the footnote text can be separated from the main text if necessary.

NOTE: Footnote text can interrupt sentences! Sentence splitting information (in the column-based text format) is not correct in these cases.

# Annotation STWR (Speech, Thought, Writing Representation)
## Main attributes
These attributes are obligatory for each STWR annotation.

| Attribute | Values                                   | Possible combined values                                                | Description                                                                                                                                                                   |
|----------|------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| type     | direct, freeIndirect, indirect, reported | indirect_freeIndirect                                                   | STWR type                                                                                                                                                                     |
| medium   | speech, thought, writing                 | speech_thought, speech_writing, thought_writing, speech_thought_writing | STWR medium                                                                                                                                                                        |
| id       | _Number_                                 |                                                                         | ID; refers to the IDs of frame, speaker and intExpr and can also link discontinuous STWR annotations (e.g. a direct STWR that is separated by a frame).|
| level    | _Number_ (starts with 1)                 |                                                                         | nesting depth of this STWR annotation; value=1 means highest level                                                                                                            |

_Note:_ The combined values are separated by `_` in the column-based format, but by whitespace in the XML format.

## Secondary attributes
These attributes are optional.

| Attribute | Values                 | Description                                                                      |
|----------|------------------------|----------------------------------------------------------------------------------|
| non-fact | yes                    | non-factual STWR, e.g. negated                                                   |
| border   | state, percept, unspec | borderline cases of STWR (typically for thought representation), e.g. perceptions |
| prag     | yes                    | STWR with a different pragmatic function, e.g. rhetorical figures                  |
| metaph   | yes                    | metaphorical STWR                                                                |

# Annotations frame, speaker and intExpr

| Attribute | Values          | Description                                                                                                                    |
|-----------|-----------------|--------------------------------------------------------------------------------------------------------------------------------|
| id        | _Number_        | ID; links the annotations to each other as well as to one or more STWR annotations; may have the value 0 for Frame/Speaker/IntExpr annotations without corresponding STWR annotations (this may occur at the end of a sample)                    |
| pos       | start, mid, end | only for frame: position of the frame relative to its STWR; start=before the STWR, mid=interrupts the STWR, end=after the STWR |

In rare cases, Frame annotations can appear without a linked STWR, if they are positioned at the end of a sample. In these cases, the ID has value zero.

Speaker annotations can have more than one ID, if they are associated with several different STWR annotations. 

Frame annotations can only be linked to STWR annotations with the types *direct* or *indirect*. IntExpr annotations can be linked to STWR annotations with the type *direct*, *indirect* or *reported*. Speaker annotations can be linked to STWR annotations of any type.

IntExpr annotations only appear within Frame annotations or within STWR annotations of the type *reported*.

Generally, each Frame annotation is linked to one IntExpr and one Speaker annotation. However, there are exceptions to this rule:
* There can be several IntExpr annotations for one Frame annotation. These are either coordinated elements ("er _bat_ und _bettelte_") or parts of a phrase or a complex verb that is separated ("er _rief_ laut _aus_").
* There can be several Speaker annotations for one Frame annotation. These are coordinated elements (e.g. several different people).
* There may be Frame annotations that have neither Speaker nor IntExpr (if those could not be identified).

# Additional structural remarks
* STWR annotations are often nested. The maximum nesting depth is level=5, which is very rare.
* In rare cases, Frame annotations can also be nested.
