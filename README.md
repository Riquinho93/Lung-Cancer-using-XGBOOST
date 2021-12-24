# Lung Cancer using XGBOOST

📱 [APP] link: https://applungcancer.herokuapp.com/

![Cancer](https://github.com/Riquinho93/Lung-Cancer-using-XGBOOST/blob/main/assets/cancer.jpg)

📚 The effectiveness of cancer prediction system helps the people to know their cancer risk 
with low cost and it also helps the people to take the appropriate decision based on their cancer 
risk status. The data is collected from the website online lung cancer prediction system .


📋 Summarize dataset:
- Gender: M(male), F(female)
- Age: Age of the patient
- Smoking: YES=2 , NO=1.
- Yellow fingers: YES=2 , NO=1.
- Anxiety: YES=2 , NO=1.
- Peer_pressure: YES=2 , NO=1.
- Chronic Disease: YES=2 , NO=1.
- Fatigue: YES=2 , NO=1.
- Allergy: YES=2 , NO=1.
- Wheezing: YES=2 , NO=1.
- Alcohol: YES=2 , NO=1.
- Coughing: YES=2 , NO=1.
- Shortness of Breath: YES=2 , NO=1.
- Swallowing Difficulty: YES=2 , NO=1.
- Chest pain: YES=2 , NO=1.
- Lung Cancer: YES , NO.


📚 EXtreme Gradient Boosting (XGBoost) is an optimized distributed gradient boosting library designed to be highly efficient, 
flexible and portable. It implements machine learning algorithms under the Gradient Boosting framework.
XGBoost provides a parallel tree boosting (also known as GBDT, GBM) that solve many data science problems 
in a fast and accurate way. The same code runs on major distributed environment (Hadoop, SGE, MPI) and 
can solve problems beyond billions of examples.

📚 XGBoost is a fast and efficient algorithm used by the winners of many learning competitions
of machine. XG Boost only works with ​​numeric variables.

📋 XgBoost modeling consists of two techniques: 

- Bagging: is an approach where you can take random samples of data, build algorithms, learning and using simple means to find bagging probabilities.

- Boosting: It's an approach where the selection of the approach is done more intelligently, that is,
more weight is given to sort how to sort.

📋 Types of parameters:
- Booster parameters: It affects the boosting operation
- Learning Task parameters: It guides optmized perfomance
- General Parameters: It affects each Overall function

📋 Some parameters in XGBoost

- eta: reduces resource weights to make the boosting process more conservative.
The range is from 0 to 1. This is also known as the learning rate or reduction factor.
The low eta value means the model is more robust for overfitting.

- gama: the larger the gamma value, the more conservative the algorithm. Its range is from 0 to infinity.

- max_depth: The maximum depth of a tree can be increased using the max_dept parameter.

- subsample: is the proportion of rows the model will randomly select to grow trees.

- colsample_bytree: It is the proportion of variables chosen randomly to build each tree in the model.

👨‍💻 Tools used:
- Pandas(Data vizualization)
- Xgboost (XGBClassifier)
- Numpy (Scientific Computing)
- Matplotlib (Graphics and data vizualization)
- Seaborn (Data Visualization)
- Sklearn (Preprocessing and Metrics)
- Streamlit (Create data app)
- Heroku (deploy)



