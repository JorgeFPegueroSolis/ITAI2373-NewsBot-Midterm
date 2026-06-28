This folder contains all the `.py` and `.pkl` files needed to build the 
NewsBot Agent used in `NewsBotAgent.ipynb`.

- `.py` files contain the core functions developed in earlier notebooks 
  (preprocessing, POS analysis, syntax analysis, sentiment analysis).
- `.pkl` files contain the trained components saved with `joblib` 
  (the classifier model, the TF-IDF vectorizer, the label encoder, and 
  the expected feature columns).

Together, these files are loaded by `NewsBotAgent.ipynb` to classify news 
articles, analyze their sentiment, and extract their syntactic features, 
without needing to retrain anything.
