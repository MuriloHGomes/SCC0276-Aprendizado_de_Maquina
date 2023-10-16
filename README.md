# SCC0276-Aprendizado_de_Maquina
Project developed in patership with [@JoaoBeinotti](https://github.com/JoaoBeinotti) throughout the course carried out during the undergraduate period. We used image processing and machine learning techniques to recognise and classify different ways of using masks to cover the face in the pandemic period. Among them, correct and incorrect ways of using mask.

Our aim was to obtain better results than the article ["Study of the Performance of Machine Learning Algorithms for Face Mask Detection"](https://ieeexplore.ieee.org/document/9310963), in the task of recognising the classifications of mask use presented in the database [Flickr-Faces-HQ](https://www.sciencedirect.com/science/article/pii/S2352648320300362?via%3Dihub). 

In the code of Final_Project.ipynb we do a test of the next pipeline:

  - Structuring the database;
  - Exploratory analysis of the database;
  - Choice of distinction criteria;
  - Sampling
  - Image description using Histogram of Oriented Gradient (HOG)
  - GridSearch with KNN, SVM and Neural Network (multilayer perceptron)

    We obtain the following table of results

    | Algorithm | Melhores hiper-parâmetros | ROC AUC (%) | Acurária (%) | Tempo (min) |
    | ------------- | ------------- | ------------- | ----------- | ------------- | 
    | KNN  | Nº neighbours: 7, weights: uniform| 95.7 | 95.7 | 15.58 |
    | SVM  | kernel: poly  | 99.4 | 99.4 | 45.85 |
    | MLPClassifier| activation: logistic, solve: lbfgs| 98.9 | 98.9 | 19.73 |
