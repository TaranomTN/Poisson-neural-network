# Poisson-neural-network
# DoctorVisits Model Comparison

This project compares the performance of three machine learning models on the DoctorVisits dataset:

- XGBoost
- Random Forest
- Poisson Neural Network

## 📁 Files

- `Poisson-neural-network.ipynb`: Colab notebook containing data preprocessing, model training, and results comparison.
- `DoctorVisits.csv`: Dataset used in the notebook.

## 📊 Evaluation Metrics

| Model             | RMSE   | R²     |
|------------------|--------|--------|
| XGBoost          | 0.7068 | 0.4350 |
| Random Forest    | 0.6571 | 0.5117 |
| Poisson NN       | 0.6364 | 0.5420 |

## 🔧 Requirements

- Python 3.x
- Colab (or Jupyter)
- Required libraries: pandas, numpy, sklearn, xgboost, torch

## 📌 Notes

- Poisson Neural Network was trained with 4000 epochs.
- The goal was to model doctor visits count using different machine learning approaches.

## 📬 Contact

Created by [Tarannom Torabi](mailto:taranom.torabi1377@gmail.com) — feel free to reach out with any questions or feedback!
