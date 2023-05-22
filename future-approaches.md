# Sentiment analysis

## 1st approach (ME)

1- Get Sentence embeddings using BERT
2- then dropout layer 
3- then 1 unit dense layer


## 2nd approach(ME)
1- why dont we do both supervised (Text Classification) and unsupervised learning (Topic Modeling) using bertTopic since it is based on K-means


2- it will be summed by weight 0.8* log(Text Classification) + 0.2* log(Topic Modeling)
3- get max

or 

4- enter them both to a neural network of dense layer and make it decides the weights


## 3rd approach(ME)(Rule-based)
1- doc2vec : get the sum of the word2vecs in the sentence
2- add to it it's sentiment word2vec (in training)
3- then on input get doc2vec of it add each sentiment to it and check on each sentiment with training corpus cosine simaliraty  (test)

## 3rd approach(ME)
1 - use zero shot classification

# Topic modeling (TOPICS ARE NOT PREDEFINED)

## 1st approach (ME)
1- summarize the documents (if text is too big)
2- we get the topics my LDA
3- Each topic vector is the average of the word embeddings of the words that belong to that topic

4- get the document summarization embedding  by :
	- averaging the word embeddings in it 
	- sentence embedding averaging
	- doc2vec
5- compute the cosine similarity between the sentence embedding and each topic vector, and the topic with the highest similarity score is assigned to the sentence

import spacy
import numpy as np

##### Load a pre-trained word embedding model
nlp = spacy.load("en_core_web_md")

##### Define the words to average
words = ["king", "man", "woman"]

#### Compute the average embedding
word_embeddings = [nlp(w).vector for w in words]
avg_embedding = np.mean(word_embeddings, axis=0)

#### Find the most similar word to the average embedding
vocab = nlp.vocab
most_similar = None
max_similarity = -1.0
for word in vocab:
    if word.has_vector:
        similarity = avg_embedding.dot(word.vector) / (np.linalg.norm(avg_embedding) * np.linalg.norm(word.vector))
        if similarity > max_similarity:
            most_similar = word.text
            max_similarity = similarity

print("Most similar word to", words, "is", most_similar)


## 2nd approach

1- 



# Topic Modeling (TOPICS ARE PREDEFINED)
# 1st approach 
1- use BERTopic  or Top2Vec
# 1st approach (ME)
1-summarize the documents (if text is too big)
2- get topic embeddings
3- get the document summarization embedding  by :
	- averaging the word embeddings in it 
	- sentence embedding averaging
	- doc2vec
4- compute the cosine similarity between the sentence embedding and each topic embeddings, and the topic with the highest similarity score is assigned to the sentence

# 2 approach(ME)
1- simply do zero shot classification

# 3 approach (ME)
1- text summarization (if text is too big)
2 - DO LDA get the topic X Words matix
4- know the document belongs to which Topic A
5- get Topic A average word embeddings 
6- get the word embedding of each predefined topic 
7- do cosine similarity the most similar will win




# Data Augmentation
## 1 Approach
1- by replacing words with matching lexicons and embeddings



# Evaluation :
when there are overlapping features across different sentiment labels


