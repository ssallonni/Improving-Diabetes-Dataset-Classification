This project aims to improve the accuracy of diabetes dataset classification by replicating and extending the work of Fong and Motani's paper "Symbolic Regression Enhanced Decision Trees for Classification Tasks." Our goal is to identify key predictors and features commonly found in diabetes patients and accurately predict potential diagnoses.

The project uses the Diabetes Dataset from Kaggle, including numerical features such as pregnancies, glucose levels, blood pressure, BMI, and more. Preprocessing involved removing duplicates and null values and scaling the data with a RobustScaler to avoid skewing due to outliers.

We trained and tested traditional machine learning models such as AdaBoost, CatBoost, ExtraTreesClassifier, XGBoost, Gradient Boosting, LightGBM, RandomForestClassifier, and SVM. Additionally, we implemented various decision tree models, including Standard, Oblique, and Symbolic Regression Enhanced Decision Trees (SREDT), to assess their accuracy on the dataset. Our ensemble models produced notable results, with three of them (SVM, AdaBoost, and Gradient Boosting) achieving higher mean accuracy scores than the original paper, particularly with SVM showing significant improvement. However, while our SREDT model provided valuable insights, it showed minimal differences from the original paper, and our Oblique Decision Tree had lower accuracy.

Future directions include replicating deep learning models such as NODE and TabNet, completing ablation testing to explore the significance of individual features, and reducing noise to replicate the Oblique Decision Tree's accuracy better. For more details and ongoing work, visit our GitHub Repository.

https://medium.com/@salonisharma_46565/improving-diabetes-dataset-classification-11c39dbf4682
