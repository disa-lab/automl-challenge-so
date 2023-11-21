# AutoML practitioners Challenges
This repository contains code and dataset for for the research work "Challenges and Barriers of Using Low Code Software for Machine Learning"


## Low-code (i.e., AutoML) Development
A machine learning program is a program that can learn from experience, i.e., data. In the traditional approach, a human expert analyses data and explores the search space to find the best model. AutoML aims to democratize machine learning to domain experts by automating and abstracting machine learning-related complexities. It aims to solve the challenge of automating the Combined Algorithm Selection and Hyper-parameter tuning (CASH) problem. AutoML is a combination of automation and ML. It automates various tasks on the ML pipeline such as data prepossessing, model selection, hyper-parameter tuning, and model parameter optimization. They employ various types of techniques such as grid search, genetics, and Bayesian algorithms. Some AutoML services also help with data visualization, model interpretability, and deployment.

In this study, we download a large number of Stack Overflow posts that contain discussions about various low-code platforms. We apply topic modeling on the textual contents of the posts. We label the topics and categorize the topics into hierarchies. We analyze the popularity and difficulty of the topics. Our study offers several findings based on the four research questions as discussed below;

## Stack Overflow dataset
The data is collected from low-code development-related `14.3K` SO posts. The Stack Overflow June 2022 data dump is used. The dump can be downloaded from [archive.org](archive.org).

The final list of `41` AutoML cloud and non-cloud service related tags that we used to collect posts from StackOverflow is as follows:

```json
['amazon-machine-learning', 'automl', 'aws-chatbot', 'aws-lex', 'azure-machine-learning-studio', 'azure-machine-learning-workbench', 'azureml', 'azureml-python-sdk', 'azuremlsdk', 'driverless-ai', 'ensemble-learning', 'gbm', 'google-cloud-automl-nl', 'google-cloud-vertex-ai', 'google-natural-language', 'h2o.ai', 'h2o4gpu', 'mlops', 'sparkling-water', 'splunk-calculation', 'splunk-dashboard', 'splunk-query', 'splunk-sdk', 'amazon-sagemaker', 'tpot', 'auto-sklearn', 'rapidminer', 'pycaret', 'amazon-lex', 'auto-keras', 'bigml', 'dataiku', 'datarobot', 'google-cloud-automl', 'h2o', 'mljar', 'splunk', 'transmogrifai', 'ludwig', 'azure-machine-learning-service', 'pycaret']
```

The extracted questions and answers based on these final tags are in our dataset folder `All questions.csv` and `All answers.csv` files, respectively.

### Replication Materials to Answer to RQs in the paper:
- __'Codes'__ folder includes all the data and code we used to filter data, run topic modeling, generate graphs, charts, tables etc inside a Jupyter notebook.
- __'code/Utilites'__: This contains helper method used in this project.
- __generated files__: It contains the intermediary filed generated for RQ1, RQ2, and RQ3 results.
- __RQ1 supporting files__: TopicModeling.zip
- __RQ3 supporting files__: topic popularity.csv, topic difficulty.csv
- __environment.yml__: This contains the anaconda environment used in this project. Python version 3.8 or higher is required for this project.



