# Socialness in Lexical Semantic Processing

**Data** and **scripts** associated with the manuscript Socialness Effects in Lexical-Semantic Processing by Diveica, Muraki, Binney & Pexman. Pre-print available at: https://psyarxiv.com/ek5a3/ . 

**A description of all files is provided below:**

1. Study1 – all data & files associated with Study 1: Socialness as a Predictor of Word Processing across Tasks
  - Regression_analyses.Rmd: this R script runs regression models and generates all the analysis tables and figures reported in the associated manuscript;
  - Regression_analyses.html: R Markdown document generated using the associated script. This file contains the results of all regression analyses. 
  - Data:
    - Properties_data:
      - Brysbaert2013_Concreteness.csv: Brysbaert M, Warriner AB, Kuperman V. 2014 Concreteness ratings for 40 thousand generally known English word lemmas. Behav. Res. Methods 46, 904–911. (doi:10.3758/s13428-013-0403-5)
      - ELP_Items.csv: Balota DA et al. 2007 The english lexicon project. Behav. Res. Methods 39, 445–459. (doi:10.3758/BF03193014)
      - Kuperman_2012_AoA.csv: Mandera P, Keuleers E, Brysbaert M. 2020 Recognition times for 62 thousand English words: Data from the English Crowdsourcing Project. Behav. Res. Methods 52, 741–760. (doi:10.3758/s13428-019-01272-8)
      - SocialnessNorms_DiveicaPexmanBinney2021.csv: Diveica V, Pexman PM, Binney RJ. 2023 Quantifying social semantics: an inclusive definition of socialness and ratings for 8388 English words. Behav. Res. Methods 55, 461-473. (doi:10.3758/s13428-022-01810-x)
      - Warriner 2013 Emotion ratings.csv : Warriner AB, Kuperman V, Brysbaert M. 2013 Norms of valence, arousal, and dominance for 13,915 English lemmas. Behav. Res. Methods 45, 1191–1207. (doi:10.3758/s13428-012-0314-x)
    - Task_data:
      - Cortese_2010.csv: Cortese MJ, Khanna MM, Hacker S. 2010 Recognition memory for 2,578 monosyllabic words. Memory 18, 595–609. (doi:10.1080/09658211.2010.493892)
      - ELP_Items.csv: Balota DA et al. 2007 The english lexicon project. Behav. Res. Methods 39, 445–459. (doi:10.3758/BF03193014)
      - Pexman_2017.csv: Pexman PM, Heard A, Lloyd E, Yap MJ. 2017 The Calgary semantic decision project: concrete/abstract decision data for 10,000 English words. Behav Res 49, 407–417. (doi:10.3758/s13428-016-0720-6)
      - aelp.csv: Goh WD, Yap MJ, Chee QW. 2020 The Auditory English Lexicon Project: A multi-talker, multi-region psycholinguistic database of 10,170 spoken words and nonwords. Behav Res (doi:10.3758/s13428-020-01352-0)
      - recogmemcorteseetal2015.csv: Cortese MJ, McCarty DP, Schock J. 2015 A mega recognition memory study of 2897 disyllabic words. Quarterly Journal of Experimental Psychology 68, 1489–1501. (doi:10.1080/17470218.2014.945096)
    - Regressions_dataset.csv: the full dataset that was used in the regression analyses. This file is generated in the associated scripts based on the property and task files listed above. 
  - Figures – figures generated using the associated script Regression_analyses.Rmd. 

2. Study2 – all data & files associated with Study 2: The Effect of Word Socialness on Verb Judgements
  - 1_Data_cleaning .rmd/.html: the script (1) applies a set of exclusion criteria to the raw data and generates a clean dataset of behavioural responses for inclusion in the analyses for Study 2; (2) summarizes participant demographic information. 
  - 2_Analysis .rmd/.html: the script runs the linear mixed effect models and Bayesian analyses on logRTs and Error Rates reported in the manuscript Study 2 section. It additionally includes an analysis conducted on the raw RTs.
  - Data:
    - Raw: all raw data from the Verb Judgement Task collected via Pavlovia
    - Preprocessed: 
      - Data_clean.csv: all clean data (i.e., trial-level behavioural responses remaining after exclusion criteria were applied and the associated trial information)
      - Item_Exclusions.csv: list of words that were excluded from the Study 2 analyses
      - Participant_Accuracy_Exclusions.csv: list of participants that were excluded from the Study 2 analyses
    - Demographics.csv – participants’ consent and demographic information collected via Qualtrics
  - Figures – figures generated using the associated script 2_Analysis .rmd. 
  - Output - .Rdata files containing the output of the time-intensive Bayesian ROPE analyses

3. Study3 - all data & files associated with Study 3: The Effect of Word Socialness on Noun Judgements
  - 1_Data_cleaning .rmd/.html: the script (1) applies a set of exclusion criteria to the raw data and generates a clean dataset of behavioural responses for inclusion in the analyses for Study 3 (2) summarizes participant demographic information. 
  - 2_Analysis .rmd/.html: the script runs the linear mixed effect models and Bayesian analyses on logRTs and Error Rates reported in the manuscript Study 3 section. It additionally includes an analysis conducted on the raw RTs.
  - Data:
    - Demographics.csv – participants’ consent and demographic information collected via Qualtrics
    - Raw: all raw data from the Noun Judgement Task collected via Pavlovia
    - Preprocessed: 
      - Data_clean.csv: all clean data (i.e., trial-level behavioural responses remaining after exclusion criteria were applied and the associated trial information)
      - Item_Exclusions.csv: list of words that were excluded from the Study 3 analyses
      - Participant_Accuracy_Exclusions.csv: list of participants that were excluded from the Study 3 analyses
    - Other – openly-available datasets used to conduct the analysis investigating differences in socialness scores between verbs and nouns:
      - SUBTLEX-US frequency list with PoS and Zipf information.csv : Brysbaert M, New B, Keuleers E. 2012 Adding part-of-speech information to the SUBTLEX-US word frequencies. Behav. Res. Methods 2012 444 44, 991–997. (doi:10.3758/S13428-012-0190-4)
      - Word_properties.csv contains word socialness and concreteness ratings from:
  - Diveica V, Pexman PM, Binney RJ. 2023 Quantifying social semantics: an inclusive definition of socialness and ratings for 8388 English words. Behav. Res. Methods 55, 461-473. (doi:10.3758/s13428-022-01810-x)
  - Brysbaert2013_Concreteness.csv: Brysbaert M, Warriner AB, Kuperman V. 2014 Concreteness ratings for 40 thousand generally known English word lemmas. Behav. Res. Methods 46, 904–911. (doi:10.3758/s13428-013-0403-5)
  - Figures – figures generated using the associated script 2_Analysis .rmd. 
  - Output - .Rdata files containing the output of the time-intensive Bayesian ROPE analyses

![image](https://github.com/DiveicaV/Socialness-LexicalSemanticProcessing/assets/65042145/74fc2b92-548d-4470-95d0-11dd5a699f52)
