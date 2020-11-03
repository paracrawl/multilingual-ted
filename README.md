# Multilingual TED sets
These are self-crawled sets from [TED Talks](https://ted2srt.org/) automatically aligned and non-multilingual sentences filtered-out.

**WARNING**: recently discovered that QED corpus has TED Talks sentences until 2014. These sets contain more recent talks but also includes before 2014, so be cautious because there can be a lot of overlap.

## How it is build
The datas has been extracted from 113 talks common to a certain amount of languages.
After that, al the text from the `.srt` files have been concatenated for each language pair and then aligned with hunaling.
The resulting aligned data has more or less the same text for all the languages, some the sentences are shared by a few languages but not all.
To avoid these differences another fully multilingual version was created, filtering all the sentences that are not common all the languages of the set, or almost all.

## Versions
Each directory contains a version of the corpus which its multilingual filter is performed for a different amount of languages.
