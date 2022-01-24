# Main release statistics

The following statistics are for the main release of the corpus "Redewiedergabe". Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de) (see also [Column-based text format](column_based_text_format.md)).

# Samples and tokens

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
| 1910   | 49                  | 30,430             | 59                        | 30,898                   | 108             | 61,328        |
| total | 395                 | 244,691            | 443                       | 244,768                  | 838            | 489,459       |

# STWR instances
The following tables list the number of annotated STWR instances in the corpus. These instances vary greatly in length, between one token (possible for STWR types direct and reported) and several sentences (possible for STWR types direct, freeIndirect and indirect/freeIndirect.)

Note that there are also samples that do not contain any instances. These samples were not excluded as the corpus is supposed to be representative with regard to the frequency of STWR. 

## STWR types
| Type                    | Number of instances | Percent of all annotated STWR instances|
|------------------------|--------|---------|
| direct                 | 4166   | 33.2%   |
| indirect               | 2669   | 21.3%   |
| free indirect          |  136   | 1.1%    |
| reported               | 5431   | 43.3%   |
| indirect/free indirect |  131   | 1.0%    |
| total                 | 12,533  |         |

## STWR medium
| Medium  | Number of instances | Percent of all annotated STWR instances |
|---------|--------|---------|
| speech  | 8077   | 64.4%   |
| thought | 2917   | 23.3%   |
| writing | 1129   | 9.0%    |
| ambig   | 410    | 3.3%    |
| total  | 12,533   |         |

## Average length of instances, in relation to STWR type and fictionality

|                    | number of instances | average length of instances | number of instances | average length of instances |
|--------------------|---------------------|-----------------------------|---------------------|-----------------------------|
|                    | fictional           | fictional                   | non-fictional       | non-fictional               |
| direct             | 3527                | 22.2                        | 639                 | 39.5                        |
| indirect           | 1424                | 12.4                        | 1245                | 18.4                        |
| free indirect           | 132                 | 26.4                        | 4                   | 14.0                        |
| indirect/ free indirect | 65                  | 32.8                        | 66                  | 31.7                        |
| reported           | 2778                | 8.0                         | 2653                | 11.2                        |

The average length varies between STWR types and between fictional vs. non-fictional texts. While free indirect and indirect/free indirect are too infrequent to draw robust conclusions, it is interesting to note that for the three remaining types the instances in non-fictional texts are longer on average. 

# STWR token percentages

The graphics show the distribution of types and media in fictional vs. non-fictional samples, based on tokens.

## STWR types

![rw_Types](/resources/docs/img/rw_type.png)

Direct and free indirect STWR are clearly more common in fictional texts. Free indirect even occurs almost exclusively there, but is very infrequent in general, due to the historical nature of our corpus. Indirect and reported STWR on the other hand are more frequent in non-fictional texts, though the difference is not as pronounced.

## STWR medium

![rw_Media](/resources/docs/img/rw_medium.png)

The graphic only shows the most frequent ambiguous category "speech/writing" (ambiguous between speech and writing). The other ambiguous combinations are much less frequent.

Speech representation is dominant in fictional texts and writing in non-fictional ones. The latter is due to book reviews and to written communication often being a topic in news stories. The high percentage of speech/writing also indicates that the medium tends to be underspecified and probably considered less important than the represented content in non-fiction.  

# Text types (newspaper/magazine sources)

![text types](/resources/docs/img/text_type.png)

The graphic shows the distribution of the text types within the samples drawn from MKHZ and ‘Die Grenzboten’. Note the high number of narratives found in these sources. 13.2% of our fictional samples originate from newspapers and magazines where fiction was part of the feuilleton.
