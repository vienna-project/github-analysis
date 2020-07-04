### Introduction

Have you ever worked on data processing billions of records? Unless you're working as a data engineer, you won't have the experience of processing billions of records. [**The github activity dataset**](https://www.gharchive.org/), which contains records of developers' activities on **GitHub** sing 2012, contains billions of log records.

<img src="https://imgur.com/WzgzWuu.png" width="800">

To handle this, we will use [Google BigQuery](https://cloud.google.com/bigquery), powerful and effective data warehouse tool. Even without spending a lot of money, you can experience the experience of analyzing Github records over the years through **Google BigQuery**. 



### requirements

##### 1. install python packages

````shell
pip install --upgrade google-cloud-bigquery
pip install --upgrade pandas-gpq
pip install --upgrade six
pip install --upgrade pyarrow
````

##### 2. Get Bigquery Credentials

If you wanna run the scripts in the repository, Download the credential json file according to [the link](https://cloud.google.com/docs/authentication/getting-started) and save it in the `credentials/` folder



### Reading List

#### 1.  [Read Data From Google Bigquery in jupyter](https://github.com/craftsangjae/analysis-github-activity-using-Big-Query/blob/master/scripts/3%20ways%20to%20read%20data%20from%20google%20bigquery%20in%20jupyter.ipynb)

###### It is so easy to handle Google BigQuery in the Jupyter. Let's learn 3 ways to handle Google BigQuery in Jupyter.

#### 2. [Understand the Schema of github archive](https://github.com/craftsangjae/analysis-github-activity-using-Big-Query/blob/master/scripts/Understanding%20the%20schema%20of%20github%20archive.ipynb)

###### Before we start analyzing the data, let's see how the github archive is structured.

#### 3. Analze the the GitHub Action

###### Grasp the overall aspect of the github action log







----

##### CopyRight [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This repository is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
