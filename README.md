# Music-Recommendation-System-using Spark’s ML
Music Recommendation System  using Spark's ML


## Overview

This repository contains the implementation of a Song Recommendation System that provides personalized song and artist recommendations based on user listening history. Leveraging big data technologies, including Apache Spark, PySpark SQL, Hive, and TensorFlow, the system processes large-scale datasets to build a scalable and efficient recommendation engine suitable for real-time deployment.

## Key Features

- **Collaborative Filtering**: Utilizes the Alternating Least Squares (ALS) algorithm from Spark MLlib to predict user preferences.
- **Real-Time Recommendations**: Integrates historical and real-time data to continuously update song recommendations.
- **Data Processing**: Uses PySpark SQL for efficient querying and processing of large datasets.
- **Neural Collaborative Filtering**: Implements deep learning models with TensorFlow to capture complex user-item interactions.
- **AWS Deployment**: Deployed using AWS SageMaker for scalable model training and hosting.
- **Hive Integration**: Employs Apache Hive as a data warehouse for managing extensive user and song datasets.

## Technologies Used

- **Apache Spark**: Distributed computing system for handling massive datasets.
- **PySpark SQL**: Python interface for querying and processing data within Spark.
- **MLlib**: Spark’s scalable machine learning library used for collaborative filtering.
- **TensorFlow**: Deep learning framework for building advanced neural networks.
- **Hive**: Data warehouse system for managing large-scale data storage.
- **AWS SageMaker**: Managed service for building, training, and deploying machine learning models.

## Problem Statement

The music streaming industry faces challenges in providing personalized recommendations due to enormous and continuously growing music libraries. This project aims to develop a recommendation engine that delivers highly personalized and accurate song and artist suggestions, thereby enhancing user engagement and retention.

## Approach

1. **Data Preprocessing**: 
   - Clean and process historical user interaction data.
   - Prepare user-song interaction records for model training.
2. **Collaborative Filtering**:
   - Apply the ALS algorithm to build a user-item matrix for predicting preferences.
3. **Neural Collaborative Filtering**:
   - Implement deep learning models using TensorFlow to capture complex relationships.
4. **Performance Evaluation**:
   - Measure model performance using metrics such as precision, recall, and F1-score.
5. **Real-Time Updates**:
   - Incorporate real-time data to adapt recommendations as user preferences evolve.
6. **Deployment**:
   - Deploy the model using AWS SageMaker to enable scalable, real-time recommendations.

## Setup Instructions

### Clone the Repository

```bash
git clone https://github.com/your-username/song-recommendation-system.git
cd song-recommendation-system

### Top 10 Most-Played Artists
![image](https://github.com/user-attachments/assets/da87a32b-e31d-463f-b42d-595a2bd6beac)


### Top 5 Artists by Play Count
![image](https://github.com/user-attachments/assets/ce7f3145-9ec1-47f7-b8d0-2c02e156ff2a)


### Tensor Board 
![image](https://github.com/user-attachments/assets/17c971c8-edb9-4177-8640-3afc7ec5d6ae)




