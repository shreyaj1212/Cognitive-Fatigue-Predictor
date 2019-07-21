This folder has three different models I made to predict whether a person is Cognitively Fatigued. I used signals processing to gather data about pulse, voice pitch, voice volume, and more. 

Analysis.ipynb is one model that has overfitted the data. It classifies people into "fatigued" and "not fatigued" based on whether their PVT scores are above or below the median PVT score. It is based on a small training set, and has a low – yet better than chance – accuracy.

Analysis_2.ipynb is another model that has overfitted the data, though less than Analysis.ipynb. It classifies people into "fatigued" and "not fatigued" based on whether their PVT scores are above or below the median PVT score. It is also based on a small training set, and has a low – yet better than chance – accuracy.

Regression.ipynb is a better model that uses Decision Tree Regression to predict a subject's PVT scores based on his or her select features. It has a fairly good accuracy; however, it is limited by a small dataset. The small number of features that are being assessed also limits the accuracy. 
