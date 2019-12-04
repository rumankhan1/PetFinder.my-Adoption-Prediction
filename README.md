<h1><center>PetFinder.my Adoption Prediction</center></h1>
<img src="https://i.imgur.com/sE9LQWT.jpg">
<h2> a. Business problem</h2>
<h3> i. Descripton </h3>
<p> Build the model that can predict how fatser the pet (Cat or Dog) would get adopted after posting about adoption on PetFinder.my  platfrom.</p>
<p><b>Background info:</b>Millions of stray animals suffer on the streets or are euthanized in shelters every day around the world. If homes can be found for them, many precious lives can be saved — and more happy families created.</p>
<p>Animal adoption rates are strongly correlated to the metadata associated with their online profiles, such as descriptive text, age and photo characteristics.</p>
<p>So can we build an algorithms to predict the adoptability of pets - specifically, how quickly is a pet adopted?</p>
<h3>ii. Resources</h3>
<li> Kaggle page of this competition - https://www.kaggle.com/c/petfinder-adoption-prediction/overview </li>
<h3> iii. Real world/Business Objectives and Constraints</h3>
<li>Objective is to - build a model that predicts how sooner the pet would get adopted.</li>
<li>Constraints are - Miss-classification should be as low as possible. Also, not very strict time constarint. Model can take few seconds for prediction.</li>
<h3> iv. Given data overview</h3>
<p>Given various data files</p>

<li>train.csv : This file have total 24 attributes and 16k data points. </li>
<li>color_labels.csv: this contains the color for given pet. There are total 7 colors.</li>
<li>state_labels.csv : Contains state for given pet. And total 15 states.</li>
<li>breed_labels.csv: Contains breed of given pet. Total 307 breeds.</li>
<h3>i. Performance metrics:</h3>
<li>We'll be looking at log-loss and AUC. As log-loss penalizes very badly even if there is small deviation in prediction from actual class.</li>
<li> Also, look at confusion matrix.</li>
<h1>WORKING ON IT. I'LL UPDATE THIS REPO SOON.</h1>
