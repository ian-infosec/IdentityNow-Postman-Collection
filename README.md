# IdentityNow-Postman-Collection
A collection of resources to assist with using the IdentityNow API endpoints with the Postman application

Importing a Postman Collection and Workspace
1. At the top, next to the new request button click "Import" 
![Image1](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image1.png)
2. Select the file "SailPoint IdentityNow.postman_collection.json". You should now see a collection titled SailPoint IdentityNow with 142 total requests broken down into several folders.
![Image2](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image2.png)
3. Importing the environment is not technically necessary but will make all the variables work. Start by clicking the gear in the top right corner.
![Image3](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image3.png)
4. Click the import button and select the file "IdentityNow Workspace.postman_environment.json"
![Image4](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image4.png)
![Image5](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image5.png)
5. To make things easier you can use the environment to handle authentication. A test script exists in the endpoint titled "Get Oauth Token" which will assign the resulting bearer token to the collections Authentication variable. This means that once you run the "Get OAuth Token" endpoint all your scripts will work. When you get a 401 (Unauthorized) just run the "Get OAuth Token" endpoint again. I'm working on making this easier.
*Note: you will need to get your own orgid, client_id, and client_secret from your IDN administrator.*
![Image6](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image6.png)
![Image7](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image7.png)
![Image8](https://github.com/ian-infosec/IdentityNow-Postman-Collection/blob/master/images/image8.png)
