Built a few models that were trained using the data set from https://www.kaggle.com/competitions/titanic/overview where the end goal is to accurately predict the survival chances of an individual on the titanic based on their attributes. 

All models that were used were from ScikitLearn and were tried out with different parameters in hopes of improvising accuracy. 

Models used:
- KNeighborsClassifier
- LinearSVC
- HistGradientBoostingClassifier (Ensemble using boosting)
- RandomForestClassifier (Ensemble using bagging)

Data was also cleaned and reorganised by:
- Filling missing values with mean/median/mode
- Converting text data to numbers 
- Scaling data so features are equality treated and model isn’t affected by large and extreme values
