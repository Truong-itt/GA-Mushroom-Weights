# Genetic Algorithm for Finding Optimal Weights from Mushroom Data

This project implements a Genetic Algorithm (GA) to optimize weights for a neural network using mushroom dataset. The solution includes steps for data exploration, visualization, feature engineering, and applying GA to improve classification accuracy.
---

## Table of Contents
1. [Introduction](#introduction)
2. [Project Workflow](#project-workflow)
3. [Setup Instructions](#setup-instructions)
4. [Run Project](#run-project)
---

## Introduction

Genetic Algorithms (GA) are optimization algorithms inspired by the process of natural selection. In this project, GA is used to optimize the weights of a neural network to classify mushroom data efficiently. Key features include:
- **Activation Functions:** Sigmoid and ReLU
- **Fitness Function:** Accuracy
- **Genetic Operations:** Crossover and Mutation
---

## Project Workflow

### 1. **Data Exploration and Visualization**
   - Explore the mushroom dataset for insights.
   - Perform feature engineering to enhance the data representation.
   - Visualize features to understand their distributions and correlations.

### 2. **GA Implementation**
   - Encode the neural network weights into vectors for GA processing.
   - Fitness function evaluates weights based on accuracy.
   - Key components of GA:
     - **Mating Pool Selection:** Choose the best-performing weights.
     - **Crossover:** Combine parent weights to produce offspring.
     - **Mutation:** Introduce variations for diversity.
   - Iterate through generations to find the optimal weights.

---

## Setup Instructions
### Prerequisites
- Python 3.8+
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `tqdm`
## 4. **Run project**

Run the following command to install dependencies:
```bash
git clone https://github.com/Truong-itt/GA-Mushroom-Weights.git
cd GA-Mushroom-Weights
run code with ipynb
```
