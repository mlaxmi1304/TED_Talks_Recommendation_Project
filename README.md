🎯 TED Talks Recommendation System

This project is a content-based recommendation system designed to suggest TED Talks to users based on their input topics of interest. It leverages text similarity techniques using TED Talk titles and descriptions to generate personalized suggestions.

📁 Dataset

The dataset consists of TED Talk metadata including:

Titles

Descriptions

Speaker names

Date of posting

Note: The dataset was sourced for educational use and includes publicly available TED Talk information. You can access the dataset here.

⚙️ System Requirements
OS: Windows / macOS / Linux

Python: 3.x

IDE: Jupyter Notebook

🛠️ Libraries Used

pandas, numpy — Data manipulation

nltk, string — Text preprocessing

sklearn — TF-IDF vectorization and similarity analysis

matplotlib, wordcloud — Visualization

🧠 Approach

Data Preprocessing: Cleaned and combined title and description text, removed stopwords and punctuation.

Feature Engineering: Used TF-IDF Vectorization to numerically represent TED Talk descriptions.

Recommendation Algorithm:

Calculated Cosine Similarity and Pearson Correlation between user input and TED Talk descriptions.

Selected the top similar talks for recommendation.

💡 How It Works

User enters a topic of interest.

The system processes the input and compares it with TED Talk descriptions.

Top 5 recommended TED Talks are displayed based on similarity scores.

🧪 Evaluation

The system was evaluated qualitatively by examining the relevance of recommended talks to a variety of input topics. Quantitative metrics like cosine similarity and Pearson correlation were used to rank results.

🚀 Future Work

Deploying a web-based UI for easier user interaction

Integrating real-time trends for dynamic recommendations

Scaling to support talks from other sources beyond TED

📚 References

Scikit-learn Documentation

Matplotlib Documentation

TED Talk dataset:   https://drive.google.com/file/d/18EMyw80LKC50i_OJDs3oG28HDaD97Gc3/view

