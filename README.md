# Text classification for SemEval 2014 task 9

Complete problem description can be found here: http://alt.qcri.org/semeval2014/task9/ <br>
Complete data is dowloaded from the here: http://alt.qcri.org/semeval2017/task4/?id=download-the-full-training-data-for-semeval-2017-task-4

Description of each notebook:
1. prepare-data-csv.ipynb: Using raw data txt files create pandas dataframe
2. Data cleaning and EDA.ipyb: Cleaning raw text and some Exploratory data analysis on our data
3. Modelling.ipynb: CNN model for text classification task

<br>

Dataset details:

<table>
  <tr>
    <th></th>
    <th>Positive</th>
    <th>Negative</th>
    <th>Nuetral</th>
  </tr>
  <tr>
    <td>Total</td>
    <td>3640</td>
    <td>1458</td>
    <td>4586</td>		
  </tr>
</table> 

<br>
Model architecture for text classification task: <br>

<p align="center">
  <img src="https://github.com/NamanJain2050/semeval-2014-task-9/blob/master/model_01.png" alt="model_01"/>
</p>

<br>

We've used GloVe embeddings trained on twitter dataset downloaded from here: https://nlp.stanford.edu/projects/glove/