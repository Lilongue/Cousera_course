
 <h1 align=center> My final Assignment </h1>

<h2 align=center> (Briefly about main phases of Data Science Methodology) </h2>  

---


> ## Analytic Approach

### The Decision Tree algorithm was taken. 

*It have to based not only on email fields like "from" or "title" but on some text patterns got with NLP*

---

> ## Data Requirements

#### Data should be prepared for a table-like structure. 
- But first we must to determine the main text patterns that may effect on the email importance. 
- Second - we have to offer a real-time algorithm of the email body processing for patterns searching.

---

> ## Data Collection

### Tens of sources of data each with message histories

##### The plan is:
1. Collect data from different sources
2. Split data to structured and unstructured parts
3. Use NLP methods to process the unstructured data to get some "patterns of importance"

---

> ## Data Understanding and Preparation

#### Data should be prepared for a table-like structure. 

##### So we have to:
1. Add text patterns in a structured form
2. Merge the tables from different sources

*It also good to walk through the data set to find the most relevant variables and find and exclude strongly correlated ones*

3. Data should be split on learning and evaluation sets. 

*The evaluation of real importance was based on managers feedback time-delay for answers in email stories*

---

> ## Modeling and Evaluation

#### The Decision Tree algorithm is taken

##### So we have a queue of emails based on predicted importance
1. One email is wins
2. it goes to queue and excluded from set
3. Repeat 1 and 2

##### Evaluate the model with evaluation set that was prepared on previous stage
##### Tune the model and go to modeling stage

## DO IT MANY MANY TIMES
---


```python

```
