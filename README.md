💬 Text Classification using SVM and TF-IDF
This project implements a complete pipeline for text classification using Support Vector Machine (SVM) and TF-IDF vectorization, from data crawling to evaluation.

📌 Project Structure
File	Description
Crawl Data.ipynb	Scrapes or loads raw textual data for training
Pelabelan Data dan Split Data.ipynb	Labels the dataset and splits it into training/testing sets
Preprocessing Data.ipynb	Cleans and preprocesses text (case folding, stopword removal, etc.)
TF-IDF.ipynb	Converts the preprocessed text into numerical vectors using TF-IDF
SVM.ipynb	Trains and evaluates a Support Vector Machine classifier

🧠 Methods Used
Natural Language Processing (NLP) techniques

TF-IDF for feature extraction

Support Vector Machine (SVM) for classification

Train-test splitting for evaluation

🛠️ Tech Stack
Python (Jupyter Notebook)

scikit-learn

pandas, numpy

BeautifulSoup / requests (if scraping is used)

📈 Result
This workflow helps classify text data (e.g., sentiment, topic, etc.) with measurable performance using SVM accuracy and evaluation metrics.
