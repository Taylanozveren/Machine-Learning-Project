# Machine-Learning-Project
IBM Data Science / The final project developed with explanations and comments

3. Download the dataset from [Australian Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/) or place the dataset file `weatherAUS.csv` in the `data/` folder.

## Steps to Run the Project

1. **Data Preprocessing**:
 - Clean the dataset by handling missing values and applying transformations like One Hot Encoding for categorical variables.
 - Drop the irrelevant columns like `Date`.
 - Split the data into training and test sets (80%/20%).

2. **Model Training**:
 - Train the following machine learning models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Trees
   - Support Vector Machines (SVM)
   - Linear Regression (experimental)
 
3. **Evaluation**:
 - Evaluate the models using metrics such as Accuracy, F1-Score, Jaccard Index, and LogLoss.
 - Compare the results and identify the best-performing model.

4. **Visualization**:
 - Plot the evaluation metrics to visually compare the model performances.

5. **Save and Share Results**:
 - Results can be saved to the `results/` folder for further analysis.

## Results

Based on the evaluation metrics, the following observations were made:
- **SVM** performed well in handling high-dimensional data.
- **Logistic Regression** provided interpretable results and high accuracy in binary classification.
- **KNN** performed well with localized instances but had limitations with larger datasets.

## Real-World Applications

This rain prediction model can be applied in various real-world scenarios, such as:
- **Weather Forecasting**: Assisting meteorological departments in predicting rainfall for agricultural planning and disaster management.
- **Risk Assessment**: Helping companies in sectors like insurance and agriculture assess weather-related risks.
- **Public Safety**: Supporting urban planners and emergency services in preparing for adverse weather conditions.

## Contributing

If you would like to contribute to this project, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
