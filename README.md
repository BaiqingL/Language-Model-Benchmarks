# CS 505 Final Project
### Comparison of mono and multilingual language models in sentiment classification
### Team 5 (baiqing)

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

data - contains the data we used to train and test our models as described below:

- The training and validation data is the text files containing "train" and "dev" in their names respectively inside /data/2017_English_final/GOLD/Subtask_A/
	
- The translated test data is /data/2017_Arabic_train_final/GOLD/SemEval2017-task4-train.subtask-A.english.txt

- The test data is all the files containing "arabic" and "subtask-A" in /data/2017_Arabic_train_final/GOLD 

BERT, multiBERT, Roberta, XLM-Roberta, T5, and MT5 - are all directories which contain the code used to fine-tune and evaluate their respective models.

Note: MT5 contains a notebook called MT5-36_acc.ipynb which contains a version fine-tuned with a lower learning rate as reported, but the model we used for comparison is MT5.ipynb
