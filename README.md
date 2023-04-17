<h1> Udacity Data Scientist Nanodegree Capstone Project </h1>
<h4> Project Overview :</h4>
This project contain three dataset from Starbucks and it is consist of offer and how customer react on offers.

<h4> Files and dataset :</h4>
1- profile.json<br>
Rewards program users<br>
2-portfolio.json<br>
Offers sent during 30-day test period<br>
3-transcript.json<br>
Event log<br>

<h4>Problem Statement :</h4>
The goal of this project is to predicate the purches offer and the posibletey of taking advantge with this offers by the customer. We can achive this goal by following the demographic data of the customer and other data avilable in the Dataset that provided by the company about purches offers.

<h4>Installations:</h4>
pandas<br>
numpy<br>
seaborn<br>
math<br>
json<br>
datetime<br>
matplotlib.pyplot<br>
sklearn<br>

<h4>strategy to solve the problem</h4>
<li>Exploring and Visualizing the Data.
<li>Pre-processing the data.
<li>Applying Quick Data Analysis on the cleaned pre-processed data
<li>Trying several Supervised Learning Models.
<li>Evaluating the models using the chosen metric (Accuracy) .

<h4>Dataset Description</h4>
<h6> portfolio / containing offer ids and metadata about each offer :</h6>
<li>id: Offer id
<li>offer_type: a type of offer BOGO, discount, informational
<li>difficulty: the minimum required to spend to complete an offer
<li>reward: the reward is given for completing an offer
<li>duration: time for the offer to be open, in days
<li>channels: list of ways to contact

<h6>profile: demographic data for each customer:</h6>
<li>age: age of the customer
<li>became_member_on: the date when the customer created an app account
<li>gender: gender of the customer
<li>id: customer-id
<li>income: customer’s income

<h6>transcript: records for transactions, offers received, offers viewed, and offers complete</h6>
<li>event: record description
<li>person: customer-id
<li>time: time in hours since the start of the test.
<li>value: either an offer id or transaction amount depending on the record

<h4>Data Modeling</h4>
I have used two diffrent model 'Decision Tree model' and 'Naive Bayes modle' and for evaluate these model i have used the accurce between testing and predict.

<h4>conclusion</h4>

<li>I have explored each dataset, visualize it to get an overall understanding on the data 
<li>Preprocessing Data was the task that took most of the time and effort
<li>The dataset is a bit tricky required me to use my wrangling/ engineering and preprocessing skills
<li>I have created two types of model to make sure of result and compare

<h4> Linkes </h4>
blog for this project on medium: <br>
https://medium.com/@basim.h.said/starbucks-offers-analysis-aa19eabd1bed
