# Tamasheq-English-French
***
Cécile Macaire, Tomáš Pavliček, Alejandro Ciuba, Harshita Diddee, Marek Sarvaš, Santosh Kesiraju
Made available by Alejandro Ciuba, [alejandrociuba@gmail.com](alejandrociuba@gmail.com)/[pitt.edu](alc307@pitt.edu)
***
## NOTICE
**THIS DATA HAS BEEN COLLECTED FROM VARIOUS RESOURCES. THE USE OF THIS DATA IS ONLY FOR ACADEMIC NON-COMMERCIAL PURPOSES.**
***
## Summary
Small corpus containing a dataset between Tamasheq (TAQ), English (ENG), and French (FR). The data is organized amongst the following directories:
- `bible-data/`: **WARNING: DATA CONTAINS HEAVY BIAS!** Contains `bible-tamasheq.zip` and `bible-tamahaq.zip` (language similar to TAQ).
- `bilingual-dictionary/`: Contains files pertaining to our bilingual dictionary extracted from source text\*, as well as `bilingual-dictionary.zip`.
- `parallel-sentences/`: Contains files pertaining to our parallel sentences extracted from source text\*, as well as `parallel-sentences.zip`.
***
## Directory Layouts
- `bilingual-dictionary/`:
`taq-biling.txt`:
`tamasheq_sing., tamasheq_plural (opt.)`

`eng-biling.txt`:
`eng_sing., eng_plural (opt.) / secondary_translation (opt.)`

`focused_clean_2.txt`:
| English Word(s) | Tamasheq Sing. | Tamasheq Plural (opt.) |
| :--- | :---: | ---: |
| parent / ancestor | ămaraw | imarawăn |

**NOTE:** `english.txt` in the original `dict_extraction/` folder contains extra lines and only singular noun entries.

- `parallel-sentences/`:

`parallel-sents-dialects.txt`:
| Dialect (Ša and/or Za) | Tamasheq Sentence | English Translation (word\_1/word\_2) |
| :--- | :---: | ---: |
| Ša | ma dăr tǝnsed? | How did you sleep? |
| Ša | ma šănšed? | What are you buying/selling? |
| Ša Za | ma tǝkned? | What are you making/repairing? |

**NOTE:** Another copy `parallel-sents.txt` exists with the first column removed (no dialectal information).