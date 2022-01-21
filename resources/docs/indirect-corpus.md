# Indirect corpus

This subcorpus was created to generate training data for our recognizers specifically for **indirect STWR**. The annotation system is strongly reduced, *only* specifying the type indirect (without medium or attributes).  Frame, intExpr and speaker are not annotated.

To create this corpus, the texts were  tagged by one of our automatic indirect recognizers. The annotation was then corrected by humans who checked the whole texts, so false negatives were corrected as well. Annotation quality should therefore be comparable to the [single-annotated files](/data/additional/single_annotated).

The indirect corpus is only available in [column-based text format](column_based_text_format.md) in a reduced form (only tokens and category).

## Statistics

This corpus consists of **16 files**, containing **51,864 tokens** with	**272 instances** of indirect STWR.

A list of all texts including author, title, year of publication and information on fictionality be found [here](/data/additional/simplified/indirect/txt/metadata_indirect.tsv).
