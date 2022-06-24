![Intro_Image](https://user-images.githubusercontent.com/84449238/175462327-75fcfeaf-17a6-4371-84dc-9e689fb1f273.JPG)

# Black_Friday_Sales_Prediction-AnalyticsVidhya
A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.
Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

![Data_Image](https://user-images.githubusercontent.com/84449238/175461278-55254c1d-4cfe-4f7f-a6ba-806aebda2886.JPG)

Your model performance will be evaluated on the basis of your prediction of the purchase amount for the test data (test.csv), which contains similar data-points as train except for their purchase amount. Your submission needs to be in the format as shown in "SampleSubmission.csv".

We at our end, have the actual purchase amount for the test dataset, against which your predictions will be evaluated. Submissions are scored on the root mean squared error (RMSE). RMSE is very common and is a suitable general-purpose error metric. Compared to the Mean Absolute Error, RMSE punishes large errors:

![Img1](https://user-images.githubusercontent.com/84449238/175462014-53a2f14f-85ef-443a-831f-89ea8fa69248.JPG)

Where y hat is the predicted value and y is the original value.
