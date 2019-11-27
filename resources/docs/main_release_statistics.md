# Main release statistics

The following statistics are for the main release of the "Redewiedergabe" corpus. Tokenization was performed with [CAB](https://kaskade.dwds.de/demo/cab/file) available via [Deutsches Textarchiv](http://www.deutschestextarchiv.de) (see also [Column-based text format](https://github.com/redewiedergabe/corpus/wiki/Column-based-text-format)).

# Samples and tokens

In total, the corpus contains 839 samples and 489,608 tokens.

| Decade | fictional (samples) | fictional (tokens) | non-fictional (samples) | non-fictional (tokens) | all samples | all tokens |
|--------|---------------------|--------------------|---------------------------|--------------------------|----------------|---------------|
| 1840   | 49                  | 30,728             | 55                        | 30,233                   | 104             | 60,961        |
| 1850   | 50                  | 30,258             | 57                        | 30,426                   | 107             | 60,684        |
| 1860   | 50                  | 31,058             | 54                        | 31,420                   | 104             | 62,478        |
| 1870   | 50                  | 30,436             | 53                        | 30,568                   | 103             | 61,004        |
| 1880   | 49                  | 30,251             | 55                        | 30,678                   | 104             | 60,929        |
| 1890   | 49                  | 30,963             | 55                        | 30,273                   | 104             | 61,236        |
| 1900   | 50                  | 30,567             | 54                        | 30,272                   | 104             | 60,839        |
| 1910   | 49                  | 30,430             | 60                        | 31,047                   | 109             | 61,477        |
| total | 396                 | 244,691            | 443                       | 244,917                  | 839            | 489,608       |

# STWR instances
The following tables list the number of annotated STWR instances in the corpus. These instances vary greatly in length, between one token (possible for STWR types direct and reported) and several sentences (possible for STWR types direct, freeIndirect and indirect/freeIndirect.)

The graphics show the distribution of types and media in fictional vs. non-fictional samples, based on tokens.

## STWR types
| Type                    | Number | Percent|
|------------------------|--------|---------|
| direct                 | 4166   | 33.2%   |
| indirect               | 2669   | 21.3%   |
| free indirect          |  136   | 1.1%    |
| reported               | 5431   | 43.3%   |
| indirect/free indirect |  131   | 1.0%    |
| total                 | 12,533  |         |

<img src="resources/docs/rw_type.png" width="40" height="40"/>

## STWR medium
| Medium  | Number | Percent |
|---------|--------|---------|
| speech  | 8077   | 64.4%   |
| thought | 2917   | 23.3%   |
| writing | 1129   | 9.0%    |
| ambig   | 410    | 3.3%    |
| total  | 12,533   |         |

<img src="resources/docs/rw_medium.png" width="40" height="40"/>
