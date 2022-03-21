<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">API Testing</h1>

# Functional Testing
## Creating Test Scripts <!-- {docsify-ignore} --> 
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.025.png">

After creating a **Test Suite** you will be displayed four ways to create an API

### Creating Scripts Manually
<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.030.png">
Click on **Add** to start creating a new API Test Manually

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.031.png">
For this, lets create a sample API Test fill out your boxes with:

**Name: Dog Facts**

**Description: Gets dog facts**

**Context path: api/v1/resources/dogs/all**

**Protocol: https**

**End Point: dog-facts-api.herokuapp.com/**

**Port Number:**

**Verbs: Get**

For more details on the API please visit the link **[https://github.com/DukeNgn/Dog-facts-API**](https://github.com/DukeNgn/Dog-facts-API)**

**Note**: 

- API type – select REST, SOAP or GraphQL
- Name – the name of your API script
- Description – a description of your script
- Context Path – the path to your specific API
- Protocol – http or https
- Endpoint – the main locator for your APIs
- Port Number – a port number. Defaults to 8080
- Verbs – the type of API call. GET, POST, PUT, DELETE or PATCH

### Importing Scripts
If you do not want to create your own API you can import a script through **two** different ways

- Through a website, for this example [**https://petstore.swagger.io/v2/swagger.json**](https://petstore.swagger.io/v2/swagger.json)

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.026.png">

- Through importing from your local machine

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.027.png">

**Note:** You can give the .JSON file any name, as long as the context inside has the correct information

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.028.png">

After you import either from a **file** or **URL** you will be shown the lists of APIs you can select from

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.029.png">

Once you have chosen your APIs they will be automatically added to the list with the other APIs created **manually** or **imported**