## Forms & Verifiers - Worksheet IV

<video width="600px" height="600px" controls>
  <source src="/_webrepo/_projectcreation/../../_media/_videos/_webVideos/Clip11-worksheet4.mp4" type="video/mp4">
</video>

Forms and Verifiers – Worksheet IV

### Description:

In this test script we will simulate testing form functionality. Subscription, Login, create a profile, generate a post, web applications rely on forms for countless processes including and especially the prior listed. Forms often including sensitive and desired information and often act as a barrier for entry for many applications, and therefore proper functionality is essential and lack there-of could be very detrimental. Beyond form functionality we will also be introduced to different verifiers that Qyrus offers and their implementation.

Attempt the worksheet using simply the descriptions and hints provided in the steps, but as always there will be a step key provided if necessary.

References: Qyrus documentation

Action types:

- Go to url
- set
- Select dropdown
- Click
- Verify text
- Refresh
- Verify url
- Verify is blank

Step 1

Go to desired URL.

Hint: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

Step 2

Set nickname. The nickname can be any desired characters or The Dark Knight, to follow along with the test.

Hint: refer to login script

Step 3

Set the pets name. The pets name can be any characters or name of your choosing, or InspectorGordon1!

Hint: refer to login script

Step 4

select your favorite animal using the dropdown menu. The first part of this step is to Click the dropdown arrow. Make sure to select the right identifier for the dropdown arrow.

Hint: refer to login script

Step 5

click dogbear as favorite animal.

Hint: refer to login script

Step 6

Verify text in the text box matches the selected animal. Make sure to fill every field, especially the data columb with the desired output. Make sure to verify the xpath is pointing to the proper location.

Hint: Action types, verifiers, verify text

Step 7

Refresh page.

Hint: Action types, windows, refresh

Step 8

Scroll to Nickname text box. Make sure to select the proper locator value depending on the desired scroll location

Hint: mouse event, scroll

Step 9

Verify the previously filled text boxes are now empty upon refresh. Verify is blank.

Hint: action types, verify, is blank.

### Step Key

Step 1

Action type: Go to url

Description: Go to Qyrus web testing practice page

URL: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

Step 2

Action type: set

Description: Enter nickname

Data: The Dark Knight

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;nickName&#39;]

Step 3

Action type: set

Description: set the pets name

Data: InspectorGordon1!

Index:

Locator: Xpath

Locator Value: //input[@id=&#39;petName&#39;]

Step 4

Action type: select dropdown

Description: select dropdown menu

Data:

Index:

Locator: Xpath

Locator Value: //select[@id=&#39;animal&#39;]

Step 5

Action type: click

Description: click desired animal

Data:

Index:

Locator: Xpath

Locator Value: //option[contains(text(),&#39;Dogbear&#39;)]

Step 6

Action type: verify text

Description: verify text populated is desired selection

Data: Dogbear

Index:

Locator: Xpath

Locator Value: //select[@id=&#39;animal&#39;]

Step 7

Action type: refresh

Description: refresh

Data:

Index:

Locator:

Locator Value:

Step 8

Action type: scroll

Description: scroll to Nickname header

Data:

Index:

Locator: Xpath

###### Locator value: //input[@id=&#39;nickName&#39;]

Step 9

Action type: is blank

Description: verify the text box is blank – post refresh

Data:

Index:

Locator: Xpath

###### Locator Value: //input[@id=&#39;nickName&#39;]