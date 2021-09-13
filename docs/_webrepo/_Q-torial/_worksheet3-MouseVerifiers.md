## Mouse Events & Verifiers - Worksheet III

<video width="600px" height="600px" controls>
  <source src="/_webrepo/_projectcreation/../../_media/_videos/_webVideos/Clip15-Versioning.mp4" type="video/mp4">
</video>


### Description:

This script will be led by mouse events. As the mouse is the base control of any web application it is important to master all the different mouse events alongside their points of usage. Beyond this we will be going through an array of other actions that lead the list in most commonly used action types. Verifiers allow for the proper, and in depth exploration of elements as they are interacted with and therefore are an important part of the test building process. We will begin the discovery of verifiers in this worksheet, but further explore the options throughout the course.

Attempt the worksheet using simply the descriptions and hints provided in the steps, but as always there will be a step key provided if necessary.

References: Qyrus documentation

Action types:

- Click
- Double click
- Right click
- Wait for element
- Alert handler, ok
- Contains
- Element exists
- scroll
- Drag and drop
- Send keys

Step 1
Go to url

Hint: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

Step 2
Click the first &#39;Click Me&#39; button

Step 3

Create an alert handler for the pop-up display.

Hint: Alert handlers, &#39;ok&#39;

Step 4

Right click second &#39;Right click me&#39; button

Hint: mouse events, right click

Step 5

Create an alert handler for the pop-up display.

Hint: this step is identical to step 3, try using the copy function

Step 6

Double click third &#39;Double click me&#39; button

Hint: mouse events, double click

Step 7

Create an alert handler for the pop-up display.

Hint: once again use the copy function for efficiency

Step 8

Click a given testing type

Hint: we have moved on to a new part of the page, navigate to the testing types and select an item.

Step 9

Verify that the testing types list contains the previously selected item. Remember you have to verify against something so be sure to fill out the data field with the proper value or in this case, the desired testing type.

Step 10

Click a given item on the testing types

Hint: This step is almost identical to step 8, therefore copy, paste, and alter the step to your desires.

Step 11

Verify that the element selected is visible in the testing types list. Because you are only checking for the presence of the desired element, the data column we don&#39;t need to verify against anything and the data column is not necessary.

Hint: verifiers, is visible

Step 12

Navigate back to the buttons section, and click the final &#39;Click me (wait for element)&#39; button

Hint: refer to step 1 to click

Step 13

Wait for element. As the final click warrants a new page wait for the sample button display. It is important to note that you will first have to click the button, to find the xpath of the element you are waiting for.

Hint: The data column requires population for the element that we are waiting for, in this case the element is &#39;sample button&#39;

Step 14

Verify the sample button exists. Another streamlined verification because we are only making sure the element exists, there is nothing to verify against and therefore the data column is rendered unnecessary

Hint: verifiers, element exists.

Step 15

Scroll to the select Age header.

Hint: mouse event, scroll

Step 16

Drag and Drop desired age, using the slider. Remember you will have to input the sliders original position (from locator value, and the position to which you would like the slider to go (to locator value).

Hint: mouse event, drag and drop

Step 17

Click on text box for &#39;Age Value&#39;

Hint: mouse event, click

Step 18

Send keys. Using the keyboard type &#39;enter&#39; to submit the form rather than clicking the button.

Hint: the data column should contain the desired key on the keyboard, written in lower case.

### Step Key:

Step 1

Action type: Go to url

Description: Go to Qyrus web testing practice page

URL: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

Step 2

Action type: click

Description: click the first Click me button

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;click-button&#39;]

Step 3

Action type: Alert handler, Ok

Description: launch the Ok alert handler to get back to the testing screen

Data:

Index:

Locator:

Locator Value:

Step 4

Action type: right click

Description: right click the second click me button as indicated

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;right-click-button&#39;]

Step 5

Action type: Alert handler, Ok

Description: launch the Ok alert handler to get back to the testing screen

Data:

Index:

Locator:

Locator Value:

Step 6

Action type: double click

Description: double click the third click me button as indicated

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;dbl-click-button&#39;]

Step 7

Action type: Alert handler, Ok

Description: launch the Ok alert handler to get back to the testing screen

Data:

Index:

Locator:

Locator Value:

Step 8

Action type: click

Description: click a checkbox for a given testing type

Data:

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;Smoke Test&#39;]

Step 9

Action type: verify, contains

Description: verify that the Testing types list contains the desired element

Data: smoke

Index:

Locator: Xpath

Locator Value: //p[@id=&#39;smoke-list-item&#39;]

Step 10

Action type: click

Description: click a checkbox for another item into the testing types list

Data:

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;Integration Test&#39;]

Step 11

Action type: verify, is visible

Description: verify that the testing types list contains the desired element

Data:

Index:

Locator: Xpath

Locator Value: //p[@id=&#39;integration-list-item&#39;]

Step 12

Action type: click

Description: click the final click me button indicated wait for element

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;wait-button&#39;]

Step 13

Action type: wait for element

Description: make sure the test waits for the proceeding pop-up

Data: button-logo

Index:

Locator: Xpath

Locator Value: //img[@id=&#39;button-logo&#39;]

Step 14

Action type: verify, element exists

Description: verify that the sample button is existent on the page

Data:

Index:

Locator: Xpath

Locator Value: //img[@id=&#39;button-logo&#39;]

Step 15

Action type: scroll

Description: scroll to the Select Age header

Data:

Index:

Locator: Xpath

Locator Value: //label[@id=&#39;age-label&#39;]

Step 16

Action type: Drag and drop

Description: Drag and drop age

Data:

Index:

From Locator type: Xpath

From Locator Value: //body/app-root[1]/app-qa-test-page[1]/div[1]/form[1]/div[2]/mat-slider[1]/div[1]/div[3]

To Locator Type: Xpath

To Locator Value: //body/app-root[1]/app-qa-test-page[1]/div[1]/form[1]/div[2]/mat-slider[1]/div[1]/div[3]

Step 17

Action type: Click

Description: Click into the text box for Age Value field

Data:

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;age&#39;]

Step 18

Action type: send keys

Description: send enter key, to submit form rather than clicking the button

Data: enter

Index:

Locator:

Locator Value: