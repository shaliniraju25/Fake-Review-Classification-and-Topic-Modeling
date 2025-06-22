# Fake-Review-Classification-and-Topic-Modeling

👋 Hello Everyone,
Today I’ll be presenting my project on Fake Review Classification and Topic Modeling.
Let me walk you through the entire process step by step.

🧠 What's the project about?
We all read reviews before buying anything online. But not all reviews are genuine — some are fake and misleading.
So, the goal of my project is twofold:

To detect whether a review is real or fake using machine learning.

To understand what customers are generally talking about in reviews using a technique called topic modeling.

📊 What data did I use?
I worked with a dataset that contains a bunch of product reviews — some are labeled as real, and others as fake.
Each review is just plain text, and there’s a label attached to say whether it’s fake or not.

🧹 How did I clean the data?
Before feeding this data to a machine learning model, I had to clean it:

I converted all the text to lowercase.

Removed unwanted stuff like punctuation, numbers, and common stopwords like "the", "is", "and".

Then I broke each review into words (tokenization) and converted those words to their root form using lemmatization.

This helps the model focus on the meaningful words in each review.

🔍 What did I learn from exploring the data?
I used visual tools like WordCloud to see which words were used most often.
I also plotted how many fake and real reviews are there — this gave me an idea of the data balance.

🧪 Which machine learning models did I use?
To classify reviews as fake or real, I trained a few different models:

Logistic Regression

Random Forest

Naive Bayes

Support Vector Machine (SVM)

Before that, I used TF-IDF vectorizer to turn the review text into numbers — because ML models can’t work with plain text.

I then trained the models and checked which one performed best using metrics like accuracy, precision, recall, and F1-score.

📚 What about Topic Modeling?
Next, I used LDA – Latent Dirichlet Allocation to understand the themes or topics in the reviews.
This helped me see what users talk about most — like delivery issues, product quality, customer service, etc.

To make it visual and easier to understand, I used pyLDAvis, which shows how the topics are distributed.

✅ What did I find?
One of the models (e.g., Random Forest or Logistic Regression) gave the best results in predicting fake reviews.

LDA helped identify hidden topics from the review text — even without labels.

💡 Why is this useful?
This project can be useful for e-commerce platforms and sellers — to filter out fake reviews and better understand real customer feedback.
It builds trust with customers and also helps improve products or services.

🙏 Thank You!
That’s all from my side. 
