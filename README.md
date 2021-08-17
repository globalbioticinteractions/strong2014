[![Review](https://github.com/globalbioticinteractions/strong2014/actions/workflows/review.yml/badge.svg)](https://github.com/globalbioticinteractions/strong2014/actions) [![Build Status](https://travis-ci.com/globalbioticinteractions/strong2014.svg)](https://travis-ci.com/globalbioticinteractions/strong2014) [![GloBI](https://api.globalbioticinteractions.org/interaction.svg?accordingTo=globi:globalbioticinteractions/strong2014&refutes=true&refutes=false)](https://globalbioticinteractions.org/?accordingTo=globi:globalbioticinteractions/strong2014)

Configuration to help Global Biotic Interactions (GloBI, https://globalbioticinteractions.org) index: 

Strong, Justin S., and Shawn J. Leroux. 2014. "Impact of Non-Native Terrestrial Mammals on the Structure of the Terrestrial Mammal Food Web of Newfoundland, Canada." PLOS ONE 9 (8): e106264. https://doi.org/10.1371/journal.pone.0106264


Steps to create indexed NL_FullDB.tsv:

1. download https://ndownloader.figshare.com/files/1475805 (see included copy NL_FullDB.xlsx) retrieve via `Strong, Justin; Leroux, Shawn (2014): Terrestrial Mammal Food Web of Newfoundland. figshare. Dataset. https://doi.org/10.6084/m9.figshare.855617.v5` 
2. open NL_FullDB.xlsx in LibreOffice Calc (or similar tool, spreadsheet program) 
3. transform NL_FullDB.xlsx to a UTF-8 encoded tab-delimited NL_FullDB.tsv
4. reformat date ranges to comply with ISO8601 (e.g., ```1968-1969``` -> ```1968/1969```)

Please cite the original data when using this dataset.
