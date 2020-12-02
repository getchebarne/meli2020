# meli2020
Code for Mercado Libre's 2020 Data challenge.

The cat2vec, dom2vec and word2vec folders implement category_id, domain_id and publication title mappings to vectors using the word2vec algorithm via the keras API. Get_item.ipynb builds the final array.

extract_features_sage.ipynb implements the graphSAGE algorithm in order to extract item embeddings using StellarGraph's API.

Finally, main.ipynb implements the candidate generator and the training of the stmp model (short-term memory priority).

