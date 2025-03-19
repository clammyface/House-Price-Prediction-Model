📌 Project Overview
✅ Loaded and explored the California Housing dataset
✅ Implemented an XGBoost regression model for price prediction
✅ Evaluated model performance using RMSE and R² score
✅ Visualized correlation between features to understand price drivers

📂 Dataset
The project uses the California Housing dataset available in sklearn.datasets.
The dataset includes attributes such as:
MedInc (Median income)
HouseAge (Average house age)
AveRooms (Average number of rooms)
Population, AveOccup, etc.
🔄 Data Processing
✅ Converted the dataset into a Pandas DataFrame
✅ Added target column (SalePrice) to the dataset
✅ Checked for missing values and handled them accordingly

📊 Model Training
Used the XGBoost Regressor for training.
Split the data into training and test sets.
Optimized model parameters for better performance.
📈 Model Evaluation
Evaluated using Root Mean Squared Error (RMSE) and R² score.
Visualized predictions vs. actual values.
📌 Results & Insights
The model predicts house prices with high accuracy.
Median income and house age were found to be the most significant factors.
