# Project-4
We selected data on airline flight delays and attempted to create a model that would accurately predict if a flight would be delayed days in advance.  This model could be used by freqent travelers who have tight connections to determine if they want to risk taking this flight if theres a good chance their originatign flight will be delayed and they could miss their connection.

![image](https://user-images.githubusercontent.com/94984006/171274246-ada38e40-a78b-490c-bc82-d8fdc962a02b.png)

We cleaned up the data and eliminated non-valuable rows and reducted the reduced the number of rows of data by selecting flight originating from nine cities.

![image](https://user-images.githubusercontent.com/94984006/171274586-8326b473-0003-4d68-b4f4-f8f5b14f6e27.png)

![image](https://user-images.githubusercontent.com/94984006/171274739-06654762-b090-4229-b506-4c1cb96b64e3.png)

We tested muliple Supervised Learning Models on airline flight delay information and landed on the following three models.  From the results, it appeard that the Neural Network model would perform the best with a rating of .97 and a loss rate of only .05.   

![image](https://user-images.githubusercontent.com/94984006/171273301-3fe6bf5c-dcae-410c-83c6-301b6c6bbcc5.png)

To see the models in action, we saved them and used random test cases for 20 Delayed Flight and 20 On Time flights and calculated the Accuracy, Sensitivity, Precision and F1 Scores for each model.


![image](https://user-images.githubusercontent.com/94984006/171275111-989278fb-1804-4c7a-9541-a4ea9bd9cded.png)

We then further analyzed the mode and determined the the ADA Boost classifier model was the best model, as it has high precision and a significantly low liklihood of over-predicting an on-time flight would be delayed than the Neural Netowrk Model. 

Notably the ADA Boost Classifier model also had higher Accuracy, Sensitivity and F1 scores than the Neural Network model, hinting that it is likely a better performing model overall

![image](https://user-images.githubusercontent.com/94984006/171275909-f887e116-d748-4962-954b-29d585c69ea3.png)

Just because a model has a seemingly better testing/training or accuracy score it doesn't guarantee it is the best model.  You need to test the model, and calculate and analyze the Accuracy, Sensititivty, Percision and F1 score (ASPF) of the model to determine which is the best model to meet your business need.

We've attached a diagram we developed to help understand how to calculate the ASPF for the model in hopes that it may help others understand these calculations and corresponding results better.

![image](https://user-images.githubusercontent.com/94984006/171276785-3b8f327d-6391-4dfc-af06-782b9771a4d2.png)

