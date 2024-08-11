# Big Mart Sales Prediction
**Problem Description:** 
- Nowadays, shopping malls and Big Marts keep track of individual item sales data in order to forecast future client demand and adjust inventory management.  
- In a data warehouse, these data stores hold a significant amount of consumer information and particular item details.  
- By mining the data store from the data warehouse, more anomalies and common patterns can be discovered.  
- So, the aim is to build a solution that should able to predict the sales of the different stores of Hyper Market according to the provided dataset. 

**Justification for choosing the project:** 
In our project, we developed a prediction that helps the corporate to trace the sales of each product in marts of different branches. This helps the Mart to stock the product that has high sales number which in turn increases the overall profit for the organization, thus ending up in a win-win situation for both the corporate and customers. 

**Concept used:** 
**Linear Regression:** 
- Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task.**  
- Regression models a target prediction value based on independent variables.**  
- It is mostly used for **finding out the relationship between variables and** **forecasting.****  
- Different regression models differ based on – the kind of relationship between dependent and independent variables they are considering, and the number of independent variables getting used**.** 

**Random Forest Algorithm**:
- A Random Forest is a machine-learning technique that’s used to solve **regression and classification problems.** 
- A Random Forest Algorithm consists of many decision trees. 
- The Random Forest Algorithm establishes the outcome based on the predictions of the decision trees. It predicts by taking the average or mean of the output from various trees. 
- A random forest eradicates the limitations of a decision tree algorithm. It reduces the overfitting of datasets and increases precision. 

**Hyper Parameter Tuning:** 
- When creating a machine learning model, you'll be presented with design choices as to how to define your model architecture.  
- Often times, we don't immediately know what the optimal model architecture should be for a given model, and thus we'd like to be able to explore a range of possibilities.  
- In true machine learning fashion, we'll ideally ask the machine to perform this exploration and select the optimal model architecture automatically.  
- Parameters which define the model architecture are referred to as hyperparameters and thus this **process of searching for the ideal model** **architecture** is referred to as **hyperparameter tuning.** 

**Model**: 
- The dataset we have chosen contains features like Item Weight, Item fat content, Item visibility to the user, Item type, Item MRP, Outlet size, Outlet location type, Outlet Type and Item Outlet Sales. 
- It consists of sales record of each product at different outlets over a period of 10 years. 
- The shape of the dataset is (8523, 12). 
- The dataset has null values and duplicate values, which needs to be cleaned. 

**Installation Instructions**
Clone the repository:
```
git clone https://github.com/yourusername/Big-Mart-Sales-Prediction.git
cd Big-Mart-Sales-Prediction
```
Create a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Install the required packages:
```
pip install -r requirements.txt
```
**Usage:**
### Prepare the dataset:
Ensure your dataset is in the correct format and placed in the data/ directory.
### Run the preprocessing script:
```
python preprocess.py
```
### Train the model:
```
python train.py
```
### Make predictions:
```
python predict.py --input data/test.csv --output predictions.csv
```
### Results
The model’s performance can be evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).
Visualizations of the predictions vs actual sales can be generated to better understand the model’s accuracy.

## Contributing
Contributions are welcome! If you would like to contribute to the development of the Big Mart Sales Prediction Project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of the changes.
5. Please ensure that your code adheres to the project's coding standards and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or feedback, please reach out to me at prabhupugal01@gmail.com.
