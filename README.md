

-----

# JKN Mobile Sentiment Analysis

Ever wondered what users *really* think about the JKN Mobile app? 🤔 This Google Colab project dives deep into user reviews, performing **sentiment analysis** to uncover valuable insights\! We're putting three popular machine learning algorithms to the test: **Support Vector Machine (SVM)**, **K-Nearest Neighbors (KNN)**, and **Naive Bayes**, to see which one reigns supreme in classifying review sentiments.

-----

## 🚀 Introduction

The JKN Mobile application is a vital tool for accessing healthcare services in Indonesia. Understanding user sentiment directly from their reviews can offer a goldmine of information for app improvements and service enhancements. This project aims to automate that understanding by implementing and comparing the effectiveness of different machine learning models for sentiment classification.

-----

## ✨ Project Goals

Our main missions in this project are to:

1.  **Prepare the Data:** Get those raw JKN Mobile app review texts squeaky clean and ready for analysis. 🧹
2.  **Build the Models:** Train awesome sentiment classifiers using SVM, KNN, and Naive Bayes.
3.  **Compare & Conquer:** Evaluate and benchmark the performance of these three algorithms using key metrics like accuracy, precision, recall, and F1-score. 📊
4.  **Colab Power:** Showcase the entire sentiment analysis pipeline seamlessly within a Google Colab environment. 🚀

-----

## 📚 Dataset

The heart of this project is a collection of reviews **scraped from the Google Play Store** for the JKN Mobile application. This dataset is expected to contain the review text itself, along with its corresponding sentiment label (e.g., positive, negative, neutral). The specific source and format of the dataset are handled within the notebook.

-----

## 🛠️ Methodology

Our sentiment analysis journey follows these key steps:

1.  **Data Loading:** Bringing in the JKN Mobile review dataset.
2.  **Text Preprocessing:** Cleaning up the raw text – think lowercasing, removing punctuation, tokenization, kicking out stop words, and getting words to their roots (stemming/lemmatization). 🛀
3.  **Feature Extraction:** Transforming our clean text into numerical features that our machine learning models can understand (like **TF-IDF**).
4.  **Model Training:** Teaching our SVM, KNN, and Naive Bayes classifiers to recognize sentiment patterns. 🧠
5.  **Model Evaluation:** Checking how well each model performed using standard classification metrics.
6.  **Comparison:** Analyzing the strengths and weaknesses of each algorithm to find the best fit for JKN Mobile sentiment analysis. 🎯

-----

## 📂 Code Structure

Everything you need to run this analysis is packed into one neat Google Colab notebook:

  * `sentimen_knn,svm,naive.ipynb`: This is your go-to file\! It contains all the Python code for data loading, preprocessing, model training, evaluation, and crucial comparisons.

-----

## 🏃‍♀️ How to Run

Ready to see it in action? It's super easy\!

1.  **Open the Notebook:** Just click on the `sentimen_knn,svm,naive.ipynb` file in this repository, then hit "Open in Colab" at the top.
2.  **Run All Cells:** Once it's open in Google Colab, simply go to `Runtime` -\> `Run all`. Watch the magic happen\! ✨
3.  **Step-by-Step:** Prefer a guided tour? You can also execute each cell individually to understand every single step of the process.

**Heads Up\!** 🚨 You might need to adjust the path to your dataset inside the notebook if it's not directly uploaded or linked from Google Drive.

-----

## 📦 Dependencies

This project relies on standard Python libraries for data science and machine learning. Most of these are pre-installed in Google Colab, but if you're running it locally, ensure you have:

  * `pandas`: For handling our data like a pro. 🐼
  * `numpy`: For all those numerical operations.
  * `scikit-learn`: Our powerhouse for ML models (SVM, KNN, Naive Bayes\!), feature extraction, and evaluation metrics.
  * `nltk`: For all things natural language processing. 🗣️
  * `matplotlib` & `seaborn`: If we're getting fancy with visualizations\! 📈

-----

## 📊 Results

Once you run the notebook, you'll get a clear picture of how each classifier performed. Expect to see:

  * **Accuracy scores** for each model.
  * **Precision, Recall, and F1-scores** for each sentiment class (positive, negative, neutral).
  * **Confusion matrices** to visualize classification performance.

These results will help you figure out which algorithm truly excelled at understanding JKN Mobile user sentiments\! 🏆

-----

## 🤝 Contributing

Got ideas to make this project even better? Found a bug? We'd love your help\!

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourAwesomeFeature`).
3.  Make your brilliant changes.
4.  Commit your changes (`git commit -m 'Add some amazing feature'`).
5.  Push to the branch (`git push origin feature/YourAwesomeFeature`).
6.  Open a Pull Request. We're excited to see your contributions\! 🎉

-----

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and adapt it\!

-----

## 📧 Contact

Questions, feedback, or just want to chat about sentiment analysis? Don't hesitate to reach out\!

  * **GitHub Issues:** [Create an issue right here\!](https://www.google.com/search?q=https://github.com/meryzennn/sentiment_analysis_of_jkn_mobile_app_reviews_using_svm_knn_and_naive_bayes/issues) 🐛

-----
