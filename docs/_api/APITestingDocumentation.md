` `PAGE   \\* MERGEFORMAT 4

**API Testing Documentation**
# Contents
` `TOC \o "1-3" \h \z \u [**Get Started**	 PAGEREF _Toc74215911 \h 3](#_Toc74215911)

[Swagger is a suite of API developer tools used to automate API processes across the entire API lifecycle.	 PAGEREF _Toc74215912 \h 6](#_Toc74215912)

[**Uploading Swagger JSON**	 PAGEREF _Toc74215913 \h 7](#_Toc74215913)

[**Creating New Tests Suites**	 PAGEREF _Toc74215914 \h 8](#_Toc74215914)

[**Importing Test Scripts**	 PAGEREF _Toc74215915 \h 9](#_Toc74215915)

[**Importing from Existing APIs**	 PAGEREF _Toc74215916 \h 9](#_Toc74215916)

[**Connecting Tests together with Flow**	 PAGEREF _Toc74215917 \h 10](#_Toc74215917)

[**Project Setup**	 PAGEREF _Toc74215918 \h 11](#_Toc74215918)

[**Creating a project**	 PAGEREF _Toc74215919 \h 11](#_Toc74215919)

[**Creating test Suites**	 PAGEREF _Toc74215920 \h 12](#_Toc74215920)

[**Adding Certificates**	 PAGEREF _Toc74215921 \h 13](#_Toc74215921)

[**Global Variables**	 PAGEREF _Toc74215922 \h 14](#_Toc74215922)

[**API Functional Testing**	 PAGEREF _Toc74215923 \h 14](#_Toc74215923)

[**Creating test scripts**	 PAGEREF _Toc74215924 \h 14](#_Toc74215924)

[**Importing scripts**	 PAGEREF _Toc74215925 \h 14](#_Toc74215925)

[**Creating scripts manually**	 PAGEREF _Toc74215926 \h 16](#_Toc74215926)

[**Execution and Viewing Reports**	 PAGEREF _Toc74215927 \h 24](#_Toc74215927)

[**API Performance**	 PAGEREF _Toc74215928 \h 26](#_Toc74215928)

[**Create a Project**	 PAGEREF _Toc74215929 \h 26](#_Toc74215929)

[**Create a Test Suite**	 PAGEREF _Toc74215930 \h 26](#_Toc74215930)

[**Creating Test Scripts**	 PAGEREF _Toc74215931 \h 27](#_Toc74215931)

[**Importing Scripts from Swagger**	 PAGEREF _Toc74215932 \h 27](#_Toc74215932)

[**Uploading Swagger JSON**	 PAGEREF _Toc74215933 \h 28](#_Toc74215933)

[**Create Manual API Test**	 PAGEREF _Toc74215934 \h 29](#_Toc74215934)

[**Running API Tests**	 PAGEREF _Toc74215935 \h 30](#_Toc74215935)

[**Viewing Reports**	 PAGEREF _Toc74215936 \h 31](#_Toc74215936)

[**API Process Testing**	 PAGEREF _Toc74215937 \h 32](#_Toc74215937)

[**Creating New Tests Suites**	 PAGEREF _Toc74215938 \h 32](#_Toc74215938)

[**Importing Test Scripts**	 PAGEREF _Toc74215939 \h 32](#_Toc74215939)

[Importing from Existing APIs	 PAGEREF _Toc74215940 \h 33](#_Toc74215940)

[Import Swagger JSON	 PAGEREF _Toc74215941 \h 33](#_Toc74215941)

[**Managing Scripts**	 PAGEREF _Toc74215942 \h 34](#_Toc74215942)

[**Creating Flows**	 PAGEREF _Toc74215943 \h 35](#_Toc74215943)

[**Executing and Viewing Reports**	 PAGEREF _Toc74215944 \h 36](#_Toc74215944)

[**Other**	 PAGEREF _Toc74215945 \h 37](#_Toc74215945)

[**SOAP and GraphQL**	 PAGEREF _Toc74215946 \h 37](#_Toc74215946)

[**Using Prerequisite APIs and Dynamic Variables**	 PAGEREF _Toc74215947 \h 38](#_Toc74215947)

[**Prerequisites**	 PAGEREF _Toc74215948 \h 38](#_Toc74215948)

[**Setup**	 PAGEREF _Toc74215949 \h 38](#_Toc74215949)

[**Prerequisite API Test Creation**	 PAGEREF _Toc74215950 \h 39](#_Toc74215950)

[**Test Creation & Execution**	 PAGEREF _Toc74215951 \h 41](#_Toc74215951)

[**Parameterizing Tests**	 PAGEREF _Toc74215952 \h 43](#_Toc74215952)

[**Prerequisites**	 PAGEREF _Toc74215953 \h 43](#_Toc74215953)

[**Making API Parameterized and Marking Fields**	 PAGEREF _Toc74215954 \h 44](#_Toc74215954)

[**Downloading & Uploading the Template**	 PAGEREF _Toc74215955 \h 45](#_Toc74215955)


#

# **Get Started**
Introduction

For this service, you have the ability to create, import, and check API tests without having to install software onto your local machine. With what is provided in the API Service the main purpose is to test API swiftly and keep all test results in a convenient location. The service has any API testing software's need to test out the different APIs you create.

First Steps

**Create your project:**

1. Click on API testing
1. Click on ‘New Project’
1. Enter a project name
1. Enter a project description 
1. Checkmark any teammates that will be working on the project
1. Click ‘Create Project’ 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.001.png)

**Create your suite**

1. Click on ‘Create Test Suite’
1. Enter a Test Suite Name
1. Enter a Module Name 
1. Click on ‘Create Test Suite’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.002.png)

**Create an API Manually**

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.003.png)

Fill out your boxes with:

**Name: Dog Facts**

**Description: Gets dog facts**

**Context path: api/v1/resources/dogs/all**

**Protocol: https**

**End Point: dog-facts-api.herokuapp.com/**

**Port Number:**

**Verbs: Get**

**Execution** 

1. Hit save and hit the play button to continue
1. Give the **Test** a few seconds to initiate and run, pressing the **refresh button** afterwards it will update the test status whether it **passed** or **failed**
1. You can view in detail of the test to see what kind of information you grabbed since we did a **GET** API

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.004.png)

**Reports**

Once you are satisfied with your tests results you can see all of your tests in the reports page, found by pressing the **Reports** button on the top left corner

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.005.png)

Here you are able to see all of the different charts:

- The **Pass/Fail Ratio** Graph show you how many of your tests have passed versus how many have failed
- The **Run Frequency** Graph tells you how many times you've run each test script.
- The **Execution Time** Graph is a line graph that describes the time it took for each test to run.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.006.png)

**Switching to Performance Test**

**Note: Switch to Performance Testing**

Navigate back to a project click the ‘Performance Testing’ tab located on the top left of the page. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.007.png)

**Importing an API**
### Swagger is a suite of API developer tools used to automate API processes across the entire API lifecycle.
In order to import a script from swagger, the user must: 

1. Copy and paste a swagger URL into the ‘Import Swagger URL’ form
1. Click ‘Get API’s’

For this example, we will be using the Pet Store API. The link can be found here: 

- <https://petstore.swagger.io/v2/swagger.json>

**Note:** Make sure there is no white space before or after the Swagger URL when pasting it into the input form. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.008.png)

After clicking on ‘Get APIs’, a list of APIs will appear with checkboxes next to their names. The user then: 

1. ` `Selects the checkboxes for the API’s they would like the generate. 
1. Click ‘Generate Test Script’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.009.png)
### **Uploading Swagger JSON**
If the user has a Swagger JSON file, click on ‘Browse’. This will bring the user to their File Explorer. From here, they can navigate through their File Explorer and upload their Swagger JSON file.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.010.png)

**Running API Performance Test**

1. going under the ‘Action’ header, and then selecting the run icon

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.011.png)

1. After running a test, a pop up will appear that will prompt the user to simulate a number of threads and add a threshold for a response time. Enter in these values and then click ‘Run’.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.012.png)

**Import to API Process**

Navigate to API Process, click on the ‘API Process’ tab on the top left of the screen.  

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.013.png)
### **Creating New Tests Suites**
After selecting ‘API Process’, click the ‘+’ icon on the top right of the screen to create a new Test Suite

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.014.png)

After clicking the icon, the user will fill out a form that will require to enter a test suite name and a module name.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.015.png)
### **Importing Test Scripts**
When importing APIs, there are three options available.

1. Importing from Existing APIs
1. Import Swagger JSON
1. Import Postman Collection

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.016.png)
### **Importing from Existing APIs**
After selecting ‘Importing from Existing APIs’, a list of the user’s Test Suites will appear. Click on the desired Test Suite.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.017.png)

After choosing a desired Test Suite, a list of all the API calls that are associated with that Test Suite will appear. Click the check box associated with the API call and then click the import button.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.018.png)
### **Connecting Tests together with Flow**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.019.png)

After clicking on ‘Create Flow’, the user will be able to create connections for their APIs. This can be done by clicking on the ‘+’ icon on the left panel that’s associated with the API they want to add. 

After adding at least two APIs, a user can create a connection by clicking on the ‘Add Connection’ button on the top left of the page, then dragging an arrow from one API to another.

After creating a connection, click on the ‘Save’ icon on the top right of the page. Then the user will click on the ‘Next Page’ icon directly to the left of the ‘Save’ icon.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.020.png)

When the user clicks on ‘Next Page’ they will be able to see ‘Connection 1’. From here, the user will enter the JSON path, a parameter and a key name. 

The user will then click on the ‘Save’ icon and then run the test.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.018.png)

Reference the ‘Report’ section to view the results of your test.

# **Project Setup**
## **Creating a project**
1. Click on API testing
1. Click on ‘New Project’
1. Enter a project name
1. Enter a project description 
1. Checkmark any teammates that will be working on the project
1. Click ‘Create Project’ 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.001.png)
## **Creating test Suites**
1. Click on ‘Create Test Suite’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.021.png)

1. Enter a Test Suite Name
1. Enter a Module Name 
1. Click on ‘Create Test Suite’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.002.png)

## **Adding Certificates**
1. Click on ‘Certificates’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.022.png)

1. Click on ‘Add Certificate’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.023.png)

1. Choose the PFX file
1. Enter a ‘Domain Name’
1. OPTIONAL: Enter a ‘Port Number’
1. Enter the ‘Password’
1. Click on ‘Add Certificate’ 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.024.png)
## **Global Variables**



# **API Functional Testing**
## **Creating test scripts**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.025.png)After creating a **Test Suite** you will be displayed four ways to create an API
### **Importing scripts**
###
If you do not want to create your own API you can import a script through **two** different ways

- Through a website, for this example [**https://petstore.swagger.io/v2/swagger.json**](https://petstore.swagger.io/v2/swagger.json)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.026.png)

- Through importing from your local machine

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.027.png)

**Note:** You can give the .JSON file any name, as long as the context inside has the correct information

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.028.png)

After you import either from a **file** or **URL** you will be shown the lists of APIs you can select from

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.029.png)

Once you have chosen your APIs they will be automatically added to the list with the other APIs created **manually** or **imported**
### **Creating scripts manually**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.030.png)Click on **Add** to start creating a new API Test Manually

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.031.png)For this, lets create a sample API Test fill out your boxes with:

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

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.032.png)

Now let’s **Test** our API to see if it works, on the **top right** corner save and run the API, you will be **navigated** straight to the report page

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.033.png)

Give the **Test** a few seconds to initiate and run, pressing the **refresh button** afterwards it will update the test status whether it **passed** or **failed**

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.004.png)

You can view in detail of the test to see what kind of information you grabbed since we did a **GET** API

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.034.png)

As you can see in the **Response Body** you received all dog facts

So, the test was a success!!! Let’s take a look at the other features for more customization
#### **Assertions**
#### ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.035.png)
**Notes: Assertions allow you to validate HTTP responses in your API tests**
##### Header
##### ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.036.png)
Switching to the **Header & Params** tab you create assertions to certain things in your API, for example the **Body, Authorization, and API key calls.** This is what you will fill out for your API test to verifies its given values

##### JSON Path
##### ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.037.png)
If you want to add JSON Path assertions, you would need to click the **Assertions** tab then click **JSON Path Assertion**. You do need to know how to format the path, however we included a way to convert JSON data into the correct format

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.038.png)

On whatever page you are on click the **JSON Path Extractor** button

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.039.png)

Now by filling up the JSON Body with a simple JSON data **Extract** and the response will format your data so you can easily input the data correctly in the JSON Assertion tab as shown below

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.040.png)

From what the extractor showed you fill out the JSON assertions just like the example above
##### Body
##### ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.041.png)
Go to the **Assertion** tab again and click on **Assertion on Body**, similar with the JSON Path Assertion you will verify the data to test

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.042.png)

This is an example of choosing the type of body and what kind of data you will use to verify the test
##### **Schema validation**
What is it: **used to confirm the structure of your response**

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.043.png)

Choose **Schema Validation** when you want to make sure the response that is given from the test is correct

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.044.png)

Similar to the JSON Path Extractor, if you do not know the structure of a schema use our **JSON Schema Generator** 
#### ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.045.png)
Create a simple JSON Body on the left side, then press generate and you will see the equivalent to a **Schema Response** you will then input it to the **Validation** box

**Note:** When you run your test doing this will make sure your expected **body** response will match with what you want to validate and if it passes your expectations were met
#### **Using Authorization**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.046.png)

Clicking the **Authorization** tab, you are given the option of running API tests that require a certain authorization

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.047.png)

**Basic Auth** is used when you need credentials to access certain data, for example, bank account, hotel reservations, food orders, etc. Doing so you will be able to manipulate the necessary data you need **specific** to the user

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.048.png)

**OAuth 2.0** is used when you want to use an API but need an **API KEY** this is where you will go to input the necessary information to get access to the API
## **Execution and Viewing Reports**
With all explanations finished let’s run the tests and view your overall reports from all the APIs you created/tested ![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.043.png)

Go back to the list of APIs you created and **mark** them then on the **top right corner** you can run all chosen APIs simultaneously

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.049.png)

You will be navigated to the test results page and all chosen API’s will be **running** its test

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.050.png)

After a few seconds you will see its status showing **pass** or **fail,** you may click on **View Details,** like last time, to see your responses![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.005.png)

Once you are satisfied with your tests results you can see all of your tests in the reports page, found by pressing the **Reports** button on the top left corner![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.006.png)

Here you are able to see all of the different charts:

- The **Pass/Fail Ratio** Graph show you how many of your tests have passed versus how many have failed
- The **Run Frequency** Graph tells you how many times you've run each test script.
- The **Execution Time** Graph is a line graph that describes the time it took for each test to run.

With that done let’s check out **API Performance**
# **API Performance**
Performance Testing includes increasing the load and see how the system behaves under higher load. Here, you can monitor response times and also view the status code of each request.
## **Create a Project**
1. Click on ‘API Testing’
1. Click on ‘New Project’
1. Enter a project name
1. Enter a project description 
1. Checkmark any teammates that will be working on the project
1. Click ‘Create Project’ 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.051.png)

## **Create a Test Suite**
A Test Suite is an area for a user to store their collection of test cases.

However, before creating a test suite, the user needs to navigate into the ‘Performance Testing’ section. This can be done by navigating into a project and clicking the ‘Performance Testing’ tab located on the top left of the page. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.007.png)

From here, the user is going to click the ‘Create New Suite’ button. 

After clicking on the test, a form will appear that prompts the user to:

1. Enter a test suite name
1. Enter a module name
1. Click ‘Create Test Suite’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.052.png)

## **Creating Test Scripts**

### **Importing Scripts from Swagger**
Swagger is a suite of API developer tools used to automate API processes across the entire API lifecycle.

In order to import a script from swagger, the user must: 

1. Copy and paste a swagger URL into the ‘Import Swagger URL’ form
1. Click ‘Get API’s’

For this example, we will be using the Pet Store API. The link can be found here: 

- <https://petstore.swagger.io/v2/swagger.json>

**Note:** Make sure there is no white space before or after the Swagger URL when pasting it into the input form. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.053.png)

After clicking on ‘Get APIs’, a list of APIs will appear with checkboxes next to their names. The user then: 

1. ` `Selects the checkboxes for the API’s they would like the generate. 
1. Click ‘Generate Test Script’

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.009.png)
### **Uploading Swagger JSON**
If the user has a Swagger JSON file, click on ‘Browse’. This will bring the user to their File Explorer. From here, they can navigate through their File Explorer and upload their Swagger JSON file.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.010.png)

### **Create Manual API Test**
In order to create tests manually, the user needs to click on ‘Add’ under ‘Create manual API Test’.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.054.png)

After clicking on ‘Add’, the user will be asked to fill out a form to create their API. The form will consist of: 

1. API type – select REST, SOAP or GraphQL 
1. Name – the name of your API script 
1. Description – a description of your script 
1. Context Path – the path to your specific API 
1. Protocol – http or https 
1. Endpoint – the main locator for your APIs 
1. Port Number – a port number.  Defaults to 8080 
1. Verbs – the type of API call.  GET, POST, PUT, DELETE or PATCH

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.055.png)

After the form is completed, click on the green ‘Save’ icon on the top right of the screen.

**Note:** Options to add Authentications, Head & Params, and Body can be found under Functional API documentation.
### **Running API Tests**
Running a test can be done in three ways.

1. The first option allows the user to run more than one test. The user will select each test they would like to run by selecting the checkbox associated with that test. Then, the user will click the run icon on the top right of the page.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.056.png)

1. Option two involves going under the ‘Action’ header, and then selecting the run icon

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.057.png)

1. Option three involves navigating into a specific test by clicking on ‘Go to Test’. Then on the top right corner of 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.058.png)

After running a test, a pop up will appear that will prompt the user to simulate a number of threads and add a threshold for a response time. Enter in these values and then click ‘Run’.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.012.png)
### **Viewing Reports**
Reports can be viewed by clicking on the ‘Reports’ button on the top right of the page.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.059.png)

After clicking on reports, the user will see a list of all previous and actively running rests. 

From here the user can click on ‘View Details’ to view the report

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.060.png)

After clicking on the report, the user will be able to view:

1. Response Time Results
1. Status Code Results
   1. Status code 200 = Passed Test


# **API Process Testing**
For a user to navigate to API Process, the user must click on the ‘API Process’ tab on the top left of the screen. From here they will be brought to a page where they can ‘Import APIs’, ‘Manage APIs’, ‘Create Flows’, and view ‘Report’.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.061.png)
### **Creating New Tests Suites**
After selecting ‘API Process’, click the ‘+’ icon on the top right of the screen to create a new Test Suite

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.014.png)

After clicking the icon, the user will fill out a form that will require to enter a test suite name and a module name.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.015.png)
### **Importing Test Scripts**
When importing APIs, there are three options available.

1. Importing from Existing APIs
1. Import Swagger JSON
1. Import Postman Collection

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.016.png)
### Importing from Existing APIs
After selecting ‘Importing from Existing APIs’, a list of the user’s Test Suites will appear. Click on the desired Test Suite.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.017.png)

After choosing a desired Test Suite, a list of all the API calls that are associated with that Test Suite will appear. Click the check box associated with the API call and then click the import button.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.018.png)
### Import Swagger JSON
After selecting ‘Import Swagger JSON’, two options of importing and API via Swagger will appear. 

The first option will be pasting in a swagger URL. The second option will be uploading a Swagger JSON file. For more information on this, please reference the ‘Creating Test Script’ section under API Performance.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.062.png)

### Import Postman Collection

After selecting ‘Importing Postman Collection’, two options of importing and API will appear. 

The first option will be pasting a public link from Postman. After the file has been pasted, click ‘Get APIs’ and this will generate your API.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.063.png)

The second option will be uploading a JSON File. This can be done by clicking on ‘Browse’. After clicking on ‘Browser’, this will bring you to your File Explorer. From here, you can upload your file.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.064.png)

### **Managing Scripts**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.065.png)

After selecting ‘Managing Scripts’, the user will be brought to a page that displays a list of all their imported test scripts. On this page, the user will be able to edit and delete all of their imported APIs. Furthermore, on the right side of the screen is located the imports information table which shows how many, alongside the method of imported APIs. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.066.png)
### **Creating Flows**
![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.019.png)

After clicking on ‘Create Flow’, the user will be able to create connections for their APIs. This can be done by clicking on the ‘+’ icon on the left panel that’s associated with the API they want to add. 

After adding at least two APIs, a user can create a connection by clicking on the ‘Add Connection’ button on the top left of the page, then dragging an arrow from one API to another.

After creating a connection, click on the ‘Save’ icon on the top right of the page. Then the user will click on the ‘Next Page’ icon directly to the left of the ‘Save’ icon.

x![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.020.png)

When the user clicks on ‘Next Page’ they will be able to see ‘Connection 1’. From here, the user will enter the JSON path, a parameter and a key name. 

The user will then click on the ‘Save’ icon and then run the test.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.018.png)

Reference the ‘Report’ section to view the results of your test.
### **Executing and Viewing Reports**
After running a test, click on the ‘Report’ button. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.067.png)

The report page will allow users to view:

1. Executed Time Trends
1. Pass/Fail charts
1. Run Frequency charts
1. Test Reports

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.068.png)

In the ‘Test Reports’ section, the user will be able to view details of each test previously ran and then the user can click on ‘View Details’ to view the Flow Summary.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.069.png)

While on the ‘Flow Summary’ page, the user can click on ‘View’ and look at each API Test Results. 

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.070.png)
# **Other**
## **SOAP and GraphQL**
Qyrus allows for usage of multiple different types of standards-based web services access protocols. Currently, there is support for REST, SOAP, and GraphQL. To select a standard, use the radio buttons that can be found at the top of the “Info” tab window. 

Note: REST will automatically be selected as default.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.071.png)
## **Using Prerequisite APIs and Dynamic Variables**
Users can set up prerequisite APIs to run automatically before an API test execution. At the same time, the user can also grab data from the prerequisite call and save them to variables to be used in other API tests.
### **Prerequisites**
- High level knowledge in API testing and test building
- Knowledge in building assets in Service Virtualization
### **Setup**
The first thing to do is set up two APIs in the Service Virtualization service.
#### *Login API*
This Login API will simulate a user signing in and then receiving some sort of key back for authentication. Set up the Login API exactly as shown in the below screenshot and save.

Note: Make sure to click the “Online” switch in order to make the API go live. Afterwards, take note of the Url given (ex: http://testinfra.quinnox-int.info:8085/<context>).

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.072.png)

**Request:** { "email": "example@ex.com", "pwd": "abc123" }

**Response:** { "someKey": "aBcDeFg123" }
#### *Example API*
Now, in a very similar way, make an example API and fill it out like the below screenshot and save. One thing to note is that in this API the method is GET and there is a header called “auth” using the “someKey” value from the Login API response.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.073.png)

**Response:** { “response”: “Hello” }

**Header:** auth : aBcDeFg123
### **Prerequisite API Test Creation**
After navigating into the API Testing service, click the “Variables” button in the upper right-hand corner.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.074.png)

Navigate into the “Prerequisite API” tab and click the “Add API” button.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.075.png)

The next screen given should be familiar. Enter in the information as seen in the screenshots below and make sure to click save.

(THE BODY WILL BE THE REQUEST FROM THE LOGIN API IN SERVICE VIRTUALIZTION)

Note: In the “Data Handers” tab the user is able to not only pull from a JsonPath but also XPath, Headers, and allow for some JavaScript usage.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.076.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.077.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.078.png)

Note: Users can test run their Prerequisite APIs by clicking the “Run” button and then navigating back and clicking the reports button on the Prerequisite API list as shown below.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.079.png)

Clicking the “Dynamic Variables” tab will show the new “auth” variable created in the login prerequisite.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.080.png)
### **Test Creation & Execution**
Click the “Go Back” button in the upper right-hand corner of the screen to navigate back to API testing. Create a new APi test and fill it out as shown in the screenshots below and click save.

Note: In the “Headers & Params” tab the dynamic variable is used in the header section and is surrounded by pound signs (##) in order to active usage.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.081.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.082.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.083.png)

Finally, run the API test and view the report. It will look like the screenshot below. Clicking the “Prerequisite Results” tab will show the report for the Prerequisite API.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.084.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.085.png)
## **Parameterizing Tests**
Qyrus allows for certain fields and inputs to be parameterized. This allows the user a more dynamic range of test usage, allowing for one test to cover many different test cases or scenarios.
### **Prerequisites**
- Basic knowledge in API test building
### **Making API Parameterized and Marking Fields**
To mark the API test for parameterization, simply click the switch on the right-hand side of the “Info” tab of any API test labeled “Make API Parameterized” as seen in the screenshot below.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.086.png)

To mark certain fields and inputs for parameterization, simply click the switch next to those fields. View the example screenshot below.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.087.png)
### **Downloading & Uploading the Template**
Afterwards, click the Save button and then the Download button, both located in the upper right-hand corner of the page. A dialog box will open where the user clicks a button to download the template and then upload the template after filling in necessary data.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.088.png)

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.089.png)

Afterwards, a file formatted as <Your-Test-Case-Name>\_Data.xslx will be downloaded. Open this file and there will be a column named Test\_Case. The other columns will be all of the Data Column names that were given in the steps specified as parameterized.

Enter test case names under the Test\_Case column. Each test case will use its associated data in the example data column(s) to the right of it.

If a user wants to skip a step in a test case, they can provide the ~ symbol as the data.

![](Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.090.png)
