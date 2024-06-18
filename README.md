# Wikipedia_Toxicity
''' Using NLP and machine learning, make a model to identify toxic comments from the Talk edit pages on Wikipedia. Help identify the words that make a comment toxic.'''
In my project on detecting Wikipedia toxicity, I built a machine-learning model using a Support Vector Machine (SVM) classifier. This project involved developing a text classification model using Natural Language Processing (NLP) techniques and an SVM to identify toxic comments. The dataset I used included columns such as ID, Comment Text, and Toxic, where the 'Toxic' column indicates whether a comment is toxic.

The first phase of the project involved data preprocessing, which included cleaning the text data by removing stop words, punctuation, and other irrelevant characters. I also performed tokenization, stemming, and lemmatization to standardize the text. Additionally, I converted the text data into numerical representations using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) to prepare it for the SVM classifier.

Once the data was preprocessed, I split the dataset into training and testing sets to evaluate the model's performance. I then trained the SVM classifier on the training data, optimizing hyperparameters to improve accuracy and generalization. The SVM was chosen for its effectiveness in high-dimensional spaces and its ability to handle the binary classification task of detecting toxic comments.

During the evaluation phase, I assessed the model's performance using metrics such as accuracy, precision, recall, and F1-score. These metrics provided insights into the model's ability to correctly identify toxic comments while minimizing false positives and false negatives. The results showed that the SVM classifier was effective in detecting toxicity in comments, demonstrating good generalization on the test set.

Additionally, I conducted error analysis to understand the model's weaknesses and areas for improvement. This involved analyzing misclassified examples to identify patterns or specific types of toxicity that the model struggled with. Based on this analysis, I made iterative improvements to the preprocessing steps and model parameters.

Overall, this project highlighted the potential of using SVM classifiers in combination with NLP techniques for text classification tasks like toxicity detection. The insights gained from this model can be applied to improve content moderation systems on platforms like Wikipedia, helping to create a safer and more respectful online environment.
