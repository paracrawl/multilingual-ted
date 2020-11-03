# TED Corpus
This is a self-crawled version of the TED Corpus.

## How it is build
The datas has been extracted from 113 TED Talks common to a certain amount of languages.
After that, al the text from the `.srt` files have been concatenated for each language pair and then aligned with hunaling.
This first version of the dataset has more or less the same text for all the languages, but the alignment or the common sentences could differ between one pair and another.
To avoid these differences another fully multilingual version was created, filtering all the sentences that are not common to at least 19 languages.

## Versions
Each directory contains a version of the corpus which its multilingual filter is performed for a different amount of languages.
