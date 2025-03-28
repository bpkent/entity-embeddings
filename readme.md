All About Entity Embeddings
=========

Let's suppose our primary task is to predict hypothetical house sale prices from a
variety of categorical and numeric features.

We also have a variety of ancillary tasks that come up:
- Visualize our data and helping non-technical stakeholders to interpet it.
- Predict if a house will be sold or rented
- Predict how long a house will stay on the market
- Predict rental rate if a house is rented instead of sold.

We want to learn embeddings for the common categorical variables that will
1. Improve prediction performance on our primary task
2. Transfer to the other tasks to improve them as well
3. Capture interpretable relationships between entities (i.e. categorical levels) via a
   distance/similarity function.


Work plan
=========
- Read, read, read
- Organize thoughts at a high level
- Refine the purpose, motivating examples and tasks, etc.
- Hands-on project (or two) with code and data
- Scientific study, if time permits and there's a need in the literature
    - Systematic experimentation
- Write up thoughts and results, either as a long blog post or a paper
