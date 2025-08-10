✈️ Airline Tweet Sentiment Analysis
Author: Prathik
Date: 10 August 2025
Project Type: NLP / Sentiment Analysis

📌 Project Overview
This project performs sentiment analysis on airline-related tweets to classify them as Positive (😄), Neutral (😐), or Negative (😡). It leverages Natural Language Processing (NLP) techniques, specifically TF-IDF Vectorization and a Logistic Regression classifier.

The model is designed to:

Preprocess text data (cleaning, tokenization, stopword removal).
Classify the sentiment of airline-related tweets.
Display confidence scores for predictions using a bar plot.
Provide emoji-enhanced sentiment predictions for better visualization.
📂 Features
Data Preprocessing

Tokenization using nltk.
Removal of common English stopwords.
Lowercasing and cleaning of non-alphabetic tokens.
Model Building

Standard train-test split for model evaluation.
TF-IDF Vectorization with ngram_range=(1, 2) to convert text into numerical features.
Logistic Regression as the classification algorithm.
Interactive Predictions

A Gradio interface for real-time, interactive sentiment predictions.
Emoji output for intuitive sentiment representation.
Confidence score bar charts to show the model's certainty for each sentiment class.
Evaluation

Reports model accuracy on both training and test datasets.
Includes example predictions on real-world tweets to demonstrate practical application.
📊 Example Predictions
| Tweet | Sentiment | | :--------------------------------------------- | :---------- | | "The crew was super friendly and the seats were comfy" | 😄 Positive | | "We were stuck on the runway for two hours" | 😡 Negative | | "It was fine, nothing special" | 😐 Neutral | | "Check-in was smooth and the plane was spotless" | 😄 Positive | | "The food was terrible and they lost my luggage" | 😡 Negative | | "WiFi worked okay, but not super fast" | 😐 Neutral |

🛠 How to Run
To run this project, you can use Google Colab or a local Python 3.8+ environment.

Open the Notebook:

If using Google Colab, upload the natural_language_processing_for_sentiment_analysis.py notebook directly.
If running locally, ensure you have Python 3.8 or newer installed.
Install Dependencies: Open your terminal or Colab notebook cell and run the following command to install all necessary libraries:

bash
pip install gradio pandas scikit-learn matplotlib seaborn nltk

Run
Copy code
pip install gradio pandas scikit-learn matplotlib seaborn nltk
Run All Cells: Execute all cells in the notebook from top to bottom. In Google Colab, you can do this by going to Runtime -> Run all.

Interact with the Model: Once all cells have run, a Gradio interface will launch (either directly in Colab or as a local web server). You can then type your own flight-related sentences into the provided textbox to get real-time sentiment predictions and confidence scores.

📜 Author
Prathik — This project was created as part of an internship project submission.

📊 Conclusion
This sentiment analysis project on airline-related tweets effectively demonstrates the application of Logistic Regression with TF-IDF vectorization for classifying tweets into Positive, Neutral, and Negative categories.

Key Insights:

The sentiment distribution indicates a higher frequency of negative tweets, suggesting passengers are more inclined to share complaints.
The confusion matrix highlights the model's strong performance in detecting negative sentiments, though some overlap occurs between neutral and positive classifications due to nuanced language.
Classification metrics confirm that Negative sentiment detection is the most robust, followed by Neutral, and then Positive.
Overall Performance: The model is particularly effective at identifying negative feedback, which can be invaluable for airlines in prioritizing customer service responses. Future enhancements could involve expanding the dataset, exploring more advanced models like BERT, or implementing sentiment-specific preprocessing techniques to further refine accuracy.

✈️ This workflow offers a practical approach for real-time airline monitoring systems, enabling quick responses to passenger feedback and mood tracking.

If using Google Colab, upload the natural_language_processing_for_sentiment_analysis.py notebook directly.
If running locally, ensure you have Python 3.8 or newer installed.
Install Dependencies: Open your terminal or Colab notebook cell and run the following command to install all necessary libraries:
