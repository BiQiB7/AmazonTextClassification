# Text Classification on Amazon Product Review Dataset
Dataset:  modified subset of the Amazon Arts and Crafts related product purchases, only including the ‘Review Text” and the corresponding rating {1,2,3,4,5} provided by the user. This can be considered a multi-class classification problem where your classes are the scores provided by the user {1,2,3,4,5}.

The notebook contains code, outputs and explaination. The outline is as following:
1.  Data Exploration and Visualization: We employed statistical analysis and created plots such as bar charts and box plots to uncover insights into the reviews and their associated ratings
2.  Text Processing and Normalization: We experimented with various text preprocessing techniques, including expanding contractions, removing punctuation, converting text to lowercase, replacing links with a placeholder, stemming and lemmatisation.
3.  Vector space Model and feature representation:
     - Text vectorisation methods, include Term Frequency (TF), Term Frequency-Inverse Document Frequency (TF-IDF), Bag-of-Words (BoW), N-gram Features, and Word Embeddings.
     - We used LogisticRegression as our  base model to evaluate the performance of these techniques, to identify the best-performing vectoriser.
4.  Model training, selection and hyperparameter tuning and evaluation: Explored various bag-of-words models, including Logistic Regression, RandomForest, XGBoost and LightGBM. We conducted hyperparameter tuning on each model using our preprocesed text data to optimise their performance
5.  Modelling text as a Sequence: Evaluated the performance of sequence-to-sequence model, including simple RNN, LSTM (with or without word embeddings), pretrained DistillBERT, and Transformer with BERT.
6. Topic Modelling of high and low ratings on reviews with ratings of 1 and 5, respectively, using Latent Dirichlet Allocation (LDA).
