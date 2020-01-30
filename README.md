# FUZZ-IEEE2020
Source codes, raw data and results for paper Predictability of Off-line to On-line Recommender Measures via Scaled Fuzzy Implicators submitted to FUZZ-IEEE 2020

The paper as well as this repository is partially based on the data from (https://arxiv.org/abs/1809.03186) presented at REVEAL 2018 vorkshop. For instructions on running the recommending algorithms and off-line evaluation, please refer to https://github.com/lpeska/REVEAL2018 repository. 

## Abstract
We introduce "fuzzy Challenge Response Framework" (fChRF) as a formal model for understanding of relationship between a model (usually computed) and real world observations. Both real and model situations consist of challenges/questions and responses/answers. We introduce a class of "scaled fuzzy Implicators" (sfI) to measure the quality of reduction of real world situations to model situations. 

In this paper, we test these formal concepts in a recommender systems  use-case. A recommender algorithm (trained off-line with a metric) aims to provide users with relevant objects. Observations consist of user behavior in such recommended on-line scenario. 

Using fChRF and fsI we measure which recommender and which off-line metric is the most promising help with respect to user behavior evaluated with several on-line measures. We present results on a real world small e-commerce enterprise A/B testing data. 

## Usage
- raw results for off-line evaluation are in resultsWithNovDiv_32_0dot01Temporal.rar
- raw results for on-line evaluation are in log.txt file
- result processing is done in ChRF_evaluation.ipynb python notebook. Note that raw result files have to be unpacked and it may be necessary to update references to load files in the notebook
