## Title of the Project
### Federated Graph Neural Network–Based Secure Recommendation System for Distributed E-Commerce Platforms

The integration of a privacy-preserving recommendation system within a distributed e-commerce platform, aimed at generating accurate personalized product suggestions while ensuring user data security.

## About
<!-- Detailed Description about the project -->

Federated Graph Neural Network–Based Secure Recommendation System is a project designed to enhance personalized recommendations in distributed e-commerce platforms while preserving user data privacy. Traditional recommendation systems rely on centralized storage of user interaction data, which leads to privacy risks, security vulnerabilities, and scalability issues.

This project overcomes these challenges by modeling user–product interactions as a graph and applying Graph Neural Networks (GNNs) to learn complex relationships. Federated learning enables collaborative model training across multiple e-commerce nodes without sharing raw user data. Secure aggregation ensures that only model updates are exchanged, making the system scalable, secure, and privacy-aware.

## Features
<!-- List the features of the project as shown below -->

- Privacy-preserving recommendation using federated learning.
- Graph Neural Network–based modeling of user–product interactions.
- A framework-based application suitable for deployment.
- High scalability for distributed e-commerce platforms.
- Reduced data leakage and centralized storage risks.
- Improved recommendation accuracy with low communication overhead.

## Requirements
<!-- List the requirements of the project as shown below -->

* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu).
* Development Environment: Python 3.8 or later for model development and integration.
* Machine Learning Frameworks: PyTorch and PyTorch Geometric for GNN implementation.
* Federated Learning Framework: Flower (FL) for distributed model training.
* Backend: Node.js / Flask (existing e-commerce backend).
* Database: MongoDB / MySQL for storing user and product data.
* Security: HTTPS and JWT authentication.
* IDE: Visual Studio Code for development and debugging.
* Version Control: Git and GitHub for source code management.

## System Architecture
<!-- Embed the system architecture diagram as shown below -->
<img width="1360" height="574" alt="image" src="https://github.com/user-attachments/assets/ac53ef97-a02e-4663-86eb-841e9f9c3bc0" />
<img width="1148" height="719" alt="image" src="https://github.com/user-attachments/assets/337c1084-fab1-4cad-b07b-e52de3fa620f" />
<img width="1104" height="709" alt="image" src="https://github.com/user-attachments/assets/e5f25123-42d9-486a-bfd5-cb583fbf315d" />


## Output
<!-- Embed the Output picture at respective places as shown below -->

#### Output1 – Personalized Product Recommendations
Displays recommended products based on user interaction history learned through federated graph neural networks.
<img width="1353" height="476" alt="image" src="https://github.com/user-attachments/assets/2d9b3906-0be5-47a8-bb9f-7e5ad710507f" />
<img width="824" height="719" alt="image" src="https://github.com/user-attachments/assets/7cbd551c-04db-455b-81f9-35100357a749" />


#### Output2 – Privacy-Preserving Federated Training
Shows distributed training across multiple simulated e-commerce nodes without sharing raw user data.
<img width="744" height="740" alt="image" src="https://github.com/user-attachments/assets/f0af4e38-658f-45ce-b327-b5785307de24" />
<img width="1259" height="713" alt="image" src="https://github.com/user-attachments/assets/42bcec7e-0443-4ad2-b1c8-8fded8c68e47" />
<img width="728" height="726" alt="image" src="https://github.com/user-attachments/assets/6a1bbb89-4f8e-48c0-9e53-af9070e55362" />


Recommendation Accuracy: ~94%  
Note: Performance metrics may vary based on dataset size and interaction density.

## Results and Impact
<!-- Give the results and impact as shown below -->

The proposed system improves recommendation accuracy while ensuring strong privacy protection by eliminating centralized user data storage. Federated learning enables secure collaboration across distributed nodes, and graph neural networks effectively capture complex user–product relationships. This project demonstrates a scalable and secure recommendation solution suitable for real-world e-commerce platforms.

## Articles published / References

1. McMahan, B., et al., “Communication-Efficient Learning of Deep Networks from Decentralized Data,” AISTATS, 2017.
2. Wu, Z., et al., “A Comprehensive Survey on Graph Neural Networks,” IEEE Transactions on Neural Networks and Learning Systems, 2020.
3. Kairouz, P., et al., “Advances and Open Problems in Federated Learning,” Foundations and Trends in Machine Learning, 2021.
