# Water Quality Prediction

## Introduction

Water quality prediction is essential for ensuring safe drinking water. This project utilizes machine learning to predict water potability based on key parameters such as pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.

## Exploratory Data Analysis (EDA)

EDA tasks focus on visualizing missing values, understanding the distribution of potability, exploring relationships between columns, calculating correlations, and creating histograms. These steps collectively provide a comprehensive understanding of the dataset.

## Results

The project employed various machine learning algorithms for classification, including Logistic Regression, Decision Tree Classifier, Random Forest Classifier, K-Nearest Neighbors (KNN), Support Vector Classifier (SVM), Naive Bayes, and XGBoost. SVM stood out for its robust performance, demonstrating superior accuracy and a balanced precision-recall trade-off compared to other models.

.

## How to Run the Flask Application

1.**Clone the Repository:**
```python
git clone https://github.com/YourUsername/Water-Quality-Prediction.git
```
2.**Navigate to Project Directory:**
```python
cd Water-Quality-Prediction
```
3.**Install Dependencies:**
```python
pip install -r requirements.txt
```
4. **Run the Flask App:**
Execute the following command to run the Flask application:
```python
python app.py
```

This will start the Flask development server.

5. **Access the Application:**
Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/). You should see the water quality prediction form.

6. **Input Water Quality Parameters:**
Fill in the values for pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity.

7. **Submit the Form:**
Click the "Predict Potability" button to submit the form. The application will process your input and display the prediction results.

8. **Explore Results:**
Review the prediction for water potability (Potable or Not Potable) based on the provided water quality parameters.

That's it! You have successfully run the Flask application and used the machine learning model to predict water potability.


## Conclusion

The Water Quality Prediction project contributes to the intersection of data science and public health by leveraging machine learning techniques to ensure safe drinking water. The results highlight the potential of SVM for accurate water quality classification.



