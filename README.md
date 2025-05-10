# Heart Disease Prediction using Logistic Regression  
This project uses machine learning to predict whether a person has heart disease based on several medical parameters. It employs a Logistic Regression model built with Scikit-learn and uses a heart disease dataset in CSV format.  
## Features  
- Load and preprocess heart disease dataset  
- Train/test split with stratification  
- Train a Logistic Regression model  
- Evaluate model performance using accuracy scores  
- Make predictions on custom input data  
## Dataset  
The dataset used is `heart.csv`, which contains the following features:  
- age  
- sex  
- cp (chest pain type)  
- trestbps (resting blood pressure)  
- chol (serum cholesterol)  
- fbs (fasting blood sugar)  
- restecg (resting electrocardiographic results)  
- thalach (maximum heart rate achieved)  
- exang (exercise-induced angina)  
- oldpeak (ST depression)  
- slope (slope of the peak exercise ST segment)  
- ca (number of major vessels)  
- thal (thalassemia)  
- target (1: disease, 0: no disease)  
## How to Run  
1. Make sure Python and the required libraries are installed:  
```bash  
pip install numpy pandas scikit-learn  
```  
2. Place the `heart.csv` file in the working directory.  
3. Run the script using Python:  
```bash  
python heart_disease_prediction.py  
```  
4. The script will output:  
- Training accuracy  
- Testing accuracy  
- Prediction result for a sample input  
## Example Output  
```  
Accuracy of training data :  0.8554216867469879  
Accuracy of test data :  0.8688524590163934  
[1]  
the person have a heart disease  
```  
## Code Overview  
- Load CSV using Pandas  
- Split features and labels  
- Stratified train-test split  
- Train Logistic Regression model  
- Evaluate model accuracy  
- Use custom input to predict outcome  
## Custom Prediction  
To test your own data, modify this section:  
```python  
data = (34, 0, 1, 118, 210, 0, 1, 192, 0, 0.7, 2, 0, 2)  
```  
This must match the number and order of features used in the dataset.  
## Technologies Used  
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

