# News Headline Category Classifier

Welcome to the **News Headline Category Classifier** — a sleek and powerful Streamlit web app that classifies news headlines into topics like **Politics**, **Business**, **Technology**, **Sports**, and **Entertainment** using Natural Language Processing (NLP).

---

## Features

- Classify any news headline into 5 categories
- Visualize prediction confidence scores
- Beautiful multi-page Streamlit UI with sidebar navigation
- Built with TF-IDF and Naive Bayes
- Real-time predictions
- Fully customizable frontend with gradient backgrounds and clean layout

---

## Live Demo

Try it now: [News_Headlines_Classifier](https://your-streamlit-app-link.streamlit.app)

---

## Categories

| Label        | Description                             |
|--------------|-----------------------------------------|
| `Politics`   | News related to governance, elections, policies, etc. |
| `Business`   | Headlines about economy, finance, markets |
| `Technology` | Tech trends, gadgets, companies |
| `Sports`     | Sports updates, players, games |
| `Entertainment` | Movies, music, celebrity news |

---

## Tech Stack

- **Python 3.9+**
- **Streamlit** for the UI
- **scikit-learn** for ML model
- **TF-IDF** for feature extraction
- **Multinomial Naive Bayes** for classification
- **joblib** for model persistence

---

## Model Details

- Preprocessing: Lowercasing, punctuation removal
- Vectorization: `TfidfVectorizer`
- Classifier: `MultinomialNB`
- Accuracy: ~90% on validation set

---

## Installation & Run

```bash
# Clone the repo
git clone https://github.com/your-username/news-headline-classifier.git
cd news-headline-classifier

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
