<h1 align="center">🍽️ Sentiment Analysis of Restaurant Reviews 🧠</h1>
<h3 align="center">NLP-Powered Review Classifier</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Sentiment%20Analysis-blue?style=for-the-badge" alt="Project Type" />
  <img src="https://img.shields.io/badge/Technology-NLP%20%7C%20Machine%20Learning-orange?style=for-the-badge" alt="Technology" />
  <img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge" alt="Status" />
</p>

---

<h2>📌 Overview</h2>

<p>
  This project analyzes restaurant reviews to determine whether they are positive or negative. Using Natural Language Processing (NLP) techniques, the reviews are cleaned, transformed into numerical features, and classified using a Random Forest model.
</p>

---

<h2>🔧 System Workflow</h2>

<p>The pipeline transforms raw text into a classified sentiment:</p>

<ol>
  <li><b>Text Preprocessing:</b> Cleans and standardizes raw reviews.</li>
  <li><b>Feature Engineering:</b> Converts text into a Bag-of-Words model using CountVectorizer.</li>
  <li><b>Model Training:</b> Splits data and trains a Random Forest classifier for sentiment prediction.</li>
</ol>

<p>🎯 <b>Goal:</b> Identify whether a restaurant review is positive or negative.</p>

---

<h2>🚀 Features</h2>

<ul>
  <li>✅ <b>Text Cleaning:</b> Removes punctuations, converts text to lowercase.</li>
  <li>✅ <b>Stemming:</b> Uses <b>PorterStemmer</b> to reduce words to their root forms (e.g., "liked" → "like").</li>
  <li>✅ <b>Stop Word Removal:</b> Filters out common words ("the", "and", etc.) to improve model accuracy.</li>
  <li>✅ <b>Bag-of-Words:</b> Uses CountVectorizer to create a numerical feature matrix.</li>
  <li>✅ <b>Classification:</b> Trains a Random Forest classifier to predict sentiment.</li>
</ul>

---

<h2>⚙️ Installation & Usage</h2>

<h3>📥 Install Dependencies</h3>
<pre><code>pip install pandas numpy sklearn nltk</code></pre>

<h3>🚀 Run the System</h3>
<pre><code>python sentiment_analysis.py</code></pre>

---

<h2>🧠 How It Works</h2>

<ol>
  <li>🔍 <b>Text Cleaning:</b> Punctuation is removed, text is lowercased and split into words.</li>
  <li>✂️ <b>Stemming:</b> Words like "loved" and "liked" are stemmed to their root form, e.g., "love."</li>
  <li>🛑 <b>Stop Words Removal:</b> Common words like "is", "and", "the" are removed to focus on meaningful content.</li>
  <li>🛠️ <b>Feature Engineering:</b> CountVectorizer converts cleaned text into a Bag-of-Words matrix.</li>
  <li>📊 <b>Data Split:</b> Splits the data into training and testing sets using <b>train_test_split()</b>.</li>
  <li>🌳 <b>Random Forest Classifier:</b> Trains on the training data and predicts sentiments on the test set.</li>
</ol>

---

<h2>🔍 Future Improvements</h2>

<p>Possible enhancements for more robust analysis:</p>

<ul>
  <li>💡 Implement TF-IDF instead of CountVectorizer for better feature representation.</li>
  <li>💡 Add sentiment scores (e.g., positivity percentage).</li>
  <li>💡 Use a more advanced classifier like Logistic Regression, SVM, or Neural Networks.</li>
  <li>💡 Deploy the model with a web app (e.g., Flask/Streamlit).</li>
</ul>

---

<h2>🔧 Technologies Used</h2>

<p>
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/NLTK-yellow?style=flat-square" alt="NLTK" />
  <img src="https://img.shields.io/badge/Scikit--Learn-red?style=flat-square" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Pandas-green?style=flat-square" alt="Pandas" />
  <img src="https://img.shields.io/badge/RandomForest-orange?style=flat-square" alt="Random Forest" />
</p>

---

<h2>📫 Contact</h2>

<p>
  Reach out for collaboration or improvements:
  <br>
  📧 Email: <b>gantisharan6639@gmail.com</b>  
  🔗 LinkedIn: <a href="https://linkedin.com/in/sharan-ganti" target="_blank">Sharan Ganti</a>
</p>

---

<p align="center">⭐ Analyzing reviews, one sentiment at a time! ⭐</p>
