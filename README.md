# CS 505 Final Project
# Comparison of mono and multilingual language models in sentiment classification
# Team 5 (baiqing)

## Names
Baiqing Lyu - baiqing@bu.edu
Bowen Li - bown@bu.edu
Ciaran Hikaru Ueda Fitzgerald - cueda@bu.edu
Richard Chen - richchen@bu.edu
Shen Yan - sy5nb@bu.edu
Tengzi Zhao - tengzi@bu.edu

# Project decription
We fine-tuned BERT, multiBERT, Roberta, XLM-Roberta, T5, and MT5 models for the task of sentiment classification on tweets. 
We fine-tuned these models on English tweets, and tested the monolingual models on Arabic tweets translated to English and the multilingual models on Arabic tweets direction (zero-shot classification).
A further description, results, and discussion of this project can be found in our report.

# Files & Directories
Report.pdf - contains our report on the project
data - contains the data we used to train and test our models (it contains a separate README)
BERT - contains the code used to fine-tune BERT
multiBERT - contains the code used to fine-tune multiBERT
Roberta - contains the code used to fine-tune Roberta
XLM-Roberta - contains the code used to fine-tune XLM-Roberta
T5 - contains the code used to fine-tune T5
MT5 - contains the code used to fine-tune MT5 (MT5.ipynb) and a similar approach to compare with (mt5_soft_prompt_tuning.ipynb)
