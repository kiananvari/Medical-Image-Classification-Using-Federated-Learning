# Medical-Image-Classification-Using-Federated-Learning
This project aims to classify COVID-19 Lung CT scans into two classes, namely COVID and NonCOVID, using federated learning techniques. The objective is to ensure data privacy by keeping the data distributed across multiple local servers, while still achieving a global model through aggregation and collaboration.

# Project Overview
The project consists of one global server and three local servers, each representing a different country. The big dataset of each country is added to their respective local servers. The classification models are trained individually on each local server using the local data.

To maintain data privacy, the raw data is not sent to the global server. Instead, the local models are aggregated using certain approaches to create a global model. This approach is inspired by the paper "Effectiveness of Federated Learning and CNN Ensemble Architectures for Identifying Brain Tumors Using MRI Images."

Once the global model is updated and created, it is pushed back to the three local servers, ensuring that the data remains near each local server and does not leave the respective countries. This process resembles federated learning, where the global model is improved collaboratively without sharing sensitive data.

# Results
The performance of the global model on the test dataset can be found below:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

# Acknowledgments
This project was inspired by the paper "Effectiveness of Federated Learning and CNN Ensemble Architectures for Identifying Brain Tumors Using MRI Images." We appreciate the authors for their valuable insights and research.
