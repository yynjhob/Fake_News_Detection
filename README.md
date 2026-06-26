### Fake News Detection - LLM + Classical ML

A two-stage credibility assessment pipeline combining LLM-derived semantic features with traditional ML classifiers across textual, social, and temporal dimensions. Achieves 98% accuracy on the FakeNewsNet dataset.

---
## Key Finding

The architecture was reshaped by a counterintuitive result: **propagation pattern features consistently outperformed content features**. How information spreads - velocity, clustering, and temporal burst patterns in the first propagation window — was a stronger signal of inauthenticity than what the content actually said.

This shifted the design from a pure NLP problem to a multi-dimensional signal problem.

---
## Tech Stack

`Python` `Transformers` `XGBoost` `LangChain` `scikit-learn` `pandas` `NumPy`
