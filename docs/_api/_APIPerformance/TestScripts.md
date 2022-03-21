<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">API Testing</h1>

# Performance Testing
Performance Testing includes increasing the load and see how the system behaves under higher load. Here, you can monitor response times and also view the status code of each request.

## Importing Scripts from Swagger
Swagger is a suite of API developer tools used to automate API processes across the entire API lifecycle.

In order to import a script from swagger, the user must: 

1. Copy and paste a swagger URL into the ‘Import Swagger URL’ form
1. Click ‘Get API’s’

For this example, we will be using the Pet Store API. The link can be found here: 

- <https://petstore.swagger.io/v2/swagger.json>

**Note:** Make sure there is no white space before or after the Swagger URL when pasting it into the input form. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.053.png">

After clicking on ‘Get APIs’, a list of APIs will appear with checkboxes next to their names. The user then: 

1. ` `Selects the checkboxes for the API’s they would like the generate. 
1. Click ‘Generate Test Script’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.009.png">

## Uploading Swagger JSON
If the user has a Swagger JSON file, click on ‘Browse’. This will bring the user to their File Explorer. From here, they can navigate through their File Explorer and upload their Swagger JSON file.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.010.png">

## Create Manual API Test
In order to create tests manually, the user needs to click on ‘Add’ under ‘Create manual API Test’.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.054.png">

After clicking on ‘Add’, the user will be asked to fill out a form to create their API. The form will consist of: 

1. API type – select REST, SOAP or GraphQL 
1. Name – the name of your API script 
1. Description – a description of your script 
1. Context Path – the path to your specific API 
1. Protocol – http or https 
1. Endpoint – the main locator for your APIs 
1. Port Number – a port number.  Defaults to 8080 
1. Verbs – the type of API call.  GET, POST, PUT, DELETE or PATCH

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.055.png">

After the form is completed, click on the green ‘Save’ icon on the top right of the screen.

**Note:** Options to add Authentications, Head & Params, and Body can be found under Functional API documentation.

## Running API Tests
Running a test can be done in three ways.

1. The first option allows the user to run more than one test. The user will select each test they would like to run by selecting the checkbox associated with that test. Then, the user will click the run icon on the top right of the page.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.056.png">

1. Option two involves going under the ‘Action’ header, and then selecting the run icon

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.057.png">

1. Option three involves navigating into a specific test by clicking on ‘Go to Test’. Then on the top right corner of 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.058.png">

After running a test, a pop up will appear that will prompt the user to simulate a number of threads and add a threshold for a response time. Enter in these values and then click ‘Run’.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.012.png">

## Viewing Reports
Reports can be viewed by clicking on the ‘Reports’ button on the top right of the page.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.059.png">

After clicking on reports, the user will see a list of all previous and actively running rests. 

From here the user can click on ‘View Details’ to view the report

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.060.png">

After clicking on the report, the user will be able to view:

1. Response Time Results
1. Status Code Results
   - Status code 200 = Passed Test