# Restaurant_reviews

# What is BERTopics and Why using it?
BERTopics (Bidirectional Encoder Representations from Transformers) is a state-of-the-art topic modeling technique that utilizes transformer-based deep learning models to identify topics in large text collections. There are several benefits of using BERTopics for topic modeling:

1. Improved topic quality: BERTopics has been shown to produce more coherent and interpretable topics compared to traditional topic modeling techniques, such as Latent Dirichlet Allocation (LDA).
Better handling of large text collections: BERTopics can handle large text collections effectively, which is crucial for modern text data.
2. Ability to capture semantic relationships between words: BERTopics leverages the representation power of transformers to capture the semantic relationships between words in the text, which results in more accurate and meaningful topics.
3. Fine-grained control of the number of topics: Unlike other topic modeling techniques, BERTopics provides fine-grained control over the number of topics to be extracted, which can be useful in applications where the number of topics is critical.
4. Easy to fine-tune: BERTopics is trained on large text corpora, which means it can be fine-tuned on specific text collections, leading to improved performance on these collections.
# The Scenario
In this project, we are going to learn by example. The example also serves as the Cookbook which we can use a template for the future use cases. We are going to use a dataset of “restaurant reviews” from Kaggle [https://www.kaggle.com/datasets/vigneshwarsofficial/reviews] to categorize the reviews from the patrons into different meaningful categories: “Environment”, “food”, “staff”, “service” and so on.<br>
At the end of this project, instead of going through the whole dataset, we will categorize the restaurant reviews from patrons into meaningful categories such as "Environment," "food & taste", "Overall Experience", and "staff." The specific department managers will receive a CSV file containing reviews about their department, saving them the effort of searching through the entire dataset.
