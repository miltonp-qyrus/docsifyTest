<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">API Testing</h1>

# Functional Testing
## Other <!-- {docsify-ignore} --> 

### Assertions
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.035.png">
**Notes: Assertions allow you to validate HTTP responses in your API tests**

### Header
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.036.png">
Switching to the **Header & Params** tab you create assertions to certain things in your API, for example the **Body, Authorization, and API key calls.** This is what you will fill out for your API test to verifies its given values

### JSON Path
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.037.png">
If you want to add JSON Path assertions, you would need to click the **Assertions** tab then click **JSON Path Assertion**. You do need to know how to format the path, however we included a way to convert JSON data into the correct format

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.038.png">

On whatever page you are on click the **JSON Path Extractor** button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.039.png">

Now by filling up the JSON Body with a simple JSON data **Extract** and the response will format your data so you can easily input the data correctly in the JSON Assertion tab as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.040.png">

From what the extractor showed you fill out the JSON assertions just like the example above
### Body
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.041.png">
Go to the **Assertion** tab again and click on **Assertion on Body**, similar with the JSON Path Assertion you will verify the data to test

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.042.png">

This is an example of choosing the type of body and what kind of data you will use to verify the test
### Schema validation
What is it: **used to confirm the structure of your response**

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.043.png">

Choose **Schema Validation** when you want to make sure the response that is given from the test is correct

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.044.png">

Similar to the JSON Path Extractor, if you do not know the structure of a schema use our **JSON Schema Generator** 
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.045.png">

Create a simple JSON Body on the left side, then press generate and you will see the equivalent to a **Schema Response** you will then input it to the **Validation** box

**Note:** When you run your test doing this will make sure your expected **body** response will match with what you want to validate and if it passes your expectations were met

### Using Authorization
Clicking the **Authorization** tab, you are given the option of running API tests that require a certain authorization
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.046.png">


#### Basic Auth
is used when you need credentials to access certain data, for example, bank account, hotel reservations, food orders, etc. Doing so you will be able to manipulate the necessary data you need **specific** to the user

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.047.png">



#### OAuth 2.0
is used when you want to use an API but need an **API KEY** this is where you will go to input the necessary information to get access to the API

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.048.png">