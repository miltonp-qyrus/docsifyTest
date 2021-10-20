## Login Script – Worksheet II

<video width="600px" height="400px" controls>
  <source src="/_webrepo/_projectcreation/../../_media/_videos/_webVideos/Clip9-worksheet2.mp4" type="video/mp4">
</video>


### Description:

In this test you will perform a series of actions on the Qyrus web testing practice domain. The actions are aimed to simulate those most commonly found in login test script. With regards to testing most every web application, the login process is one of the most common and important flows. Proper execution and lack there-of, of a login script is critical in regards to proper platform usage, and platform safety. Today, we will be using Qyrus to create an automated web test simulating a proper login.

References: Qyrus documentation

Action types:

- Go to url
- Click
- Set
- Wait

<u> Step 1 </u>

Action type: Go to url

Description: Go to Qyrus web testing practice page

URL: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

<u> Step 2 </u>

Action type: click

Description: click the nickname text box

Data:

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;nickName&#39;]

<u> Step 3 </u>

Action type: set

Description: Enter nickname

Data: The Dark Knight

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;nickName&#39;]

Now it is your turn. To complete the script there are a few steps that remain. Taking what you&#39;ve learned thus far complete the steps described below. Try your best to complete the steps using simply the descriptions and hints, but if necessary, the answer key will be provided as well.

<u> Step 4 </u>

Set the pets name. The pets name can be any characters or name of your choosing, or InspectorGordon1!

Hint: as a check, refer to the fields in step 3.

<u> Step 5 </u>

Now we need to select our favorite animal using the dropdown menu. The first part of this step is to Click the dropdown arrow. Make sure to select the right identifier for the dropdown arrow.

Hint: as a check, refer to the fields in step 2.

<u> Step 6 </u>

Lastly click your favorite animal from the list provided. If you have no preference a safe choice is always dogbear.

Hint: as a check, refer to the fields in step 2.

<u> Step 7 </u>

Now that everything is entered, we would like to click submit to enter the data. Find the submit button at the end of the form and click it.

Hint: as a check, refer to the fields in step 2.

<u> Step 8 </u>

After hitting submit there is a pop-up that should display on the screen. A very common practice, and a handy action type is the wait. In this step we will wait 2 seconds, allowing the video to end smoothly and make sure all end processes are functional before termination

Hint: Action type, windows, wait.

### Steps Key

<u> Step 4 </u>

Action type: set

Description: set the pets name

Data: InspectorGordon1!

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;petName&#39;]

<u> Step 5 </u>

Action type: click

Description: click dropdown arrow

Data:

Index:

Locator: Xpath

Locator Value: //select[@id=&#39;animal&#39;]

<u> Step 6 </u>

Action type: click

Description: click desired animal

Data:

Index:

Locator: Xpath

Locator Value: //option[contains(text(),&#39;Llama&#39;)]

<u> Step 7 </u>

Action type: click

Description: click Enter or Submit

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;submit-button&#39;]

<u> Step 8 </u>

Action type: Wait

Description: Wait 2 seconds

Duration: 2