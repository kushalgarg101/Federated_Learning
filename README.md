# Federated Learning 

Federated Learning is a decentralized machine learning paradigm that enables multiple devices or organizations to collaboratively train a shared model without exchanging raw data. Instead of centralizing data in one location, the model is distributed to local devices (e.g., smartphones, IoT devices, or hospitals), where it is trained on local datasets. Only model updates (e.g., gradients or parameters) are sent back to a central server, which aggregates them to improve the global model. This process iterates, refining the model while keeping data decentralized.

Problems it solves:

1.Avoids centralizing sensitive data (e.g., medical records, personal messages), reducing risks of breaches and ensuring compliance with regulations like GDPR or HIPAA.
2.Enables collaboration across entities (e.g., hospitals, banks) that cannot legally or ethically share data.

This approach helps to train model on more data than it could have been using traditional approach.

Flower ai is a framework which allows us to carry out federated learning.
Check documentation here:  [Flowerai](https://flower.ai/docs/framework/index.html).

Reference [https://www.deeplearning.ai/short-courses/intro-to-federated-learning/]
