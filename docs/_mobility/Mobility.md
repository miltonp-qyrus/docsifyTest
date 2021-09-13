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

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.001.png)
## **Test Suites**
### **Prerequisites:** 
- Basic knowledge on how to build a Project 
- Created Project 

Test Suites are folders where you can store and organize your test scripts. This section shows how to create a test suite.

1. Click on ‘Create Suite’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.002.png)

1. Enter a Test Suite Name
1. Enter a Module Name 
1. Click on ‘Create Suite’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.003.png)
## **Project Setup**
### **Prerequisites:** 
- Created Project 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.004.png)

### **App Management**
Click on ‘Application Management’ to upload your apk or ipa file based on your device type

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.005.png)

1. Click on ‘Upload APK’ or ‘Upload IPA’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.006.png)

1. Click on ‘Choose File’ and select your APK or IPA file or drag the file inside the square

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.007.png)

1. When uploaded successfully, you will see the app as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.008.png)


### **Database Configuration**
Click on ‘Database Configuration’ to setup your database connection

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.009.png)

1. Click on ‘New Configuration’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.010.png)

1. Enter a Configuration Name
1. Enter your database information
1. Click ‘Create Config’

` `![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.011.png)

1. When created successfully, you will see your database as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.012.png)

### **Device Pool**
Click on ‘Device Pool’ to setup devices to run your tests on

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.013.png)

1. Click on ‘New Device Pool’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.014.png)

1. Enter a Device Pool Name
1. Check the devices you want in this device pool
1. Click ‘Save and Continue’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.015.png)

1. ` `When created successfully, you will see your device pool as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.016.png)
### **Global Variables**
Global variables are recommended when:

1. A value is being reused multiple times throughout a test
1. Creating variables to synthetically generate data

Click on ‘Global Variables’ to create the variables

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.017.png)

1. Click on ‘Add’

` `![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.018.png)

1. Click on the dropdown menu for ‘Type’ and select an option
1. Enter a Variable Name
1. Enter a Variable Value
1. Click ‘Add’ to add another variable
1. Click the red trashcan to delete the variable
1. Click ‘Save’ to be able to use the variables created

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.019.png)

### **Remote Devices**
Click ‘Remote Devices’ to connect to the devices allocated in Qyrus

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.020.png)

1. Select the device region
1. Select the application file you’ve uploaded on ‘Application Management’
1. Select the App Activity \*Android Only
1. Enter App Package
1. Enter the device name to narrow down device results
1. Click the ‘Clipboard icon’ button to copy the capabilities in JSON format

` `![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.021.png)

1. When done successfully, you will see the success message as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.022.png)

## **Test Scripts**
### **Prerequisites:** 
- Created Project 
- Created Suite

### **Creating Scripts Manually**

**Step 1:** User can also ***Create Test Script*** using ***Create Manually Test Script*** option by entering ***Test Script Name, Module Name*** and ***Objective*** of the test script.

` `![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.023.png)

**Step 2:** Your script is now created. Click on the icon highlighted below to start building the action steps with the device. 



![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.024.png)

**Step 3:** Tap on the device icon highlighted below to make the device screenshot panel disappear 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.025.png)

Now you are ready to start building your test script

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.026.png)
### **Creating Scripts Using Live Test**

- **Objective**: Get Mobile device to web browser
- **Set Up**: APK/IPA upload and Device Pool configuration

After creating the project and test suite, now we can Create a Test Script

**Step 1:** Click on the Create Test Script Button

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.027.png)

**Step 2:** Enter the Test Script Name, Module Name, and the Objective of your test script. The Next button helps the user to select the application and choose the device created from the device pool section. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.028.png)


**Step 3:** Choose your APK/IPA file and Device Pool that you had uploaded in the Setup section ![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.029.png)

**Step 4:** You will then be asked to select your App Activity

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.030.png)

**Step 5:** After selecting your device, you will be able to see the status of the device highlighted below. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.031.png)

**Step 6:** Click the “Build Live Test” button

Now you are ready to start building your test script

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.032.png)

Users also have an option to ***import the scripts to Restore point***. After selecting your APK/IPA file and device pool, users should click on ***Advanced Options*** to ***import the scripts***.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.033.png)

Click on ***Import test script to restore point*** button so you can see the list of suites.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.034.png)

After clicking on suite, user can see the list of scripts, select the script*** which needs to be imported and click on ***Import*** button.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.035.png)

After importing the script user should click on the ***Build Live Test*** button.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.036.png)

### **Interacting with device during live test building**
This section covers connecting to a device and details of the icons in interacting with the device. 

If you are not connected to a device, click on the highlighted button as shown below to connect to a device.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.037.png)

Once you are connected, you are able to interact with the device using these buttons

1. Click on the ‘grey mobile device’ button to hide the device
1. Click on the ‘Mouse Cursor Hand’ button to get the coordinates on the device using your mouse
1. Click on the ‘Refresh’ button to get an updated screenshot of the device
1. Click on the ‘Back’ button to go back to the test page
1. Click on the ‘Quick Search’ toggle fetch locator values that are quicker to find
1. Click on the ‘Green Tilted Phone’ button to disconnect the device

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.038.png)
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


![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.039.png)

In this example, we will type out the username by fetching the locator value for username

In the Description, you can say “Set Username”. 

To fetch the location of an element, click on the location where you want to fetch the value from with your mouse. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.040.png)

Wait for the green notification bar saying “The element has been set successfully” and the Id Value will appear automatically.


![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.041.png)

You can also check if it selected the element that you expected using “Verify Element” button. The bounding boxes should appear on the mobile device with the green notification saying “Bound has set successfully”. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.042.png)

For this step, lets type out the username. You would want to change the Action Type to “Set” under “Input Events”. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.043.png)

You can now check to see if the step actually passes by clicking on “Execute Step”. We can also see whether it typed “admin” on the username field and seeing the green “Pass”. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.044.png)

Users can also make a particular step as ***Optional*** and ***Enable/Disable the Screenshot*** for the step in Step Creator.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.045.png)

Now you can “Push to Script”

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.046.png)


# **Executing Tests & Viewing Reports**
## **Prerequisites:** 
- Created Project 
- Created Suite
- Created Script
- Setup Device Pool





## **Execute Test/Dry Run** 

**Note:** Make sure to save your test scripts before executing your tests. Executing before saving will cause the test to ignore and lose the changes you’ve made. 

**Step 1:** To save a test script, click on the Save button highlighted below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.047.png)

**Step 2:** Click on the execute button on the top right. It will drop down the 2 ways of executing the tests: **Dry Run** and **Execute Run** 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.048.png)

**Dry Run** helps you run your test script without generating a report

**Execute Run** helps you to generate reports for your test scripts

**Step 3:** If you click on Dry Run, it would lead you to the following screen

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.049.png)

**Step 4:** Select the options with the right APK/IPA file, app activity, and Device pool of the app. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.050.png)

**Step 5:** Click on Execute Run

**Step 6:** Click on the Dry Run tab at the top to see the status of your “Dry Run” tests

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.051.png)

**Step 7:** You can click the “Refresh” button to see the updated status of your tests. The “Refresh Time” dropdown helps you to automatically update the result every 5s, 10, 15s, 30s, 45s, 60s without having to press the refresh button multiple times. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.052.png)

**Step 8:** You will see the test result under the “Status” column with either Pass/Fail/Cancelled

Note: *Dry Run tests gives the status of your last 5 tests only.* 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.053.png)

**Step 9:** Click on “View Details” to see the detail steps of your scripts

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.054.png)

**Step 10:** You can see the screenshots of each action of your script here

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.055.png)

**Viewing Reports**

Execute run helps to generate reports of a test script.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.044.png)

Select the options with the right APK or IPA file, app activity, and Device pool of the app and click the “Execute Now” button

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.056.png)

Click on the Reports tab

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.057.png)

**Running Tests** tab shows you the status of the running tests

**Test Results** tab shows you the status of your completed tests


![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.058.png)

If the tests are complete, it will disappear from the Running Tests tab. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.059.png)

Click on the Test Results tab and click on the highlighted icon to see the detailed steps of each action with screenshots. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.060.png)

## **Scheduling Test Executions**

**Note:** Scheduling test takes place when you “Execute Run”

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.044.png)

Click on “Advanced Options”

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.061.png)

Select the toggle for the “Schedule Type”

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.062.png)

The toggle will prompt you with two options: **Schedule Once** and **Schedule Repeat**

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.063.png)

For ***Schedule Once***, choose your date, time zone and time

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.064.png)

For ***Schedule Repeat***, you have the option to run your script Weekly, Daily, and Hourly.

For ***Weekly***, check the box with the days you want to run your tests with the time, time zone, and end date.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.065.png)

For ***Daily*** and ***Hourly***, fill out the time, time zone, and end date

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.066.png)

# **Other**

## **Parameterizing Tests**
Qyrus allows for steps to be parameterized. This allows the user a more dynamic range of test usage, allowing for one test to cover different test cases or scenarios.
### **Prerequisites:** 
- Created Project 
- Created Suite
- In progress of script building
### **Marking Steps for Parameterization**
To mark a step for parameterization, simply click the “Parameterize” button and ensure it is highlighted. Then, give a name for the parameter data column. This will show up in the downloaded parameter file. Make sure to save the test before continuing.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.067.png)
### **Downloading, Adding Data, and Uploading File** 
Afterwards the user will be able to download the parameter file. 

1. Click on the ‘Parameterize File’ button.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.068.png) 

1. Click ‘Download File’ 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.069.png)

1. Open the xslx file that was downloaded
1. In the first column enter the test case names
1. Enter your data for the next columns. The column names will be populated based on the names you provided in the Data Column field for each step
1. Enter a ~ symbol for that test case to skip that step when running the script

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.070.png)

1. When you are finished filling out the data, click on the ‘Choose File’’ button
1. Select the xslx file
1. Click on ‘Upload File’

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.071.png)

1. When done successfully, you will see the messages as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.072.png)
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

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.073.png)

1. Execute run the script
1. Click the toggle to turn healer on or off. At default, healer will be on

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.074.png) 

1. Execute the script
1. In the reports section, the ‘Bandage’ symbol will indicate that healer was used for the script
   1. **Note**: Script must pass in order for healer to have a baseline

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.075.png) 
### **Usage**
When element locators change, healer will return the correct element locator value which would correctly navigate through the application as it normally does. To show this, we will change an element locator value in the script to an incorrect value. 

1. Navigate back into the test script and change the element value to an incorrect one.
   1. Example: com.ctclogindemo:id/et\_username -> com.ctclogindemo:id/et\_user

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.076.png)

1. Execute run the script with the healer option turned on
1. Go inside the failed test
1. Click on the ‘Healer’ button in the Actions section

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.077.png) 

1. The Healer Response shows the correct value of the element

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.078.png)

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

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.079.png) 
### **Usage**

1. Run the script with either ‘Dry Run’ or ‘Execute Run’
1. Enable the ‘OTP’ option

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.080.png)

1. While the script is running, click on the ‘Verify OTP’ button. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.081.png) 

1. Enter the one-time password

` `![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.082.png)

1. Click the ‘green checkmark’ button

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.083.png)

1. When done successfully, you will see the success message as shown below

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.084.png)
## **Marking Script for Component Importing**
Qyrus allows users to reuse test scripts across multiple different solutions. Users are able to move test scripts from the Mobility over to Component Testing pretty easily. 
### **Prerequisites**
- Knowledge in Mobility 
- Knowledge in Component Testing 
- Tests to Import 
### **Usage**
1. Click on the ‘more options’ button for the script that you want to import

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.085.png)

1. ` `Click on ‘Mark As Component’ option

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.086.png)

1. When done correctly, the script will have this ‘Flag’ symbol

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.087.png) 

1. Go to Component Testing and click the “Import Scripts” button. 

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.088.png)

1. Then, select Mobility, whichever scripts to import, and click the “Import” button.

![](Aspose.Words.9669dacf-cbe9-43ca-9e35-18f0bd3278e7.089.png)
## **Using Dynamic Action Types**
Qyrus allows users to create variables during test execution and use those values dynamically to perform a wide variety of actions. For a full list of actions, visit our Action Types Documentation (link here). 
### **Perquisites**
- Created Project 
- Created Suite
- In progress of completing Script
### Setup
1. In your script, add a step with the action type ‘Create Variable’ and grab the text of the desired element

