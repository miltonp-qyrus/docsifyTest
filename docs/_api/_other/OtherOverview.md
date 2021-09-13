<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">API Testing</h1>

# Other
## SOAP and GraphQL <!-- {docsify-ignore} --> 
Qyrus allows for usage of multiple different types of standards-based web services access protocols. Currently, there is support for REST, SOAP, and GraphQL. To select a standard, use the radio buttons that can be found at the top of the “Info” tab window. 

Note: REST will automatically be selected as default.
![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.071.png)

### Prerequisites
- High level knowledge in API testing and test building
- Knowledge in building assets in Service Virtualization

### Setup
The first thing to do is set up two APIs in the Service Virtualization service.

#### Login API
This Login API will simulate a user signing in and then receiving some sort of key back for authentication. Set up the Login API exactly as shown in the below screenshot and save.

Note: Make sure to click the “Online” switch in order to make the API go live. Afterwards, take note of the Url given (ex: http://testinfra.quinnox-int.info:8085/<context>).

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.072.png)

**Request:** { "email": "example@ex.com", "pwd": "abc123" }

**Response:** { "someKey": "aBcDeFg123" }

#### Example API
Now, in a very similar way, make an example API and fill it out like the below screenshot and save. One thing to note is that in this API the method is GET and there is a header called “auth” using the “someKey” value from the Login API response.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.073.png)

**Response:** { “response”: “Hello” }

**Header:** auth : aBcDeFg123

### Prerequisite API Test Creation
After navigating into the API Testing service, click the “Variables” button in the upper right-hand corner.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.074.png)

Navigate into the “Prerequisite API” tab and click the “Add API” button.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.075.png)

The next screen given should be familiar. Enter in the information as seen in the screenshots below and make sure to click save.

(THE BODY WILL BE THE REQUEST FROM THE LOGIN API IN SERVICE VIRTUALIZTION)

Note: In the “Data Handers” tab the user is able to not only pull from a JsonPath but also XPath, Headers, and allow for some JavaScript usage.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.076.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.077.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.078.png)

Note: Users can test run their Prerequisite APIs by clicking the “Run” button and then navigating back and clicking the reports button on the Prerequisite API list as shown below.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.079.png)

Clicking the “Dynamic Variables” tab will show the new “auth” variable created in the login prerequisite.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.080.png)

### Test Creation & Execution
Click the “Go Back” button in the upper right-hand corner of the screen to navigate back to API testing. Create a new APi test and fill it out as shown in the screenshots below and click save.

Note: In the “Headers & Params” tab the dynamic variable is used in the header section and is surrounded by pound signs (##) in order to active usage.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.081.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.082.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.083.png)

Finally, run the API test and view the report. It will look like the screenshot below. Clicking the “Prerequisite Results” tab will show the report for the Prerequisite API.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.084.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.085.png)

## Parameterizing Tests
Qyrus allows for certain fields and inputs to be parameterized. This allows the user a more dynamic range of test usage, allowing for one test to cover many different test cases or scenarios.
### Prerequisites
- Basic knowledge in API test building

### Making API Parameterized and Marking Fields
To mark the API test for parameterization, simply click the switch on the right-hand side of the “Info” tab of any API test labeled “Make API Parameterized” as seen in the screenshot below.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.086.png)

To mark certain fields and inputs for parameterization, simply click the switch next to those fields. View the example screenshot below.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.087.png)

### Downloading & Uploading the Template
Afterwards, click the Save button and then the Download button, both located in the upper right-hand corner of the page. A dialog box will open where the user clicks a button to download the template and then upload the template after filling in necessary data.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.088.png)

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.089.png)

Afterwards, a file formatted as <Your-Test-Case-Name>\_Data.xslx will be downloaded. Open this file and there will be a column named Test\_Case. The other columns will be all of the Data Column names that were given in the steps specified as parameterized.

Enter test case names under the Test\_Case column. Each test case will use its associated data in the example data column(s) to the right of it.

If a user wants to skip a step in a test case, they can provide the ~ symbol as the data.

![](../../../_media/_apiImgs/Aspose.Words.1a0bb08a-a30f-4674-a26b-60d476b195cd.090.png)