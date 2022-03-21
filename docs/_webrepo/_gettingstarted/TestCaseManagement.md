<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Web Repository</h1>


# Getting Started
## Test Case Management <!-- {docsify-ignore} --> 
In this section what will be discussed is test case management using Sprints, Test Lab, versioning, and branching scripts. This gives users the opportunity to edit their scripts based on their needs.

### Versioning Scripts
Versioning scripts allows the user to further customize their test script for different uses. It also serves as a restore point, should the user want to revert their test to a certain version.
1. Under the ‘Dry Runs’ menu tab, navigate to the ‘Versions’ tab on the blue navigation menu to the right.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_1.png">

2. Make sure your tests are saved, and click ‘Create Restore Point’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_2.png">

3. Conversely, the ‘Create Restore Point’ button can be found on the ‘Save’ tab

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_3.png">

4. Enter a ‘Restore Point Name’
5. Enter a ‘Restore Point Description’
6. Click ‘Create Restore Point’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_4.png">

7. Verify Restoration point
   - Upon creation the user should automatically be navigated to the ‘Versions’ tab 
   - The recently created restore point will be shown under the ‘Restore Point’ subheading

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_5.png">

8. Copy the steps on following test scripts and save

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_6.png">

9. Navigate once again to the previously created ‘Restoration’ in the ‘Versions’ tab of the blue navigation menu on the right

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_7.png">

10. Click the red icon on the right to ‘Reset’
11. Click ‘Yes’ on the pop-up window
   - Upon Reset, note that the test script is now restored to the original version prior to the added and saved test steps
   - The feature works conversely as well. If steps were deleted after a ‘Version’ was created those steps would be present upon a ‘Restore’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Versioning_8.png">

### Creating Sprints
Sprints allow the user to sync up test cycles with live sprints being ran by teams.
1. Click ‘Create Sprint’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Sprint.png">

2. Enter a ‘Sprint Name’
3. Enter a ‘Sprint Objective’
4. Enter a ‘Sprint Start & End Date’
5. Click the ‘Create Sprint’ button

### Importing Scripts into Sprint/Test Lab
Importing scripts into these other sections allows test execution of those scripts in the sections.
1. Click ‘Import Test Script’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Import_Script_1.png">

2. Click ‘Import Test Script’ button 
3. Upon Navigation to the ‘Import Scripts’ page there are a few things to note:
   1. Displayed on the left half of the screen are previously created modules within the test repository
   2. On the right-hand side is the created previously created test suite to which test scripts must be added
4. Click on the desired module

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Import_Script_2.png">

5. Select Desired Test Scripts and ‘Push to Suite’, options include:
   1. Employ drag and drop
   2. Use the blue ‘Plus’ icon found next to every test script
   3. Select each desired script using the check boxes on the left of the name and click the ‘Push to Suite’ button
6. Once Selected click ‘Save to Suite’ button

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Import_Script_3.png">

7. Upon navigation back to the ‘Test Scripts’ page, verify that the desired test script has been imported
   - The script should show up on the test scripts table in the center of the screen alongside a numerical indicator on the ‘Test Scripts’ heading

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Import_Script_4.png">

### Starting the Sprint
Starting the sprint allows users to sync the sprint with test cycles.
1. From the ‘Test Scripts’ page click the ‘Start Sprint’ button located on the top right-hand corner of the screen

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Start_Sprint.png">

2. When prompted with a pop-up, verify the sprint details and click the ‘Start Sprint’ button
3. Navigated back to the ‘Test Scripts’ page note that the sprint is active because the previously selected ‘Start Sprint’ button now displays ‘Finish Sprint’.  

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Start_Sprint_2.png">


### Creating Scheduled Runs
Scheduled runs in Test Lab allow users to run test scripts at designated times.
The first step the user will want to do is to click onto ‘Test Lab’.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Schedule_Run_1.png">

From here, the user will have two options for scheduling a run

1. If a user wants to schedule a run for more than one script, the user can select the scripts they want to run by clicking on the checkbox associated with that script. After all the desired scripts have been selected, click on ‘Execute’ and then ‘Execute Test’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Schedule_Run_2.png">

2. The user can also navigate into their desired script by clicking on the right arrow associated with that script. Then, the user can select ‘Execute’ and ‘Execute Test’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Schedule_Run_3.png">

After clicking ‘Execute Test’, the user will be brought to the ‘Select Brower’ Page. The user can select between Google Chrome, Mozilla Firefox and Internet Explorer. They can choose more than one option.

After selecting a browser, click on ‘Schedule Test’, which is located on the black panel to the left. The user will then be presented with the options of doing a one-time scheduled test and/or repeat a scheduled test. The user then clicks whichever option is desired (Make sure there is a green checkbox next to your chosen option).

3. For a one-time scheduled test, the user must select a time, time zone and a date

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Schedule_Run_4.png">

4. For a repeated schedule test the user has the option to select weekly, daily, and/or hourly. For the weekly option the user selects the week, then selects the time, time zone and date. For the daily and hourly option, the user selects the time, time zone and date.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Create_Schedule_Run_5.png">

Click ‘Schedule Test’

### Viewing Scheduled Runs
Viewing scheduled runs are similar to viewing regular test runs.
There are two ways to view your scheduled runs:

1. Navigate into a project and go under ‘Analysis’
   1. Under Analysis the user will see Test Lab
   2. Click ‘Scheduled Runs’

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/View_Schedule_Run_1.png">

2. Navigate into a project and click the hamburger icon in the top right corner
   1. Under ‘Reports’ click on ‘Scheduled Runs’

   <img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/View_Schedule_Run_2.png">
   
   After clicking on ‘Scheduled Runs’, the user will be able:
   2. View All Scheduled Runs
   3. View All Schedule Information
   4. Pause Scheduled Test
   5. Delete Scheduled Test

### Branching
Users can choose to branch their tests that they hold in Test Lab or in the Sprints section to different tests. This allows for the user to have a higher degree of test case management, allowing for different versions of a script to exist based on the needs of the Sprint or some other requirement.

To branch, first open up a test script located in the Sprints section or Test Lab. Edit that test script by adding some additional step(s). Once ready, click the save button and then the “Save as different test script” option as seen in the screenshot below.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Branch_1.png">

A new dialog box will open prompting the user to enter in a new name, objective, and any tags if desired. Once the user clicks save, they can navigate to the specified module (in this case GOOG) in Test Repository in order to view their new script as seen in the screenshot below.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Branch_2.png">

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_webimages/Branch_3.png">
