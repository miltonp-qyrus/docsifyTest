<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Component</h1>

# Tests

## API Data Handlers <!-- {docsify-ignore} --> 
Data handlers can be found in the ‘Test Steps’ portion of the API test component, assuming that one of your components is an API test. The two potential Data handlers, which can be found under the ‘Data Handlers’ tab in the step menu include:

- Get (GetDataHandler)
- Set (SetDataHandler)

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_componentImgs/Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.037.png">
The ’Get’ Data handler allows the user to capture API response values and store them in variable format for future use. This handler requires the desired Json Path, and a variable name. For request bodies, the User should enter ’$’ as the Json Path with a variable name in the variable field. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_componentImgs/Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.038.png">

The ‘Set’ Data handler bridges the test script with the given API call. The handler requires:

- Key – the key dropdown will allow you to select from a list of previously created variables using the ‘Get data handler’. The ‘Set’ key corresponds with the ‘Get’ variable name. 
- Actual Parameter name – desired parameter name
- Parameter type (5 options)
  - Path
  - Query
  - Request Body
  - Request Key
  - Header

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_componentImgs/Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.039.png">

During the Test Step creation phase, it is important to note:

- If there are parameterized steps included in any given component test (web, mobile, or API) the parameterization can be handled in step using the parameterization dropdown, or within the file using a ‘~’ in replacement of the desired test step to skip. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_componentImgs/Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.040.png">

- The ‘Mark As Component’ feature allows you to flag given test scripts upon creation. These scripts are now available in the ‘Component testing’ menu and can be easily imported into component tests.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_componentImgs/Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.041.png">

It is also important to note the ‘Test steps’ page. 