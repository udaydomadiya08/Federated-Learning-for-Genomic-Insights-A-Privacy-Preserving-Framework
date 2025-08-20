NOTE:

  https://drive.google.com/file/d/1wtK9c7AZQhPjATwznIlsowlIhiMeJdYx/view?usp=sharing  //data file is located here
  code is given in ipynb fiel and research paper is also atttached

Federated Learning (FL) is a decentralized machine learning paradigm that enables multiple clients to collaboratively train a shared model without the need to exchange raw data, thereby preserving data privacy and security. In this project, three distinct models were developed with the following objectives:

Prediction of X vs. Y chromosomes

Classification of autosomes vs. sex chromosomes

Prediction of Infinium design type

Multiple federated learning strategies were implemented, including FedAvg, FedSGD, and FedProx, alongside a centralized baseline model for performance comparison. The best-performing model for each task was selected based on achieving the highest accuracy, and these models were deployed across the server and client nodes for training and iterative updates.

To ensure data confidentiality during model parameter exchanges, Homomorphic Encryption was employed for encrypting and decrypting model weights, allowing secure computations without revealing sensitive data.

The experiments achieved 88% accuracy in two chromosome classification models and 74% accuracy in predicting Infinium design type. These results demonstrate the potential of federated learning in genomic data analysis while maintaining strict privacy constraints. The outcomes of this research contribute to the broader scientific goal of advancing genomic understanding and potentially aiding in the long-term vision of biological immortality.
