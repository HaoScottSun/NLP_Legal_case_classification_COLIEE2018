# NLP_Legal_case_classification_COLIEE2018

With the explosive growth of legal documents, automatic Legal Information Retrieval(LIR) is critical to help law professionals to conduct quality services. In this paper, we propose using association rules to retrieval relevant legal documents. Our method is tested on three COLIEE 2018 tasks, and achieve acceptable and stable performance on all the tasks.

Detail process and results are published as "Legal Information Retrieval by Association Rules".

Reference URL: https://sites.ualberta.ca/~miyoung2/COLIEE2018/

------------------------------------------------------------------------------------------------------

This project contains solution for task 1 and task 2 of COLIEE 2018.

Task 1:The Legal Case Retrieval Task
This legal case competition focuses on two aspects of legal information processing related to a database of predominantly Federal Court of Canada case laws, provided by Compass Law. 

The legal case retrieval task involves reading a new case Q, and extracting supporting cases S1, S2, ... Sn for the decision of Q from the entire case law corpus. Through the document, we will call the supporting cases for the decision of a new case 'noticed cases'. 

Task 2: The Legal Case Entailment task
This task involves the identification of a paragraph from existing cases that entails the decision of a new case.

Given a decision Q of a new case and a relevant case R, a specific paragraph that entails the decision Q needs to be identified. We confirmed that the answer paragraph can not be identified merely by information retrieval techniques using some examples. Because the case R is a relevant case to Q, many paragraphs in R can be relevant to Q regardless of entailment.

This task requires one to identify a paragraph which entails the decision of Q, so a specific entailment method is required which compares the meaning of each paragraph in R and Q in this task. 

Detailed content of task 1 and 2 can be found from the url above.

------------------------------------------------------------------------------------------------------

COLIEE Task 1.pptx - general results of the task 1
COLIEE Task 2.pptx - general results of the task 2

my_doc2vec_model - trained doc2vec model file for task 1

task1-doc2vec.ipynb - code for solving the task 1
task2.ipynb - code for solving the task 2

Training and testing data can be downloaded from the url above.

Copyright: @Hao Sun
