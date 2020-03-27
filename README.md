# Spam Email Classifier

This project was done as final course project for CS418: Introduction to Data Science course at the University of Illinois at Chicago during the Fall 2019 term along with teammates [Yushenli1996](https://github.com/Yushenli1996) and [nathanhe789](https://github.com/nathanhe789).

----

We wanted to be able to classify if emails are spam or not spam by training on the [Spambase Dataset](https://archive.ics.uci.edu/ml/datasets/spambase) from UCI’s Machine Learning repository. 

In addition to solving the above problem, we wanted to be able to find out which specific words inside the email contribute more to finding out if emails are spam-related or not.

We used classification algorithms to identify if emails in the given dataset are spam or not, and clustering algorithms for text analysis on the dataset of emails.

Check out the [Jupyter Notebook](SpamEmailClassifier.ipynb "Spam Email Classifier") or [the project report](https://docs.google.com/document/d/1HDNRm1eo5YnTJG1SPG9VdGhRVKZpo7TECoHNzEcC2sY/edit?usp=sharing "Final Project Report") to see the data science flow implemented.

----

**Project Background**

The main focus of this project revolves around the constant issue of modern spam emails and the countermeasure study of spam mail identification. Fraudulent companies, scammers, and robocalls often find a way to get a hold of email addresses somehow and exploit that. As a result, they flood everyone’s email inbox with a myriad of irrelevant information. To counter this exploitation, large corporations have implemented their own email filtering system to detect and identify suspicious emails, whether it actually does contain a harmful computer virus or spam email, and separate those emails from actual useful emails for individuals. Such big public companies like Google have their own Gmail system with built-in spam email recognition and filtering to reduce the chances of people falling for suspicious spam emails. This project dives deeper into the internal design system of spam email recognition and filtering system. To do so, a dataset provided by the University of California at Irvine and Hewlett-Packard is used to examine the filtering classification algorithm. The dataset is used for Hewlett-Packard Internal-only Technical Report; therefore, it only contains sensitive keywords that Hewlett-Packard requires.