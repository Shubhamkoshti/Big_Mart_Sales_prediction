
# Big Mart Sales Prediction

### Objective
Predict the sales of each product from a perticular outlet store by understanding the properties of product and outlet which play a key role in increasing sales. we will try to predict the sales by building a model.

### Data Set Information
Big Mart sales data contains 8523 rows and 12 feature for 1559 products across 10 stores in different cities in 2013 

### Attribute Information
- Item_Identifier: Unique product ID
- Item_Weight: Weight of product
- Item_Fat_Content: Whether the product is low fat or not
- Item_Visibility: The % of total display area of all products in a store allocated to the particular product
- Item_Type: The category to which the product belongs
- Item_MRP: Maximum Retail Price (list price) of the product
- Outlet_Identifier: Unique store ID
- Outlet_Establishment_Year: The year in which store was established
- Outlet_Size: The size of the store in terms of ground area covered
- Outlet_Location_Type: The type of city in which the store is located
- Outlet_Type: Whether the outlet is just a grocery store or some sort of supermarket
- Item_Outlet_Sales: Sales of the product in the particular store. This is the outcome variable to be predicted


### Library Used
Numpy  
Pandas  
Matplotlib
Seaborn  
Sklearn  
statsmodels  
xgboost

### Conclusion
I have used 3 models on this dataset but xgboost is giving me Lower RMSE and best score. By using this model we will predict the sales of sevral product from a perticular outlet store,






