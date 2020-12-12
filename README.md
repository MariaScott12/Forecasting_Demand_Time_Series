# Forecasting_Demand_Time_Series
Utilize historic corporate data to create time series forecast.
  
**Project Description:** 
Forecasting is essential across industries from staffing call centers  to launching a new drug therapy.  It’s also important vertically from S&OP to finite manufacturing scheduling.
ERP systems can tie a forecast through all of these levels providing one source of truth.
However as with so many things, the results will only be as good as the forecast accuracy.

**Objective:**
Create time series forecast to predict future demand based on historical product data.

**Methodology:**
The data was found at https://www.kaggle.com/felixzhao/productdemandforecasting

Like so many businesses, the challenge was not lack of volume of data, the set includes 1.3 million observations, but data quality.  There are only five attributes for each observation:  Product Category, Product Code, Order Demand, Warehouse, and Date.

After cleaning the data and checking for stationarity of the time series, I focused in on the two product categories that accounted for 88%  of demand, identified seasonal patterns in the data, identified SARIMA as the appropriate algorithm. 

**Results:**
Created forecast with 82% accuracy for 3-month projection, with MAE of 31% on the test set, and standard error of 240k on 691k weekly demand.
