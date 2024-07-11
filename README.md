# Nature-Inspired-Algorithms-for-IDS

## Overview

In today's digital age, cybersecurity plays a crucial role in protecting sensitive information and systems from unauthorized access and attacks. Intrusion Detection Systems (IDS) are pivotal in this realm, as they monitor network traffic, identify malicious activities, and alert administrators to potential threats.

This project focuses on building an Intrusion Detection System using machine learning techniques, specifically leveraging Nature-Inspired Algorithms (NIAs) such as Grey Wolf Optimization (GWO) and Particle Swarm Optimization (PSO). These algorithms simulate natural behaviors to optimize solutions and have shown promise in enhancing the performance of IDS.

## Nature-Inspired Algorithms

Nature-Inspired Algorithms draw inspiration from biological and physical phenomena to solve complex optimization problems. GWO mimics the social hierarchy and hunting mechanism of grey wolves to optimize solutions. PSO, on the other hand, models the social behavior of bird flocks or fish schools to iteratively improve solutions.

### Grey Wolf Optimization (GWO)

GWO is a metaheuristic optimization algorithm based on the leadership hierarchy and hunting mechanism of grey wolves. It optimizes a population of solutions by iteratively updating the positions of grey wolves (solutions) in search space.

### Particle Swarm Optimization (PSO)

PSO is a swarm intelligence-based optimization technique where particles (solutions) move through the search space, adjusting their positions based on their own best-known position and the global best-known position found by the swarm.

## Dataset

The NSL-KDD dataset is used in this project, obtained from Kaggle. It is an improved version of the widely used KDD Cup 1999 dataset, containing a variety of features extracted from network traffic data, with instances labeled as normal or attack types.

- **Dataset Description**: The NSL-KDD dataset improves upon the original KDD dataset by eliminating redundant records in the training set, ensuring classifiers are not biased towards more frequent entries. It also provides non-duplicate test sets, avoiding biases towards methods with higher detection rates on common records. The dataset's balanced selection across difficulty levels enables accurate evaluations of machine learning techniques, while its reasonable size allows for comprehensive experiments without random sampling, ensuring consistent and comparable research results.
- **Dataset Link**: [Dataset](https://www.kaggle.com/datasets/hassan06/nslkdd)

## Architecture of the Code

The architecture of the code involves several key components:

1. **Data Preprocessing**: Includes loading the dataset, handling missing values, and encoding categorical variables.
   
2. **Feature Selection**: Selecting relevant features to enhance the model's performance and reduce computational complexity.
   
3. **Model Training**: Utilizing GWO and PSO to optimize hyperparameters of machine learning models such as Support Vector Machines (SVM) or Neural Networks (NN).
   
4. **Evaluation**: Assessing model performance using metrics like classification accuracy, precision, recall, and F1-score.

## Results

### Final Result

- **Leader Particle Dimension**: 10
- **Leader Particle Fitness**: 0.9488806834178833
- **Leader Particle Classification Accuracy**: 0.9970764640284517

These results demonstrate the effectiveness of the optimized model in accurately classifying network traffic as normal or malicious.
