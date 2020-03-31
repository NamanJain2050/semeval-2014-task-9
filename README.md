# Text classification for SemEval 2014 task 9

Complete problem description can be found here: http://alt.qcri.org/semeval2014/task9/ <br>
Complete data is dowloaded from here: http://alt.qcri.org/semeval2017/task4/?id=download-the-full-training-data-for-semeval-2017-task-4

## Description of each notebook:
1. prepare-data-csv.ipynb: Using raw data txt files create pandas dataframe
2. Data cleaning and EDA.ipyb: Cleaning raw text and some Exploratory data analysis on our data
3. Modelling.ipynb: CNN model for text classification task

## Dataset details:

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
  <tr>
    <td>Train</td>
    <td>2919</td>
    <td>1166</td>
    <td>3662</td>		
  </tr>
  <tr>
    <td>Test</td>
    <td>721</td>
    <td>292</td>
    <td>924</td>		
  </tr>
</table> 

## Model architecture for text classification task: <br>

Model inspired from here: https://arxiv.org/abs/1610.08815 <br>

<p align="center">
  <img src="https://github.com/NamanJain2050/semeval-2014-task-9/blob/master/images/model_01.png" alt="model_01"/>
</p>

<br>

We've used GloVe embeddings trained on twitter dataset downloaded from here: https://nlp.stanford.edu/projects/glove/
<br>
<br>

## Model Results

Classification report: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/semeval-2014-task-9/blob/master/images/classification_report.png" alt="class_report"/>
</p>
<br>
Metric Plot: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/semeval-2014-task-9/blob/master/images/f1_score.png" alt="class_report"/>
</p>
<br>
Loss Plot: <br>
<p align="center">
  <img width="500" height="500" src="https://github.com/NamanJain2050/semeval-2014-task-9/blob/master/images/loss.png" alt="class_report"/>
</p>
<br>

## Conclusion

We've achieved an F1-score of 0.6205 on test dataset
