# MACHINE-LEARNING-MODEL-IMPLEMENTATION   

NAME: HARSHINI J

INTERN ID: CT04DG2834

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION

In this project, I worked on building a Spam Message Classifier using Python and Scikit-learn. The entire implementation was done inside a Jupyter Notebook environment. The goal was to create a machine learning model that could classify messages as either spam or ham (not spam) by learning from a real-world dataset. I learned how machine learning works in theory, but how to actually apply it using Python libraries and open datasets. I used a public dataset available on GitHub . I don't need to download or manually upload any files. That made my work reproducible, so others can run my notebook from start to finish without needing anything extra. The dataset was loaded directly using pandas.read_csv() and it had two columns: one for the label (spam or ham) and one for the message content itself.

 The libraries Pandas, Matplotlib, Seaborn, Scikit-learn, and some built-in Python functions are used for this project. Each of these libraries played a unique role in the development of this model. The library Pandas helped me load, clean, and manipulate the dataset. I could easily see the shape of the data, preview the top rows, and understand the distribution of spam vs ham messages. Matplotlib and Seaborn were used for data visualization. I used these libraries to create bar plots showing how many spam and ham messages were present. This visualization gave me a better idea of how balanced or imbalanced the dataset was. The class distribution understanding is very important in classification problems, and these libraries made that process very visual.

The core machine learning part was using the Scikit-learn. I created a text classification pipeline using CountVectorizer, MultinomialNB, and Pipeline. CountVectorizer converted the text messages into a bag-of-words format so that the machine learning model could work with it. The MultinomialNB is a Naive Bayes classifier suitable for text classification, learned patterns from the training data. I used train_test_split to divide the data into training and test sets, which helped me validate the model’s performance on unseen data.Training dataset was about 80 percent and testing dataset was about 20 percent. The user can type a message and the model will predict whether it's spam or not. This part made the project more interactive. I also used predict_proba() to show confidence scores, which adds more interpretability.

From this project, I gained hands-on experience in machine learning. I learned how to clean data, visualize it, build and evaluate a model, and it accept input from users. I also learned how to make my notebook clean, modular, and presentable enough for internship submissions and GitHub portfolios. Overall, this project helped me gain confidence in working with text data, pipelines, classification tasks, and collaborative tools like jupyter notebook and GitHub. I learned how to use the open datasets and simple models to solve real problems in a practical way.

OUTPUT








