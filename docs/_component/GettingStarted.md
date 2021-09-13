||||
| :- | :-: | -: |

**Component Documentation**
# **Overview**
By definition, the term component means to be one part of a whole thing; therefore, when you need to test a whole project that has multiple sections, the Component platform will allow the user to break those large projects into smaller API, Mobile, and/or Web components. By breaking down and testing the components, you are able to figure out where errors occur much easier and faster.
# **Component Basics**
- Project Setup
  - Creating a project
- User Roles
  - **Designer**: Designers can design and test components; however, they cannot approve a component to sending it to the testing stage.
  - **Reviewer**: Reviewers can design, test components, and approve a component to the testing stage; however, Reviewers cannot approve the components they specifically created.
  - **Tester**: Testers are not able to design or approve components to the testing stage. The tester is only allowed to tests components after it has been approved.
- Design Components - Creating Component, Quick Run, Send for Approval
  - API
  - Mobile
  - Web
- Test Components
  - Create tests
  - Import desired components
  - wire component to create complete component test
  - Save & Run
- Reports - analyze any given test run
  - Test reports table
    - Name, Date & Time, Status, Details, watch send or save live video, and more 
  - Execution Summary Report
    - Step Description, Expected results, Actual results, Status, Execution time, and per step screenshots

    
# **Project Setup **
## Creating Project
There are two ways to create a new project in the component service. 

**Create Project** – click on either the create project button or the empty space to create a new project, fill out a project name, description, and who has access to your project

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.001.png)
### **Note:** Different Roles for who has access to the project
#### *Designer – design components and test (cannot approve)*
#### *Reviewer - like admin role*
#### *Tester - only design tests (cannot approve)*

**Import Scripts** – selecting import scripts you have a choice of different scripts that is provided for you as a template

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.002.png)

**Note:** Different types of imports

*Web Automation – Scripts that run web scripts*

*Web Repository – Scripts that run large collection of data ‘objects’*

*Mobility – Scripts that run mobile applications*

**Configuration**

Before you create components and test them, head to the setup to make sure you have the prerequisites to create/run the components

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.003.png)
## **Device Pool (redirect to Mobile?)**
This is where you will go to setup a mobile virtual device to be used to test mobility component tests. Create a new mobility device and through the whole list select any device that fits the requirements for your mobility test, save and continue

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.004.png)

**Note:** For more information on devices checkout **Mobility** in the documentation
## **File Management (Application Management) (redirect to Mobile?)**
This is where you will upload your files that are required to be tested, adding such files the component tests will be able to access.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.005.png)

**Note:** For more information on devices checkout [**Mobility](https://cogcloud.atlassian.net/wiki/spaces/HOW/pages/593363155/Mobility+Documentation)** in the documentation

## **Remote Device (redirect to Mobile?)**
This is where you are going to combine both the device pool and file management

**Instructions:**

1. Choose your device region
1. Select the application test you have uploaded
1. From the list of devices you copy the device to the clipboard

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.006.png)

**Note:** For more information on devices checkout **Mobility** in the documentation
## **Database Configuration (skip for now – redirect to Web?)**
This is where you will be creating a simple database that will be used in your testing **if needed** to do a complete test. If your test does not require some sort of database you can skip this step

**Instructions:**

1. Create a new configuration
1. Create name for the database
1. Choose between MySQL or PostgreSQL
   1. MySQL handles simpler database while PostgreSQL handles complex queries and massive databases
1. Create a hostname to create its location where your database is located i.e, **db.examplehostname**
1. Create a port number to be able to connect directly to the database or another application to the database, **Default value: 3306**
1. Create a database name, **specific**, to the database, gives it an identity when trying to call the database
1. Create a username and password to limit the access to your database. If you would like others to use your configured database, give them your **username and password**

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.007.png)
## **Global Variables**
This is where you will create global variables that can be used throughout the entire service you are using, in this case, the component service. To test repetitive and main variables create them here so you can get access to them by calling them with **# <variable-name> #**

**List of types of variables:**

- Custom – any value you want from strings to integers to double to booleans
- Integer – any whole number 
- Decimal – any decimal number
- UUID/GUID - Unique Identifier that is used to hold information unique to the specific ID you give. GUID are used for microsoft software
- Email - any strings that are attached with *@email.com*
- Date - any date that follows the **dd-MM-yyyy format**
- BaseURL - any form of base URL I.e. **google.com** 
- FirstName - any first name
- LastName - any last name

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.008.png)
# **Design Components **
Design Components is the section of the Component platform where users can create individual API, Mobile, and/or Web components, which then can be sent off for approval so they can be used for tests.

In order to begin designing components, the user must first navigate into a project by clicking on the ‘Select Project’ button.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.009.png)

The user will then be directed to the Component Dashboard. From here, the user will be presented with options to design components, test components, and do a project setup. The user’s ability to perform these tasks depends on the roles that were assigned to them during ‘Project Setup’. There are three different roles a person can be.

1. Designer: Designers can design and test components; however, they cannot approve a component to sending it to the testing stage.
1. Reviewer: Reviewers can design, test components, and approve a component to the testing stage; however, Reviewers cannot approve the components they specifically created.
1. Tester: Testers are not able to design or approve components to the testing stage. The tester is only allowed to tests components after it has been approved. 

Therefore, if the user’s role is not Designer or Reviewer, the user will not be able to design components.

In order for a user to begin designing components, click on the ‘Design’ button.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.010.png)
## Component Building
After clicking on the ‘Design’ button, the user will be brought to the Component Design page. From here, the user can select which category they would like to design a component for. They will be able to select from:

1. API
1. Mobile
1. Web

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.011.png)
### API
#### *Create Component*
After navigating into Component Design and clicking the ‘Select’ button under the API section, the user can begin creating their components. If the user has not built a component in the API category before, the user will have three options available for building a component. These options include: 

1. Importing a Swagger URL
1. Uploading a Swagger JSON
1. Creating a manual API test 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.012.png)

All steps on importing and uploading via Swagger can be viewed in the API Testing Documentation under API Performance -> Create Test Script.

When creating a Manual API Testing, the user must click on the ‘Add’ button under ‘Create Manual API Test’. After clicking on the button, a form will appear that will require the user to enter:

1. Component Name
1. Module Name
1. Component Description

After filling out the form, click on ‘Create Component’ button and the newly created component will appear.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.013.png)

If a component has already been created, then the user can create another component by clicking on the ‘Create Component’ button located on the left panel.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.014.png)

When the ‘Create Component’ button is clicked, the same Create Component Form as previously mentioned will appear. After filling out the form, click on ‘Create Component’.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.013.png)
#### *Test Steps*
After the ‘Create Component’ form has been filled out or a Swagger component was imported, the user will be brought to the ‘Test Steps’ page. From here, the user will be prompted to fill out a form that will create an API connection. The user will be required to enter:

1. Context Path
1. Protocol
1. End Point
1. Port Number
1. Verbs
   1. Get
   1. Post
   1. Put
   1. Delete
   1. Patch

After filling out the form, the user can click on the ‘Save’ icon on the top right.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.015.png)
### Mobile
#### *Create Component*
After navigating into Component Design and clicking the ‘Select’ button under the Mobile section, the user can click on the ‘Create Component’ button on the left panel.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.014.png)

Next, the ‘Create Component’ form will appear and the user will be required enter: 

1. Component Name
1. Module Name
1. Component Description

After this form is completed, click on ‘Create Component’.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.013.png)
#### *Test Steps*
After clicking on ‘Create Component’, the user will be able to begin creating their test steps by clicking on the ‘Add Step’ button.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.016.png)

Clicking on ‘Add Step’ will bring the user to the ‘Test Step’ page. Here the user can create all their test steps. Each test step requires the user to select an action type. After an action type is selected, all of the other required fields will contain a red ‘\*’ symbol, which is located to the right of the text field title. 

The user can also add more steps by clicking on the blue ‘Add Step’ button located on the bottom right of the page.

After all the steps have been completed, click on the green ‘Save’ icon on the top right of page.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.017.png)
### Web
#### *Create Component*
After navigating into Component Design and clicking the ‘Select’ button under the Web section, the user can create a component by clicking on the ‘Create Component’ button located on the left panel. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.018.png)

Next, the ‘Create Component’ form will appear and the user will be required enter: 

1. Component Name
1. Module Name
1. Component Description

After this form is completed, click on ‘Create Component’.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.013.png)
#### *Test Steps*
After clicking on ‘Create Component’, the user will be able to begin creating their test steps by clicking on the ‘Add Step’ button.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.016.png)

Clicking on ‘Add Step’ will bring the user to the ‘Test Step’ page. Here the user can create all their test steps. Each test step requires the user to select an action type. After an action type is selected, all of the other required fields will contain a red ‘\*’ symbol, which is located to the right of the text field title. 

The user can also add more steps by clicking on the blue ‘Add Step’ button located on the bottom right of the page.

After all the steps have been completed, click on the green ‘Save’ icon on the top right of page.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.019.png)
## Quick Runs
Quick runs are useful for making sure a test runs correctly before sending it for approval.

After the user creates their test steps, the user can click on the blue ‘Play’ button located on the top right of the screen to begin their quick run. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.020.png)

When running a quick run on a Mobile and Web component, a pop up will appear that will require more information to start the quick run.
### Mobile
After clicking on the blue ‘Play’ button to begin your quick run, a pop up will appear that prompt the user to enter the following:

1. Device Pool
1. A device from the Device Pool
1. An APK or IPA
1. App Activity
1. An option to enable a one-time password (OTP) (Optional)

After completing the form and clicking ‘Run’, the quick run will execute.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.021.png)
### Web
After clicking on the blue ‘Play’ button to begin your quick run, a pop up will appear that prompt the user to enter the following:

1. Operating System
1. Browser
1. Database Configuration (optional)
1. Enable Verify one-time password (OTP) (optional)

After completing the form and clicking ‘Run’, the quick run will execute.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.022.png)

### Viewing Quick Run Status
When the quick run begins, the user can click on the ‘Lighting Bolt’ icon on the right panel to view their quick run status. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.023.png)
## Approval Process
After a test script has been created and saved, the user can begin the approval process. The approval process differentiates depending on if the user has the role of Designer or Reviewer.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.024.png)
### Role: Designer
When the user has the role of ‘Designer’ and clicks on the red icon that represents ‘Send for Approval’, a notification will appear at the bottom right of the screen stating “Component Sent for Review”.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.025.png)

The user can click on the ‘Go Back’ button, the user can view the components current status.



![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.026.png)

### Role: Reviewer
When the user is given the role of ‘Reviewer’, they are able to approve or deny all components sent for review except components that they created.

The Reviewer can view all components waiting for approval by clicking on the ‘Awaiting Approvals’ tab located on the left panel. From here they can view their status and then click on ‘Go to Component’ to approve or deny component requests.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.027.png)

After clicking on ‘Go to Component’, the user can either click on the ‘Approve or Reject’ buttons located at the bottom of the right panel.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.028.png)


## Differences in Web Test Building
1. No Repository to store tests
1. No Sprints
1. No Test Execution
###
## Differences in Mobile Test Building
1. No live testing available
1. Unable to create test suites
## Differences in API Test Building
1. Does not support Graph QL
# **Test**
## Creating Tests 
After creating a project, click on the ‘Select Project’ button.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.009.png)

After doing so the user can navigate to the ‘Test’ tab of the component section to begin the process of creating a component test.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.029.png)

From the ‘Test’ page a user has access to all previously created tests in a given project with details including test description, linked components, different potential actions, and a link to go to the test. From this navigation click ‘Create Test’ to continue the test creation process. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.030.png)

Provide a:

- Test Name
- Module Name
- Test Description

Upon completion click the ‘Create Test’ button

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.031.png)
###
### Adding Components

Upon Creation of a new Test the user will be prompted to the step creation page. It is important to note a few things. 

On the left half of the page, there exists a component menu where the user can select individually created components. Note the mobility, or web icons on the component selectors identify the origins of the component.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.032.png)

Upon identification of the desired component for a given test, click the yellow ‘Plus’ button to add that component to the connections display. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.033.png)

###
### Wiring Components

Upon the addition of two or more components, each of them must be wired. The center of the screen holds the connections display. This allows the User to create connections between components and build out complete component tests. Note there is a delete and reset button on the top right corner of the display, and a handy reset view button in case the user loses track of the components

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.034.png)

Wiring components is a multiple step process:

- Click ‘Add Connection’ button
- Generate a connection by clicking and holding the desired starting script
- Then, while holding the cursor down, drag the arow icon to the desired end script
- When the two components are shown adjoined with a blue arrow the components are wired 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.035.png)

Click the ‘Save’ Icon, followed by the ‘Next’ button

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.036.png)

### API Data Handlers
Data handlers can be found in the ‘Test Steps’ portion of the API test component, assuming that one of your components is an API test. The two potential Data handlers, which can be found under the ‘Data Handlers’ tab in the step menu include:

- Get (GetDataHandler)
- Set (SetDataHandler)

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.037.png)The ’Get’ Data handler allows the user to capture API response values and store them in variable format for future use. This handler requires the desired Json Path, and a variable name. For request bodies, the User should enter ’$’ as the Json Path with a variable name in the variable field. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.038.png)

The ‘Set’ Data handler bridges the test script with the given API call. The handler requires:

- Key – the key dropdown will allow you to select from a list of previously created variables using the ‘Get data handler’. The ‘Set’ key corresponds with the ‘Get’ variable name. 
- Actual Parameter name – desired parameter name
- Parameter type (5 options)
  - Path
  - Query
  - Request Body
  - Request Key
  - Header

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.039.png)

During the Test Step creation phase, it is important to note:

- If there are parameterized steps included in any given component test (web, mobile, or API) the parameterization can be handled in step using the parameterization dropdown, or within the file using a ‘~’ in replacement of the desired test step to skip. 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.040.png)

- The ‘Mark As Component’ feature allows you to flag given test scripts upon creation. These scripts are now available in the ‘Component testing’ menu and can be easily imported into component tests.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.041.png)

It is also important to note the ‘Test steps’ page. 
## Executing Tests & Viewing Reports
Upon the creation and saving of a given test script, the user can use the ‘Run’ button to navigate from the created test to the results tab. Upon run the user will be prompted to provide specifics in relation to the component tests being run.

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.042.png)

Upon running the test the user will be navigated to the ‘Component Report’ tab. It is important to note a few features:

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.043.png)

- The Test Reports table
- Action types upon the test script
  - It is important to note action types such as a downloadable execution video, send and savable test scripts, reset and delete test scripts, upon more. 
- Test reports search box
- ‘View Details’ tab for step-by-step execution results

Click the ‘View Details’ tab on the far-right side of any given step. This will lead you to the ‘Component steps’ page where it is important to note:

- Tests passed 
- Tests failed
- Step description
- Actual results
- Expected results
- Status 
- Execution time
- Screenshots 

![](Aspose.Words.2f572e7c-e1bc-424a-bb14-b916aa36d020.044.png)

Step by step execution and results can now be viewed by the user.
||||
| :- | :-: | -: |

