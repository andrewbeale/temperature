# Diurnality
A repository for data from Beale et al, **A cellular basis for the mammalian nocturnal-diurnal switch**, _BioRxiv_ 2025 (https://www.biorxiv.org/content/10.1101/2023.06.22.546020v2)

Custom analysis of temperature shift proteomics and phosphoproteomics experiments in primary biologically replicate human and mouse fibroblasts. This code accompanies the revised manuscript published on bioRxiv, which provides experimental design. Much of the code in this repository was adapted from David Wong /github.com/davwong47/Circadian-proteomics to this particular set of experiments. It is made public for transparency.

### Directory structure

This revision directory contains files pertaining to the revised manuscript (v2 bioRxiv):

- **R notebooks** - these are numbered in the order in which they are to be run, and each begins with a short description and a summary of input/output files.

- **/1 Raw files from Perseus** -> proteomics + phosphoproteomics .txt files.

- **/Processed data** -> Notebooks prefixed with 1 are output csv from R notebooks "1 Cleaning and normalising data...". Notebooks prefixed with 2 have additional columns for the statistical tests, which were run separately in Prism.
