<h1>Project 4 - Machine Learning Integration</h1>
<h2>Fake News Detector</h2>
<br>
<p><b>Group Name:</b> Knights of the round Tableu
  <br><b>Members:</b>
  <br>Dominika Rzezniczak
  <br>George Jeffries
  <br>James Fairgrieve
  <br>Ovidiu Serban</p>
<h3>Introduction</h3>
<p>The term fake news means “news, articles that are intentionally and verifiably false” designed to manipulate people’s perceptions of real facts, events, and statements. It’s about information presented as news that is known by its promoter to be false based on facts that are demonstrably incorrect, or statements or events that verifiably did not happen. 
Fake News is a real problem . False information can increase social tensions, influence political elections , damage the reputation of a public figure, or even fuel conflicts between two countries.</p>
<h3>Resources</h3>
<p>Dataset obtained from Kaggle.com, two csv files - Fake.csv and True.csv containing 22,819 and 21,416 news articles respectively.</p>
<img src="https://github.com/DominikaRzez/project4_knights-of-the-round-tableau/blob/main/images/fake-news.png?raw=true" width="400" height="300">
<img src="https://github.com/DominikaRzez/project4_knights-of-the-round-tableau/blob/main/images/true-news.png?raw=true" width="400" height="300">
<h3>Data Preprocessing and Cleaning</h3>

<h3>Models</h3>
<h4>Naive Bayes</h4>
As the first model we trained the Naive Bayes model using Google Colab and PySpark. The model was choosen as its fast, accurate and reliable and works particularly well with Natural Language Processing. The model calculates the probability of each tag for a given text, but without considering features distribution.
<br>The model was initially trained and run on the dataset cleaned with the TextHero library, but didn't achieve the desired accuracy. The results for training and testing data were 67% and 66% respectively.</p>
<img src="https://github.com/DominikaRzez/project4_knights-of-the-round-tableau/blob/main/images/NB_TextHero_Classification.png?raw=true">
<p>To improve the accuracy the model has been trained and run again on the dataset cleaned and preprocessed using NLTK library. This time the model resulted the accuracy above 90% for both training and testing data.</p>
<img src="https://github.com/DominikaRzez/project4_knights-of-the-round-tableau/blob/main/images/NB_NLTK_Classification.png?raw=true">

<h3>Models Optimisation and Evaluation</h3>
<h3>Tableu Report</h3>
<p>Scan the QR code below to see our report in Tableu</p>
<img src="https://github.com/DominikaRzez/project4_knights-of-the-round-tableau/blob/main/images/tableau-QR.png?raw=true">
