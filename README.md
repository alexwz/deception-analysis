# Deception Analysis
Resources for the paper: "Truth or lie: exploring the language of deception"

This repo contains the following files:
1. analysis_results_all.xlsx - main data file with the results of the study.
  The columns are as follows:
  - p1_k2: truth 1, lie 2
  - pis1_tran2 describes whether the row is from written (1) or transcribed (2) part of the data set
  - iav, dav, sv, lcm_adj and lcm all are all Linguistic Category Model variables for language abstraction
  - spos and sneg reports positive and negative sentiment
  - c_mhd2 and c_mdd2 contain averaged MHD and MDD
  - c_gun_fog_cnt is the Fog Index value
  - placeName, persName, geogName, orgName variables are named entities
  - columns starting from prep up to tokens contain frequencies of morphological/part-of-speech classes
  - tokens contains the number of tokens

2. deception-models.ipynb - jupyter notebook with source code for the machine learning experiment
