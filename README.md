# Ensemble-Learning-Comparison-on-Diabetes-Classification
Comparison of ensemble learning methods on diabetes disease classification with various datasets

## About The Project

* This project compares various ensemble learning techniques for the classification of diabetes disease. Ensemble methods combine multiple machine learning models to improve predictive performance and robustness.
* In this project, we explore and compare the effectiveness of popular ensemble algorithms, such as Random Forest, AdaBoost, Gradient Boosting, and more, in diagnosing diabetes based on three different datasets of relevant features.
* Key Features:
  - Implementation of different ensemble methods for classification
  - Evaluation and comparison of model performance using metrics like accuracy, precision, recall, and F1-score
  - Jupyter notebooks with detailed explanations and visualizations
  - Dataset used for experimentation
  - Code for preprocessing, model training, and evaluation
* This project has already been published in JMASIF (Jurnal Masyarakat Informatika) with the title [Perbandingan Metode Ensemble Learning pada Klasifikasi Penyakit Diabetes](https://doi.org/10.14710/jmasif.13.1.42912).

## Technology Used
* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* xgboost
* lightgbm
* catboost

## Objectives/ Problems

Diabetes is a medical condition characterized by elevated blood sugar levels. According to the World Health Organization (WHO), the number of diabetes cases increased from 108 million to 422 million between 1980 and 2014. Machine Learning offers methods like Ensemble Learning for diabetes classification. This study compares three Ensemble Learning techniques, namely Bagging, Boosting, and Stacking, using three datasets: Pima Indians Diabetes, Frankfurt Hospital Diabetes, and Sylhet Hospital Diabetes.

## Dataset Used
1. [Pima Indians Diabetes Database by UCI Machine Learning](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
2. [Frankfurt Hospital Diabetes Dataset by John](https://www.kaggle.com/johndasilva/diabetes)
3. [Sylhet Hospital Diabetes Dataset by Ishan Dutta](https://www.kaggle.com/ishandutta/early-stage-diabetes-risk-prediction-dataset)

## Workflow
- Data Preprocessing
  - MinMaxScaler for each dataset (change range of data to to fall within 0 and 1)
- Data Exploration
- Feature Engineering
- Data Splitting
  - 80% Training data
  - 20% Testing data
- Model Building
- Model Training & Testing
- Model Evaluation
  - Accuracy
  - Precision
  - Recall
  - F1-score

## Algorithms/ Methods
- Bagging
	- Bagging
	- Random Forest
	- Extra Trees
- Boosting
	- Adaptative Boosting
	- Gradient Boosting
	- Extreme Gradient Boosting
	- Light Gradient Boosting
	- Cat Boosting
- Stacking
	- Stacked Generalization

## Performance (Accuracy)
### Dataset 1 (Pima Indians Diabetes Database)
![images/Grafik%20Akurasi_Dataset%201.png](images/Grafik%20Akurasi_Dataset%201.png)
### Dataset 2 (Frankfurt Hospital Diabetes Dataset)
![images/Grafik%20Akurasi_Dataset%202.png](images/Grafik%20Akurasi_Dataset%202.png)
### Dataset 3 (Sylhet Hospital Diabetes Dataset)
![images/Grafik%20Akurasi_Dataset%202.png](images/Grafik%20Akurasi_Dataset%202.png)

## Conclusion
* In general, all Boosting methods give the best results for all datasets, but specifically, the Light Gradient Boosting method gives the best results in most of the data (Dataset 2 & Dataset 3)

## Publications
* L. M. Cendani, and A. Wibowo, "*Perbandingan Metode Ensemble Learning pada Klasifikasi Penyakit Diabetes,*" JURNAL MASYARAKAT INFORMATIKA, vol. 13, no. 1, pp. 33 - 44, May. 2022. https://doi.org/10.14710/jmasif.13.1.42912

## Contributors
* [Linggar Maretva Cendani](https://github.com/LinggarM) - [linggarmc@gmail.com](mailto:linggarmc@gmail.com)
* Adi Wibowo - [bowo.adi@live.undip.ac.id](mailto:bowo.adi@live.undip.ac.id)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
- [UCI Machine Learning - Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [John - Diabetes Dataset](https://www.kaggle.com/johndasilva/diabetes)
- [Ishan Dutta - Early Stage Diabetes Risk Prediction Dataset](https://www.kaggle.com/ishandutta/early-stage-diabetes-risk-prediction-dataset)
