# Store Vender Forecast Model
Author: Lisa Broadhead

<strong>Data:</strong>
https://drive.google.com/drive/u/0/folders/1p5lPFn2pmZ0XtW_4oIjYB8PXxETe2Rg9

<strong>Full Document:</strong>
https://github.com/lisabroadhead/store-vender-forecast/blob/main/project_part_4.ipynb

## Business Problem
Help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.

## Goal 
Predict the size and type of outlets based on the given features to meet the business problem.

## Data Science Predictive Model and Analysis

fig 1: Store counts went down, revenue stayed the same, and more SuperMarket Type 1 are being built
<img src="https://github.com/lisabroadhead/store-vender-forecast/blob/main/stores_sales_2.png" />

fig 2: Revenue didn't go down because SuperMarket Type 1 was being built and they're bringing in the most revenue. Even though, based on product category they don't have the highest priced items. 
<img src="https://github.com/lisabroadhead/store-vender-forecast/blob/main/Screen%20Shot%202022-06-30%20at%2012.06.43%20PM.png" />

fig 3: Of the SuperMarket Type 1, medium-low locations are bringing in the most revenue.
<img src="https://github.com/lisabroadhead/store-vender-forecast/blob/main/store_type_size%20(1)%20(1).png" />

### Compilation Breakdown
1. Barplots were chosen because for their simplicity in relaying data quickly and efficiently 
2. One lineplot was chosen because the flow of reverent needed to be show and a lineplot explained that best 

### Summary
Businesses are driven by revenue and sales. First there was an exploration into what was bringing in the most revenue. Upon analysis of the data it became apparent that shopping categories overall revenue had less impact than on the store itself. Further analysis, showed that correlation between store size and type was leading to the stores overall revenue success. That is what these charts so heavily focus on store type and size to generate the final conclusion.  

### Limitations & Next Steps
Limitations to this model consist mainly in its simplicity and lack of data. More factors than just type and size could be affecting the success of the store. For example the size of the city, other store in the area, could adobe playin a part.

Based on the information that has been curated, the best next step is to test our theory on live data to give a better idea on how your predictions will play out in the future. 

## Machine Learning Models
<strong>Full Documentation</strong>
https://github.com/lisabroadhead/store-vender-forecast/blob/main/regression_models.ipynb

### Methods
fig 1: Overview of the regression models, visual explanation of how the data is working  and why one model was chosen over the others
<img src="https://github.com/lisabroadhead/store-vender-forecast/blob/main/regression.png" />

fig 2: Overview of our evaluation metrics. They follow our best tune models, with a higher training data and a lower test data
<img src="https://github.com/lisabroadhead/store-vender-forecast/blob/main/evaluations%20(1).png"/>

### Compilation Breakdown
1. Lineplot chosen because of its simplicity in relaying the flow between the max depth and accuracy 

### Results
Based on the success of the other models looked at, random forests were able to produce the best models. Even after tuning the best tuning accomplished was in the .6 range. When the models were evaluated random forests were able to hold a better training and test score. The test score is still at 50% accuracy. If more accuracy was required more data would need to be supplied.  

### Limitations & Next Steps
Even with extensive testing, our test and training data are both only able to rise so high. Because of this our model accuracy is still inthe .6 range. If a higher accuracy rate for both the training and test data sets were needed, more data would need to be acquired.


## For further information
For any additional questions, please contact email
Lisa Broadhead
lb.broadhead@gmail.com
