# Word2Vec-Skip-Gram-Embeddings-Experiments
Implemented NLP model, ran experiments on parameters &amp; provided in-depth explanations

Explored TensorFlow's Word2Vec skip-gram tutorial: built embeddings from text corpus using negative sampling. Experiments: (1) Increased skip window – model improved (lower training error, semantically richer neighbors) by capturing broader context; (2) Reduced vocab_size to 500 – accuracy dropped due to excessive [UNK] mappings, losing nuance; (3) Explained NCE loss (approximates softmax via true/noise classification for efficiency); (4) [UNK] replaces rare words to manage vocab size/OOV; (5) t-SNE varies per run from stochastic init/randomness; (6) Antonyms close as they share contexts (distributional similarity). Submitted Q&A report with interpretations. AI certificate coursework.


