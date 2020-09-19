# AdvertisementRegression
This work seeks to create a model that will predict the sales that a company will generate with respect to advertisement expenditure across multiple channels like radio, tv, and newspaper.The steps taken have been subdivided into three parts namely, Data understanding,  Data Exploration and finally Model Building.

### Data Understanding 
In order to gain more insight into the dataset and also to determine the relationship between the features and the label, we performed an exploratory data analysis.
The following insights were drawn from the dataset:
* The dataset is made up of 200 rows and 4 columns(TV, radio, newspaper and sales)
* all the columns are numeric
* The features are TV, radio, newspaper and the target column is sales.
* there are no missing values in the dataset.\
it was realized that the dataset has already been cleaned, meaning there will be no need in cleaning the dataset again.

### Data Exploration 
To fully understand the relationship between the target value(sales) and the features, we used visual exploration to achieve this goal.
We started by creating a scatter plot to show the relationship between sales and the other columns as shown below.

![reg1](https://user-images.githubusercontent.com/68768460/93653375-2d9a7100-fa08-11ea-84c8-9a9c3bf01ea8.png)

clearly , it can be observed from the scatter plot that TV has a very strong positive relationship with sales. This means that, the more the company advertises through the TV media, the company will generate higher sales.
However , sales and other advertisment mediums like radio and newspaper seems to have a very weak relationship from the scatterplot.\
To be really certain of these relationships , we plot the correlation matrix to help us determine these relationships.

![reg2](https://user-images.githubusercontent.com/68768460/93653879-5ae81e80-fa0a-11ea-934a-83f892a1ba1e.png)
The legend tells that the warmer colours show higher and positive correlation whiles the colder colours show low or negative correlation.   
it can be observed from the correlation matrix above that the correlation between sales and TV is 0.78 which indicates a very strong postive correlation between sales revenue and TV.\
Also, the correlation between sales and radio is 0.58 which indicates a mild postive correlation between sales and radio advertisement. This means that, an increse in radio advertisment will increase sales in small proportion.
Finally, the correlation between sales and newspaper is 0.23 which is a very weak positive correlation between sales and newspaper advertisment. 


