dataset link combined_data_1.txt
https://drive.google.com/file/d/1Qz_AIP5eyceZcUfoD4Ht9Uc7f9WPv0xY/view?usp=drivesdk

# Advanced-recommendation-system
Advanced recommendation system
# Introduction to Recommendation systems

In this modern world we are overloaded with data and this data provides us the useful information. But it's not possible for the user to extract the information which interest them from these data. In order to help the user to find out information about the product , recommedation systems where developed.

Recommeder system creates a similarity between the user and items and exploits the similarity between user/item to make recommendations.


What recommeder system can solve ?

1. It can help the user to find the right product.
2. It can increase the user engagement. For example, there's 40% more click on the google news due to recommendation.
3. It helps the item providers to deliver the items to the right user.In Amazon , 35 % products get sold due to recommendation.
4. It helps to make the contents more personalized.In Netflix most of the rented movies are from recommendations.

## Attribute Information:

● userId : Every user identified with a unique id (First Column)

● productId : Every product identified with a unique id(Second Column)

● Rating : Rating of the corresponding product by the corresponding user(Third Column)

● timestamp : Time of the rating ( Fourth Column)




# Steps and tasks:

#### 1. Read and explore the given dataset.  (Rename column/add headers, plot histograms, find data characteristics)
#### 2. Take a subset of the dataset to make it less sparse/ denser. ( For example, keep the users only who has given 50 or more number of ratings )  
#### 3. Split the data randomly into train and test dataset. ( For example, split it in 70/30 ratio)
#### 4. Build Popularity Recommender model.  
#### 5. Build Collaborative Filtering model.
#### 6. Evaluate both the models. ( Once the model is trained on the training data, it can be used to compute the error (RMSE) on predictions made on the test data.  
#### 7. Get top - K ( K = 5) recommendations. Since our goal is to recommend new products for each user based on his/her habits, we will recommend 5 new products.  
#### 8. Summarise your insights.

