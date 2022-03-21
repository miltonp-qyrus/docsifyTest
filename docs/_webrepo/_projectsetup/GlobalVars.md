<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Web Repository</h1>

# Project Setup
Under Project Setup, the user is able to set up various parameters, arguments, and configurations in order to run their test as they want.

## Global Variables <!-- {docsify-ignore} --> 
Global variables can be utilized to make test maintenance easier for the user. A user can create multiple “Environments” or profiles in order to hold different global variables in. These variables can be used in any test script within the project.

Global variables are recommended when:

1. A value is being reused multiple times throughout a test
1. Creating variables to synthetically generate data

### Creating Global Variables: 
1. Navigate into a project that was previously created
2. Click on ‘Project Setup’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Global_Var_1.png">

3. Click on ‘Global Variable’ on the black panel on the left side of the screen

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Global_Var_2.png">

4. Click on ‘New Variable’ on the top right of the page
5. After ‘New Variable’ is clicked, a form will appear that requires a variable name, a variable type (custom, integer, decimal, etc.) and a variable value
6. After these values are entered, click the save button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Global_Var_3.png">

### Viewing Global Variables
**Note: SCRIPT MUST BE CREATED FIRST**
1. Navigate to an area where you are able to create test scripts (Test Repository, Sprints, or Test Lab)
1. Next, navigate into a previously created test script. After navigating into a test script, you will see a blue panel on your right side. Click on the arrow pointing to the right and you will see a tab that says ‘Global Variable’.
1. Click on ‘Global Variable’, click on the ‘Select Environment’ dropdown, and select ‘Global’
1. After this you will see all the global variables created.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/View_Global_Var_1.png">

### Using Global Variables
1. Navigate to an area where you are able to create test scripts (Test Repository, Sprints, or Test Lab)
2. Next, navigate into the previously created test script. If a test script has not been created, please view the ‘Creating Scripts’ documentation.
   1. After navigating into a test script and a test step has not been created yet, click on ‘Create Step Manually’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Use_Global_Var_1.png">

3. Click on ‘Add Step’ and then begin creating the steps. This is where you will add your global variables. When adding global variables, it is important to add a ‘#’ sign before and after the variable name. Ex: #Google\_Website# and #Search\_Query#
4. After all your steps are made, click ‘Save’ in the top right corner

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Use_Global_Var_2.png">

### Edit/Delete Global Variables
1. Navigate into a project
2. Click on Project Setup

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Edit_Global_Var_1.png">

3. On the far-right side of the global variable table, there will be an edit and delete icon. Click on the icon to perform the action you want completed.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Edit_Global_Var_2.png">

### Synthetically Generate Data with Global Variables
Users can synthetically create data with global variables and use that data in test scripts for data generation.
In order for a user to synthetically generate data, the user must:

1. Navigate into a project and click on ‘Project Setup’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Synth_Global_Var_1.png">

2. Click on ‘Global Variable’ located on the black panel on the left side.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Synth_Global_Var_2.png">

3. Click on the ‘New Variable’ button located on the top right of the page.

In order to synthetically generate data, the user must select one of these 6 options for the data type. These options include:

1. UUID/GUID
1. firstName
1. lastName
1. Email
1. Integer
1. Decimal

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Synth_Global_Var_3.png">


- When selecting UUID/GUID, a random value will be assigned to that variable at runtime. 

- When selecting firstName or lastName, a random name will be assigned to that variable at runtime.

- When selecting an email, the user will have an option to enter an email or generate a random email. When generating a random email, the format will look like **???????##@gmail.com**. The ‘?’ symbol represents a random letter and the ‘#’ symbol represents a random number. Therefore, in this example, the email will generate 7 random letters, 2 random numbers and have the domain @gmail.com.

- When selecting Integer or Decimal, the user will be prompted to enter a Min and Max value. After the user enters these values, a random number will be generated that fall between these two values. 

## Global Variables

<video width="600px" height="400px" controls>
  <source src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/Web/Clip19-GlobalVariables.mp4" type="video/mp4">
</video>