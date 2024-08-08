Title: A Comparative Study of Open-Source and Closed-Source Large Language Models for Native Language Identification

Name: Yee Man Ng

Vrije Universiteit Amsterdam

13 August 2024

# Project description
This GitHub repository contains the code used for the experiments conducted in the Masters thesis project titled "A Comparative Study of Open-Source and Closed-Source Large Language Models for Native Language Identification", by Yee Man Ng, under supervision of dr. Ilia Markov at the Vrije Universiteit Amsterdam. It aims to investigate the use of open-source and closed-source large language models for Native Language Identification, the task of automatically identifying an author's native language based on texts written in their second language. 

## Structure
The folder 'code' contains all relevant code for our baselines (SVM & BERT), running open-source (LLaMA-2, LLaMA-3, Mistral, Phi-3 & Gemma) and closed-source LLMs (GPT-3.5 & GPT-4) out-of-the-box, as well as fine-tuning open-source LLMs using the Unsloth library. It is recommended to run the notebooks using Google Colaboratory with the A100 GPU, as most experiments for this study were ran with this GPU. 

The folder 'data' can be used to store the NLI datasets. The thesis made use of the TOEFL11, ICLE-NLI (a subset of the International Corpus of Learner English) and The Varieties of English for Specific Purposes dAtabase (VESPA) datasets. Both the TOEFL11 and ICLE-NLI are not publicly available. 

The VESPA dataset can be accessed for research purposes and downloaded via the following website: https://corpora.uclouvain.be/catalog/en/corpus/vespa. Please first run `data-preprocessing_VESPA.ipynb` to preprocess and split the data. 