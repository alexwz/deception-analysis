# Deception Analysis
Resources for the paper: "Truth or lie: exploring the language of deception"

This repo contains the following files:
1. **[analysis_results_all.xlsx](https://github.com/alexwz/deception-analysis/blob/main/analysis_results_all.xlsx)** - results of the study.
  Columns are as follows:
  - **p1_k2** truth (1) or lie (2)
  - **pis1_tran2** the row is from written (1) or transcribed (2) part of the data set
  - **iav, dav, sv, lcm_adj, lcm_all** are Linguistic Category Model variables for language abstraction
  - **spos, sneg** positive and negative sentiment
  - **c_mhd2, c_mdd2** contain averaged MHD and MDD
  - **c_gun_fog_cnt** is the Fog Index value
  - **placeName, persName, geogName, orgName** variables are named entity frequencies as identified by the Spacy tool
  - **tokens** is the number of tokens
  - **liczba_zdan** is the number of sentences
  - remaining columns (located between prep and tokens) contain frequencies of morphological and part-of-speech (grammatical) classes, see [here](https://www.sketchengine.eu/polish-nkjp-part-of-speech-tagset/) for more details

2. **[deception-models.ipynb](https://github.com/alexwz/deception-analysis/blob/main/deception_models.ipynb)** - jupyter notebook with source codes for the machine learning experiment.

3. **[dataset.tar.gz](https://github.com/alexwz/deception-analysis/blob/main/dataset.tar.gz)** - raw study data.
