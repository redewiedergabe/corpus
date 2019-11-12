# XML

Folder: [data/xml](https://github.com/redewiedergabe/corpus/tree/master/data/xml)

This version of the corpus consists of TEI compliant XML files. Each file contains the text of one sample and the annotations of the project Redewiedergabe.

For a more detailed explanation of the annotation structure see [Annotation structure](https://github.com/redewiedergabe/corpus/wiki/Annotation-structure).

# Structure of a sample file
* TEI header with general information
* `<fs>` tag with metadata in the format defined by the Redewiedergabe project (see [Metadata](https://github.com/redewiedergabe/corpus/wiki/Metadata))
* The sample text contains the following XML tags: `<said>` (STWR annotation), `<seg>` (frame/speaker/intExpr annotation), `<note>` (footnote text), `<p>` (paragraph; always covers the full sample text)

# Project-specific TEI extensions
We created a RELAX-NG syntax schema that adapts the TEI Module for Linguistic corpora to the annotation schema of the project Redewiedergabe. The following paragraph lists the extensions we defined.

Schema and Documentation: [data/xml/resources](https://github.com/redewiedergabe/corpus/tree/master/data/xml/resources)

## Extensions of the TEI element `<said>`

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

### Extensions of the TEI element `<seg>`
| Attribute | Values | Description                                     |
|----------|-------------------------|-----------------------------------------------------------|
| id       | _number_                    | ID                                             |
| pos      | start, mid, end         | if type=frame: position of the frame relative to its STWR |

The attribute `type` of the `<seg>` tag is used to specify which information the tag is used for. Options are: frame, speaker, intExpr.
