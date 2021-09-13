<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Web Repository</h1>

# Other
## Parameterizing Tests <!-- {docsify-ignore} --> 
Qyrus allows for steps to be parameterized. This allows the user a more dynamic range of test usage, allowing for one test to cover different test cases or scenarios.
### Prerequisites
- Basic knowledge in test building
### Marking Steps for Parameterization
To mark a step for parameterization, simply click the “Parameterize” button and ensure it is highlighted. Then, give a name for the parameter data column. This will show up in the downloaded parameter file. Make sure to save the test before continuing.

![Parameterize 1](../../_media/_webimages/Aspose.Words.404e87e9-6ed7-4fc7-ac81-b7d471d1c9f8.117.png)
### Downloading, Adding Data, and Uploading File
Afterwards the user will be able to download the parameter file. To do this, on the right panel, go to the “Parameter File” tab and then click the “Download Template” button.

![Parameterize 2](../../_media/_webimages/Aspose.Words.404e87e9-6ed7-4fc7-ac81-b7d471d1c9f8.118.png)

Afterwards, a file formatted as <Your-Test-Case-Name>\_Data.xslx will be downloaded. Open this file and there will be a column named Test\_Case. The other columns will be all of the Data Column names that were given in the steps specified as parameterized.

Enter test case names under the Test\_Case column. Each test case will use its associated data in the example data column(s) to the right of it.

If a user wants to skip a step in a test case, they can provide the ~ symbol as the data.
![Parameterize 3](../../_media/_webimages/Aspose.Words.404e87e9-6ed7-4fc7-ac81-b7d471d1c9f8.119.png)

Finally, upload the file to Qyrus by clicking the “Upload Template” button and choose the file.


![Parameterize 4](../../_media/_webimages/Aspose.Words.404e87e9-6ed7-4fc7-ac81-b7d471d1c9f8.120.png)

Note: To parameterize clicks, make sure to specify what locator type will be used and then provide “##” in the locator value field as shown below:
![Parameterize 5](../../_media/_webimages/Aspose.Words.404e87e9-6ed7-4fc7-ac81-b7d471d1c9f8.121.png)