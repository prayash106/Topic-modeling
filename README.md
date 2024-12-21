# Topic Modelling

This repository contains code for topic modeling of movie reviews using three different approaches: **unsupervised**, **semi-supervised**, and **supervised** methods.

### Models Used:
1. **Latent Dirichlet Allocation (LDA)** – An unsupervised topic modeling technique that discovers latent topics in a collection of documents by assuming each document is a mixture of topics and each word in the document is attributable to one of the document’s topics.
   
2. **CoRex (Corex Topic Modeling)** – A semi-supervised topic modeling technique that incorporates anchors to guide the discovery of topics based on a predefined set of seed words. This method combines unsupervised learning with some human-defined knowledge.

3. **OpenAI Model (Supervised)** – A supervised approach that uses OpenAI's language models to identify and categorize topics in text, allowing for fine-tuned, context-aware topic modeling.

### Features:
- **Data**: Movie reviews from the NLTK movie_reviews corpus.
- **Preprocessing**: Basic text cleaning (removal of punctuation, lowercase conversion).
- **Topic Discovery**: Each model is used to identify themes or topics within the reviews and evaluate their quality.
