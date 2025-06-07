# IntroML-Summative
# Water Quality Model using Neural Network

## 📌 Project Objective

This project aims to develop and evaluate a neural network-based binary classification model that predicts whether water is **potable (safe to drink)** or **not potable**, based on various physicochemical attributes. Each team member contributes a unique model setup, applying distinct optimization strategies, and analyzing their model’s performance.

## 👥 Team Contribution

Each team member designed a personalized model variation using:
- Different **regularization methods**
- Custom **optimizers**
- Distinct **dropout rates**
- Tailored **early stopping criteria**
- Manually configured **learning rates**

This diversity allowed us to explore how tuning key hyperparameters affects the neural network’s performance.

## Dataset

We used the publicly available [water_potability.csv](https://drive.google.com/file/d/1VXHjV4Hi7d__I9v2KYudh32OVud3aEvm/view), which includes features like pH, hardness, solids, sulfate, conductivity, organic carbon, and more. The dataset was preprocessed, scaled, and split into training, validation, and test sets (70%, 15%, 15%).

## ⚙Model Setup & Techniques

Key techniques used across models:

| Component          | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Model Framework    | TensorFlow / Keras                                                          |
| Architecture       | Fully connected neural networks with 2 hidden layers                        |
| Regularization     | L1, L2, and Dropout (varied per member)                                     |
| Optimizers         | Adam, Adagrad, RMSprop                                                      |
| Dropout Rates      | Between 0.2 - 0.5                                                           |
| Early Stopping     | Patience between 5+ epochs                          |
| Evaluation Metrics | Accuracy, Precision, Recall, F1 Score, Confusion Matrix                    |

## Results Summary

Each team member trained their model and documented the outcomes. The results were evaluated on the test set using key classification metrics.

| Engineer           | Regularizer | Optimizer | Dropout | Early Stopping | Accuracy | F1 Score | Recall | Precision |
|-------------------|-------------|-----------|---------|----------------|----------|----------|--------|-----------|
| David Niyonshuti  | L2          | Adagrad   | 0.3     | Patience=5     | 0.7012   | 0.4806   | 0.3676 | 0.6939    |
| Omar Keita        | L1          | RMSprop   | 0.2     | Patience=8     | 0.6082   | 0.76     | 1.00   | 0.61      |
| Anne Marie        | L2          | Adam      | 0.3     | Patience=4     | 0.6870   | 0.4122   | 0.2919 | 0.7013    |
| Clinton Pikita    | L1          | Adam      | 0.3     | Patience=10    | 0.5427   | 0.65     | 0.69   | 0.62      |


> Full results and reflections available in the report below.

## Final Report

You can find a detailed breakdown of:
- Each member’s model configuration
- Reflections and reasoning behind parameter choices
- Comparative analysis across models
- Challenges encountered and lessons learned

👉 [**Access the Full Report Here**](https://docs.google.com/document/d/1o5iFmDgLVxZuoPW_-FcNzb93PbN5s4o2idLehAH5qiM/edit?usp=sharing)

## Authors
Contributors to the repo are:
- David Niyonshuti
- Anne Marie Twagirayezu
- Omar Keita
- Tanguy Kwizera
- Clinton Tanaka Pikita

