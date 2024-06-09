# A Bayesian Approach for Combining Stratified Election Polls

This repository contains the explanation and application of a Bayesian statistical method I developed to interpret the results of demographic-stratified election polls. I mainly wanted to make my report easily accessible in pdf form, but I also thought it would be useful to upload support for my text by including the entire script used to generate my analysis, along with the formatted data I used as input. 

### Contents

The full report is available as [Zalewski_Bayesian_Polling.pdf](./Zalewski_Bayesian_Polling.pdf), and contains the following sections:

1. Introduction
    - Stratified Election Polling
    - Bayesian Model Averaging
    - Challenges of US Election Polls
2. A Bayesian Model for Interpreting Polls
3. Data Collection
    - Polls
    - Voter Turnout Rate
    - Population
4. Model Fitting
5. Results
6. Discussion

If you'd like to see the exact code used to generate these results, including the STAN model, the file [zalewski_bma_polling.Rmd](./zalewski_bma_polling.Rmd) contains the entire script used for the analysis. Although the sections are clearly marked, annotations are sparse as they assume familiarity with what the purpose of the script as explained throughout the paper. The [data](./data) folder contains all the necessary files necessary to run the script, and these files should be placed in the directory of the markdown file when executed.
The estimated total votes for a candidate **k** in a state **s** can be estimated by the formula:





