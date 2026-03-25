Project Title:
Block Hunter: Federated Learning for Cyber Threat Hunting in Blockchain-based IIoT Networks
Description:
This project focuses on detecting cyber threats in blockchain-based Industrial Internet of Things (IIoT) networks used in smart factories.
The system uses Federated Learning (FL) to identify anomalies such as packet hijacking and packet drop without sharing sensitive data.
It ensures data privacy, security, and efficient threat detection by training machine learning models locally on devices and sharing only model updates.
Features:
Secure anomaly detection in IIoT networks
Federated Learning-based model (privacy-preserving)
Detection of cyber threats like:
Packet Hijacking
Packet Drop
Suspicious Activities
Accuracy visualization using graphs
User module:
Registration & Login
Upload network data for prediction
Service Provider module:
Train & test dataset
View results & accuracy
Download predicted datasets
Technologies Used:
Programming Language: Python
Frontend: HTML, CSS, JavaScript
Backend: Django (ORM)
Database: MySQL (WAMP Server)
Machine Learning:
Federated Learning
Deep Learning Models
How to Run:
Install Python and required libraries (TensorFlow, sklearn, etc.)
Set up MySQL database using XAMP Server
Run Django server:
python manage.py runserver
Open browser and go to:
http://127.0.0.1:8000/
Register/Login as User or Service Provider
Upload dataset or input data to detect cyber threats
Output
Predicts cyber threat type (Normal / Packet Drop / Packet Hijacking)
Displays accuracy, graphs, and results
Provides downloadable prediction reports
