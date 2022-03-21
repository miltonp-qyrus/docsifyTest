` `PAGE   \\* MERGEFORMAT 47

**Mobile Documentation**

# Contents
` `TOC \o "1-3" \h \z \u [**Getting Started**	 PAGEREF _Toc74142710 \h 3](#_Toc74142710)

[**Overview**	 PAGEREF _Toc74142711 \h 3](#_Toc74142711)

[**Basics**	 PAGEREF _Toc74142712 \h 3](#_Toc74142712)

[**Test Setup & Building**	 PAGEREF _Toc74142713 \h 3](#_Toc74142713)

[**Project Creation**	 PAGEREF _Toc74142714 \h 3](#_Toc74142714)

[**Test Suites**	 PAGEREF _Toc74142715 \h 4](#_Toc74142715)

[**Prerequisites:**	 PAGEREF _Toc74142716 \h 4](#_Toc74142716)

[**Project Setup**	 PAGEREF _Toc74142717 \h 5](#_Toc74142717)

[**Prerequisites:**	 PAGEREF _Toc74142718 \h 5](#_Toc74142718)

[**App Management**	 PAGEREF _Toc74142719 \h 6](#_Toc74142719)

[**Database Configuration**	 PAGEREF _Toc74142720 \h 7](#_Toc74142720)

[**Device Pool**	 PAGEREF _Toc74142721 \h 10](#_Toc74142721)

[**Global Variables**	 PAGEREF _Toc74142722 \h 12](#_Toc74142722)

[**Remote Devices**	 PAGEREF _Toc74142723 \h 13](#_Toc74142723)

[**Test Scripts**	 PAGEREF _Toc74142724 \h 15](#_Toc74142724)

[**Prerequisites:**	 PAGEREF _Toc74142725 \h 15](#_Toc74142725)

[**Creating Scripts Manually**	 PAGEREF _Toc74142726 \h 15](#_Toc74142726)

[**Creating Scripts Using Live Test**	 PAGEREF _Toc74142727 \h 16](#_Toc74142727)

[**Interacting with device during live test building**	 PAGEREF _Toc74142728 \h 21](#_Toc74142728)

[**Adding Test Script Steps**	 PAGEREF _Toc74142729 \h 23](#_Toc74142729)

[**Prerequisites:**	 PAGEREF _Toc74142730 \h 23](#_Toc74142730)

[**Executing Tests & Viewing Reports**	 PAGEREF _Toc74142731 \h 27](#_Toc74142731)

[**Prerequisites:**	 PAGEREF _Toc74142732 \h 27](#_Toc74142732)

[**Execute Test/Dry Run**	 PAGEREF _Toc74142733 \h 27](#_Toc74142733)

[**Scheduling Test Executions**	 PAGEREF _Toc74142734 \h 35](#_Toc74142734)

[**Other**	 PAGEREF _Toc74142735 \h 37](#_Toc74142735)

[**Parameterizing Tests**	 PAGEREF _Toc74142736 \h 37](#_Toc74142736)

[**Prerequisites:**	 PAGEREF _Toc74142737 \h 37](#_Toc74142737)

[**Marking Steps for Parameterization**	 PAGEREF _Toc74142738 \h 38](#_Toc74142738)

[**Downloading, Adding Data, and Uploading File**	 PAGEREF _Toc74142739 \h 38](#_Toc74142739)

[**Using Healer**	 PAGEREF _Toc74142740 \h 39](#_Toc74142740)

[**Prerequisites**	 PAGEREF _Toc74142741 \h 40](#_Toc74142741)

[**Setup**	 PAGEREF _Toc74142742 \h 40](#_Toc74142742)

[**Usage**	 PAGEREF _Toc74142743 \h 41](#_Toc74142743)

[**Verify OTP**	 PAGEREF _Toc74142744 \h 44](#_Toc74142744)

[**Prerequisites**	 PAGEREF _Toc74142745 \h 44](#_Toc74142745)

[**Setup**	 PAGEREF _Toc74142746 \h 44](#_Toc74142746)

[**Usage**	 PAGEREF _Toc74142747 \h 44](#_Toc74142747)

[**Marking Script for Component Importing**	 PAGEREF _Toc74142748 \h 46](#_Toc74142748)

[**Prerequisites**	 PAGEREF _Toc74142749 \h 46](#_Toc74142749)

[**Usage**	 PAGEREF _Toc74142750 \h 46](#_Toc74142750)

[**Using Dynamic Action Types**	 PAGEREF _Toc74142751 \h 47](#_Toc74142751)

[**Prequisites**	 PAGEREF _Toc74142752 \h 47](#_Toc74142752)

[Setup	 PAGEREF _Toc74142753 \h 47](#_Toc74142753)


# **Getting Started**
##
## **Overview**
Mobility allows users to build and run automated tests for mobile applications on our physical devices in our device farm. This is a brief document on how to get started with Mobility. For additional information reference the larger documentation as a whole.
## **Basics**
The Mobility service is comprised of 2 basic steps:

- Test Setup & Building – Create a project, a module and a script to test your iOS or Android apps. Build Live tests on your computer by interacting with real devices with keyboard and mouse
- Execution & Reports – Execute your mobile test scripts and see the results with picture and video evidences in the reports page.
# **Test Setup & Building**

## **Project Creation**
1. Click on Mobility 
2. Click on ‘New Project’ 
3. Enter a project name 
4. Enter a project description  
4. Select Device Type
5. Checkmark any teammates that will be working on the project 
6. Click ‘Create Project’  

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Mobile_Create_Project.png">
## **Test Suites**
### **Prerequisites:** 
- Basic knowledge on how to build a Project 
- Created Project 

Test Suites are folders where you can store and organize your test scripts. This section shows how to create a test suite.

1. Click on ‘Create Suite’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Suite_1.png">
1. Enter a Test Suite Name
1. Enter a Module Name 
1. Click on ‘Create Suite’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Suite_2.png">
### **Prerequisites:** 
- Created Project 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Prerequisites.png">

### **App Management**
Click on ‘Application Management’ to upload your apk or ipa file based on your device type

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_App_Management_1.png">

1. Click on ‘Upload APK’ or ‘Upload IPA’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_App_Management_2.png">

1. Click on ‘Choose File’ and select your APK or IPA file or drag the file inside the square

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_App_Management_3.png">

1. When uploaded successfully, you will see the app as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_App_Management_4.png">


### **Database Configuration**
Click on ‘Database Configuration’ to setup your database connection

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_DB_Config_1.png">

1. Click on ‘New Configuration’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_DB_Config_2.png">

1. Enter a Configuration Name
1. Enter your database information
1. Click ‘Create Config’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_DB_Config_3.png">

1. When created successfully, you will see your database as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_DB_Config_4.png">

### **Device Pool**
Click on ‘Device Pool’ to setup devices to run your tests on

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Device_Pool_1.png">

1. Click on ‘New Device Pool’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Device_Pool_2.png">

1. Enter a Device Pool Name
1. Check the devices you want in this device pool
1. Click ‘Save and Continue’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Device_Pool_3.png">

1. ` `When created successfully, you will see your device pool as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Device_Pool_4.png">
### **Global Variables**
Global variables are recommended when:

1. A value is being reused multiple times throughout a test
1. Creating variables to synthetically generate data

Click on ‘Global Variables’ to create the variables

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Global_Variable_1.png">

1. Click on ‘Add’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Global_Variable_2.png">

1. Click on the dropdown menu for ‘Type’ and select an option
1. Enter a Variable Name
1. Enter a Variable Value
1. Click ‘Add’ to add another variable
1. Click the red trashcan to delete the variable
1. Click ‘Save’ to be able to use the variables created

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Global_Variable_3.png">

### **Remote Devices**
Click ‘Remote Devices’ to connect to the devices allocated in Qyrus

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Remote_Devices_1.png">

1. Select the device region
1. Select the application file you’ve uploaded on ‘Application Management’
1. Select the App Activity \*Android Only
1. Enter App Package
1. Enter the device name to narrow down device results
1. Click the ‘Clipboard icon’ button to copy the capabilities in JSON format

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Remote_Devices_2.png">

1. When done successfully, you will see the success message as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Project_Setup_Remote_Devices_3.png">

## **Test Scripts**
### **Prerequisites:** 
- Created Project 
- Created Suite

### **Creating Scripts Manually**

**Step 1:** User can also ***Create Test Script*** using ***Create Manually Test Script*** option by entering ***Test Script Name, Module Name*** and ***Objective*** of the test script.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Manually_1.png">

**Step 2:** Your script is now created. Click on the icon highlighted below to start building the action steps with the device. 



<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Manually_2.png">
**Step 3:** Tap on the device icon highlighted below to make the device screenshot panel disappear 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Manually_3.png">
Now you are ready to start building your test script

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Manually_4.png">
### **Creating Scripts Using Live Test**

- **Objective**: Get Mobile device to web browser
- **Set Up**: APK/IPA upload and Device Pool configuration

After creating the project and test suite, now we can Create a Test Script

**Step 1:** Click on the Create Test Script Button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_1.png">

**Step 2:** Enter the Test Script Name, Module Name, and the Objective of your test script. The Next button helps the user to select the application and choose the device created from the device pool section. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_2.png">


**Step 3:** Choose your APK/IPA file and Device Pool that you had uploaded in the Setup section <source <img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_3.png">

**Step 4:** You will then be asked to select your App Activity

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_4.png">
**Step 5:** After selecting your device, you will be able to see the status of the device highlighted below. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_5.png">
**Step 6:** Click the “Build Live Test” button

Now you are ready to start building your test script

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_6.png">
Users also have an option to ***import the scripts to Restore point***. After selecting your APK/IPA file and device pool, users should click on ***Advanced Options*** to ***import the scripts***.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_7.png">
Click on ***Import test script to restore point*** button so you can see the list of suites.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_8.png">

After clicking on suite, user can see the list of scripts, select the script*** which needs to be imported and click on ***Import*** button.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_9.png">

After importing the script user should click on the ***Build Live Test*** button.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Create_Live_10.png">

### **Interacting with device during live test building**
This section covers connecting to a device and details of the icons in interacting with the device. 

If you are not connected to a device, click on the highlighted button as shown below to connect to a device.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Interacting_Live_1.png">

Once you are connected, you are able to interact with the device using these buttons

1. Click on the ‘grey mobile device’ button to hide the device
1. Click on the ‘Mouse Cursor Hand’ button to get the coordinates on the device using your mouse
1. Click on the ‘Refresh’ button to get an updated screenshot of the device
1. Click on the ‘Back’ button to go back to the test page
1. Click on the ‘Quick Search’ toggle fetch locator values that are quicker to find
1. Click on the ‘Green Tilted Phone’ button to disconnect the device

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Test_Script_Interacting_Live_2.png">

## **Adding Test Script Steps**

### **Prerequisites:** 
- Created Project 
- Created Suite
- Connected to Device Pool

A test script is comprised of one or more steps. For each step, you will generally need to provide between 2-4 of the following based on a particular action type: 

- *Test description*
- *Action Type*
- *Location of the element* (Id, Name, XPath, Class, AccessibilityID, index) 
- Any *data or* *input values* you will need to send to the element. 

**Note:** After each step creation, make sure to save your script before you leave or execute. 


<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_1.png">


In this example, we will type out the username by fetching the locator value for username

In the Description, you can say “Set Username”. 

To fetch the location of an element, click on the location where you want to fetch the value from with your mouse. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_2.png">

Wait for the green notification bar saying “The element has been set successfully” and the Id Value will appear automatically.


<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_3.png">

You can also check if it selected the element that you expected using “Verify Element” button. The bounding boxes should appear on the mobile device with the green notification saying “Bound has set successfully”. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_4.png">

For this step, lets type out the username. You would want to change the Action Type to “Set” under “Input Events”. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_5.png">

You can now check to see if the step actually passes by clicking on “Execute Step”. We can also see whether it typed “admin” on the username field and seeing the green “Pass”. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_6.png">

Users can also make a particular step as ***Optional*** and ***Enable/Disable the Screenshot*** for the step in Step Creator.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_7.png">

Now you can “Push to Script”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Add_Steps_8.png">

# **Executing Tests & Viewing Reports**
## **Prerequisites:** 
- Created Project 
- Created Suite
- Created Script
- Setup Device Pool





## **Execute Test/Dry Run** 

**Note:** Make sure to save your test scripts before executing your tests. Executing before saving will cause the test to ignore and lose the changes you’ve made. 

**Step 1:** To save a test script, click on the Save button highlighted below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_1.png">

**Step 2:** Click on the execute button on the top right. It will drop down the 2 ways of executing the tests: **Dry Run** and **Execute Run** 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_2.png">

**Dry Run** helps you run your test script without generating a report

**Execute Run** helps you to generate reports for your test scripts

**Step 3:** If you click on Dry Run, it would lead you to the following screen

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_3.png">

**Step 4:** Select the options with the right APK/IPA file, app activity, and Device pool of the app. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_4.png">

**Step 5:** Click on Execute Run

**Step 6:** Click on the Dry Run tab at the top to see the status of your “Dry Run” tests

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_5.png">

**Step 7:** You can click the “Refresh” button to see the updated status of your tests. The “Refresh Time” dropdown helps you to automatically update the result every 5s, 10, 15s, 30s, 45s, 60s without having to press the refresh button multiple times. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_6.png">

**Step 8:** You will see the test result under the “Status” column with either Pass/Fail/Cancelled

Note: *Dry Run tests gives the status of your last 5 tests only.* 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_7.png">

**Step 9:** Click on “View Details” to see the detail steps of your scripts

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_8.png">

**Step 10:** You can see the screenshots of each action of your script here

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Execute_9.png">

**Viewing Reports**

Execute run helps to generate reports of a test script.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_1.png">


Select the options with the right APK or IPA file, app activity, and Device pool of the app and click the “Execute Now” button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_2.png">
Click on the Reports tab

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_3.png">
**Running Tests** tab shows you the status of the running tests

**Test Results** tab shows you the status of your completed tests


<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_4.png">
If the tests are complete, it will disappear from the Running Tests tab. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_5.png">
Click on the Test Results tab and click on the highlighted icon to see the detailed steps of each action with screenshots. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/View_Report_6.png">

## **Scheduling Test Executions**

**Note:** Scheduling test takes place when you “Execute Run”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_1.png">

Click on “Advanced Options”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_2.png">

Select the toggle for the “Schedule Type”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_3.png">

The toggle will prompt you with two options: **Schedule Once** and **Schedule Repeat**

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_4.png">

For ***Schedule Once***, choose your date, time zone and time

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_5.png">

For ***Schedule Repeat***, you have the option to run your script Weekly, Daily, and Hourly.

For ***Weekly***, check the box with the days you want to run your tests with the time, time zone, and end date.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_6.png">

For ***Daily*** and ***Hourly***, fill out the time, time zone, and end date

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Schedule_7.png">

# **Other**

## **Parameterizing Tests**
Qyrus allows for steps to be parameterized. This allows the user a more dynamic range of test usage, allowing for one test to cover different test cases or scenarios.
### **Prerequisites:** 
- Created Project 
- Created Suite
- In progress of script building
### **Marking Steps for Parameterization**
To mark a step for parameterization, simply click the “Parameterize” button and ensure it is highlighted. Then, give a name for the parameter data column. This will show up in the downloaded parameter file. Make sure to save the test before continuing.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_1.png">

### **Downloading, Adding Data, and Uploading File** 
Afterwards the user will be able to download the parameter file. 

1. Click on the ‘Parameterize File’ button.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_2.png">

1. Click ‘Download File’ 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_3.png">

1. Open the xslx file that was downloaded
1. In the first column enter the test case names
1. Enter your data for the next columns. The column names will be populated based on the names you provided in the Data Column field for each step
1. Enter a ~ symbol for that test case to skip that step when running the script

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_4.png">

1. When you are finished filling out the data, click on the ‘Choose File’’ button
1. Select the xslx file
1. Click on ‘Upload File’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_5.png">

1. When done successfully, you will see the messages as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Param_6.png">
## **Using Healer**
Healer is an advanced AI tool that users can enable before they execute their test scripts. It helps prevent test flakiness and brittleness. Healer gives a response on a failing test that provides the user with the element information needed in order to fix their broken test. Below will be an example of running tests with Healer enabled. 
### **Prerequisites**
- Created Project 
- Created Suite
- Created Script
- Knowledge on how to run scripts
- Knowledge on how to look at reports

### **Setup**
1. Navigate inside your completed script. We will use this one step script as an example

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_1.png">

1. Execute run the script
1. Click the toggle to turn healer on or off. At default, healer will be on

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_2.png">

1. Execute the script
1. In the reports section, the ‘Bandage’ symbol will indicate that healer was used for the script
   1. **Note**: Script must pass in order for healer to have a baseline

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_3.png">
### **Usage**
When element locators change, healer will return the correct element locator value which would correctly navigate through the application as it normally does. To show this, we will change an element locator value in the script to an incorrect value. 

1. Navigate back into the test script and change the element value to an incorrect one.
   1. Example: com.ctclogindemo:id/et\_username -> com.ctclogindemo:id/et\_user

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_4.png">

1. Execute run the script with the healer option turned on
1. Go inside the failed test
1. Click on the ‘Healer’ button in the Actions section

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_5.png">

1. The Healer Response shows the correct value of the element

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_6.png">

1. Replace the element locator value in the script with this value in order for the script to correctly navigate through the application
## **Verify OTP**
This section will show how to enable the ‘Verify OTP’ action if your scripts requires to send a one time password.
### **Prerequisites**
- Created Project 
- Created Suite
- In progress of completing Script
- Knowledge on how to run scripts

### **Setup**

1. In your script, add a step with the action type ‘Verify Otp’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_1.png"> 
### **Usage**

1. Run the script with either ‘Dry Run’ or ‘Execute Run’
1. Enable the ‘OTP’ option

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_2.png"> 

1. While the script is running, click on the ‘Verify OTP’ button. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_3.png">  

1. Enter the one-time password

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_4.png"> 

1. Click the ‘green checkmark’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_5.png"> 

1. When done successfully, you will see the success message as shown below

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Verify_6.png"> 
## **Marking Script for Component Importing**
Qyrus allows users to reuse test scripts across multiple different solutions. Users are able to move test scripts from the Mobility over to Component Testing pretty easily. 
### **Prerequisites**
- Knowledge in Mobility 
- Knowledge in Component Testing 
- Tests to Import 
### **Usage**
1. Click on the ‘more options’ button for the script that you want to import

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Marking_Script_1.png"> 

1. ` `Click on ‘Mark As Component’ option

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Marking_Script_2.png">

1. When done correctly, the script will have this ‘Flag’ symbol

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Marking_Script_3.png"> 

1. Go to Component Testing and click the “Import Scripts” button. 

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Marking_Script_4.png">

1. Then, select Mobility, whichever scripts to import, and click the “Import” button.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Marking_Script_5.png">
## **Using Dynamic Action Types**
Qyrus allows users to create variables during test execution and use those values dynamically to perform a wide variety of actions. For a full list of actions, visit our Action Types Documentation (link here). 
### **Perquisites**
- Created Project 
- Created Suite
- In progress of completing Script
### Setup
1. In your script, add a step with the action type ‘Create Variable’ and grab the text of the desired element

