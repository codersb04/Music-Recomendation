# Music-Recommendation

## Task:
Create a model to predict the genre of the music to be liked by a person in accordance with age and gender.</br>
This problem comes under <b>Supervised learning</b> as we have labelled the dataset. We will be using <b> Decision Tree Classifier</b> to achieve the result.

## Dataset:
Reference: Programming with Mosh,  https://bit.ly/3muqqta

## Steps involved:
<b>1. Import the necessary libraries and dataset:</b></br>
The libraries we will use to perform this task are Pandas, NumPy, Sklearn, and matplotlib. We will then import our data using the pandas read_csv function</br>
<b>2. Divide the dataset:</b></br>
In this, we have to divide the dataset into targets and features. So in accordance with the task, we have been asked to predict the genre. So Genre will be our target feature which will be divided from the main dataset and the rest are kept together.</br>
<b>3. Create the model:</b> </br>
We have used <b>Decision Tress Classifier</b> Algorithm for building the model.</br>
<b>4. Train the model:</b></br>
Divide the dataset into 2 parts training and testing parts for both Target and features.</br> 
Once the model is trained we can store the model using <b>joblib</b> function in order to avoid re-training the model again and again</br>
<b>5. Check for prediction and accuracy score:</b></br>
The created model perform well with an accuracy of 75%. and also predict the correct result for the random age given as input.</br>
<b>6. Visualization:</b></br>
Finally to view the entire working of the model we build a graphical representation depicting the working of our model using sklearn and matplotlib.</br>



Reference: Python Machine Learning Tutorial (Data Science), Programming with Mosh, https://www.youtube.com/watch?v=7eh4d6sabA0
