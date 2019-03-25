## Hidden_Markov_Model

### Probabilistic states and transitions

1. Set up a new git repository in your GitHub account
2. Pick a text corpus dataset such as https://www.kaggle.com/kingburrito666/shakespeare-plays or from https://github.com/niderhoff/nlp-datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to learn word correlations and distributions within the dataset
5. Build a Hidden Markov Model to be able to programmatically
  1. Generate new text from the text corpus
  2. Perform text prediction given a sequence of words
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub

## Assignment 2 - Machine Learning
### Submitted by : Priyanka Saha

- Selected text corpus - Shakespeare Plays contained under **data** as **alllines.txt**

- Text data is very rich source of information and on applying proper Machine Learning techniques, we can implement a model to learn word correlations and distributions. To start with, the words can be represented in vector form such that similar words used in a similar context are close to each other in the vector space. Now applying different techniques e.g. Bag of words concept, the missing words can be filled given it's neighboring context. Hence to put this idea in general term, we can represent a word using an index and learn to represent it using a dimensional vector such that the mappings capture some relation and similarity in words.

- The notebook **Text Generation & Simple Prediction.ipynb** contains the approach and implementation of a Hidden MArkov Model to 1) Generate new text and 2) Perform text prediction given some observations. The notebook is self contained and got all the steps/explanations documented in place. The results of both functions have been included as well.

                                   -----------------------------------------------
