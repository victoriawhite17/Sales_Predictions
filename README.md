# Sales Predictions
## Using different models to best predict sales

Victoria White: 

### Business problem:

How do different features effect sales and using those features to predict sales


### Data:
I filled missing data with mean and most frequent, resulting in no missing data dropped. Using Linear Regression, I was able to build a model to predict sales with 56% accounted variance. 


## Results

#### How Establishment Year Effects Sales
![image](https://user-images.githubusercontent.com/106834973/186798533-534ccecf-0277-4f72-b30e-2d043f0d41a7.png)


Aside from the year 1998, sales seem to be relatively even across the board. Older stores might have loyal shoppers and newer stores could be slightly lower because they're still establishing themselves to the area.

#### How Item Types Effect Sales
![image](https://user-images.githubusercontent.com/106834973/186798758-5637bb7c-cb0a-4dfc-a13a-79c60fc4943e.png)

Exploring item types to see what sales the most at outlet locations. These stores seem to be a one stop shop

## Linear Regression Model

I fit my model with a scaler and linear regression pipeline. 

The RSME value for testing data was 1139 while the training data had a value of 1092. The R^2 value for testing data was 56% which matches the R^2 value for the training data as well. 

The testing and training data can predict sales with 56% variance accounted for. 

## Recommendations:

Using a different model such as RandomForest could produce a higher R^2 score. 


## Limitations & Next Steps

Learning more about parameters and adjusting parameters could raise the decision tree regressor's R^2 score and then a different model could be used to potentially better predict sales with more variance accounted for. 


### For further information


For any additional questions, please contact **victoria.white17@hotmail.com**
