# x-vector-anonymization-using-autoencoder-and-adversial-training-for-preserving-speech-privacy
this repository contains pytorch implementation of article "X-vector anonymization using autoencoders and adversarial training for preserving speech privacy"

jornal = Computer Speech & Language (CSL)

year = 2022

authors = Juan M. Perero-Codosero, Fernando M. Espinoza-Cuadros, Luis A. Hernández-Gómez b

<a href="https://www.sciencedirect.com/science/article/pii/S088523082200002X">link to original paper</a>

Notes :
* The authors of this article used x-vector but I used d-vector. They are all the same and are used for speaker embedding.
* I just implement the vector anonymization part
* I train on a much smaller dataset from Kaggle instead of VoxCeleb which is a huge dataset
* You only need an <a href="https://www.kaggle.com">Kaggle.com</a> account and request for an API key for downloading the dataset
