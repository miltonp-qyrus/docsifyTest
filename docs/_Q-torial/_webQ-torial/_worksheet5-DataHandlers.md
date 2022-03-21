## Data Handlers - Worksheet V

<video width="600px" height="400px" controls>
  <source src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/Web/Clip12-worksheet5.mp4" type="video/mp4">
</video>

### Description:

In this test script we will sniff one layer deeper into the functionality of Qyrus. We will first be creating variables. An essential part of business processes, building a reoccurring string or value into a variable simplifies access and consistency to that data while minimizing human error. Secondly, it makes script building easy as anytime the data needs to be accessed you can simply use the &#39;data handler&#39; action.

Attempt the worksheet using simply the descriptions and hints provided in the steps, but as always there will be a step key provided if necessary.

References: Qyrus documentation

Action types:

- Go to url
- scroll
- Click
- Create Variable – Auth ID, grocery list item, nick name
- Refresh
- Set
- Select dropdown
- Dynamic verify
- Dynamic contains
- Dynamic set

<u> Step 1 </u>

Go to desired URL.

Hint: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

<u> Step 2 </u>

Scroll to submit button.

Hint: mouse event, scroll

<u> Step 3 </u>

Click submit button.

Hint: Mouse event, click

<u> Step 4 </u>

Click &#39;Generate Random Value button&#39;. The submit button prompts a modal, on the modal is where the prior button is located.

Hint: This step is almost identical to the prior with different locator values. Consider using the copy step function

<u> Step 5 </u>

Create a variable known as &#39;Authentication Key&#39;. within the variable store the key string. Note, Enter the variable name, the locator points to the variable content or value, and the property represents the variable type.

Hint: data handler, create variable

<u> Step 6 </u>

Refresh page

Hint: Windows Action, Refresh page

<u> Step 7 </u>

Create a variable for the type of tests list item, Smoke Test. Name the variable accordingly, in this case &#39;smoke test&#39;. Make sure the locator is pointing to the correct value for the list item.

<u> Step 8 </u>

Set the Nickname. For testing purposes we will use DarkKnight1!

Hint: Input Event, Set

<u> Step 9 </u>

Create variable for Nickname. Name the variable Nickname, and point it to the previously set value, in the nickname text box.

<u> Step 10 </u>

Refresh the page.

Hint: Windows, refresh

------------------------------------------------------- fill out form -----------------------------------------------------

<u> Step 11 </u>

Click oval for Favorite color. Under the Favorite color heading on the top left corner of the page, select your favorite color

Hint: Mouse event Click

<u> Step 12 </u>

Click checkbox for bread. Directly to the right of the Favorite color heading is the shopping list, click to add bread to the shopping list

Hint: refer to step 11

<u> Step 13 </u>

Verify the shopping cart entry is the same as the previously created variable using a dynamic contains. In the data column, select bread from the previously created variables. The locator should point to the shopping item (bread) inside the shopping cart.

Hint: data handler, dynamic contains

<u> Step 14 </u>

Scroll to Nickname. Using the scroll function scroll to the nickname title.

Hint: point the locator straight at the title

<u> Step 15 </u>

Dynamic set the nickname. There is a variable previously created for the nickname, make haste of the entry process. In the data column, select the desired variable (Nickname), and point the locator to the empty nick name, text box.

Hint: Data handlers, dynamic set

<u> Step 16 </u>

Set pets name. For test consistency enter InspectorGordon1!

Hint: input event, set

<u> Step 17 </u>

Select drop down, favorite animal.

Hint: mouse events, select dropdown

<u> Step 18 </u>

Click desired favorite animal, for test case consistency select dogbear

Hint:

<u> Step 19 </u>

Click the submit button

Hint: copy step 3

<u> Step 20 </u>

Click &#39;Generate Random Value&#39; button

Hint: copy step 4

<u> Step 21 </u>

Scroll to randomly generated value

Hint: copy step 5

<u> Step 22 </u>

Dynamic verify that the value previously stored as &#39;Authentication Key&#39; is not the same as the newly, and randomly, generated key. Make sure to add the authentication key variable in the data column, and point the locator at the new key upon most recent submittal of the form.

Hint: data handlers, dynamic verify is not

### Step key

<u> Step 1 </u>

Action type: Go to url

Description: Go to Qyrus web testing practice page

URL: [https://qyrus.com/qa-test-page](https://qyrus.com/qa-test-page)

<u> Step 2 </u>

Action type: scroll

Description: scroll to submit button

Data:

Index:

Locator: xpath

Locator Value: //label[@id=&#39;age-label&#39;]

<u> Step 3 </u>

Action type: click

Description: click the submit button

Data:

Index:

Locator: xpath

Locator Value://button[@id=&#39;submit-button&#39;]

<u> Step 4 </u>

Action type: click

Description: click the &#39;Generate Random Value&#39; button

Data:

Index:

Locator: xpath

Locator Value: //button[@id=&#39;generate-button&#39;]

<u> Step 5 </u>

Action type: create variable

Description: created variable called Authentication Key for Randomly generated value

Variable Name: Authentication Key

Index:

Locator: xpath

Locator Value: (//\*[@class=&quot;main&quot;])/p

Property: text

<u> Step 6 </u>

Action type: Refresh

Description: Refresh page

Index: 

Locator:

Locator Value:

<u> Step 7 </u>

Action type: create variable

Description: created variable called &#39;smoke test&#39; for Type of tests list item – Smoke Test

Variable Name: Smoke test

Index:

Locator: xpath

Locator Value: //body/app-root[1]/app-qa-test page[1]/div[1]/form[1]/div[1]/div[2]/div[1]/div[1]/label[1]

<u> Step 8 </u>

Action type: set

Description: set nickname

Data: DarkKnight1!

Index:

Locator: xpath

Locator Value: //input[@id=&#39;nickName&#39;]

<u> Step 9 </u>

Action type: create variable

Description: created variable called Nickname for content of Nickname text field

Variable Name: Nickname

Index:

Locator: xpath

Locator Value: //input[@id=&#39;nickName&#39;]

<u> Step 10 </u>

Action type: refresh

Description: refresh

Data:

Index:

Locator:

Locator Value:

<u> Step 11 </u>

Action type: click

Description: click favorite color as indicated to the left

Data:

Index:

Locator: xpath

Locator Value: //input[@id=&#39;blue&#39;]

<u> Step 12 </u>

Action type: click

Description: click checkbox to add smoke test to the testing types list

Data:

Index:

Locator: xpath

Locator Value: //input[@id=&#39;Smoke Test&#39;]

<u> Step 13 </u>

Action type: Dynamic contains

Description: Verify smoke test on the test types list matches our previously created variable

Data: Smoke test

Index:

Locator: xpath

Locator Value: //p[@id=&#39;smoke-list-item&#39;]

<u> Step 14 </u>

Action type: scroll

Description: scroll to Nickname header

Data:

Index:

Locator: xpath

Locator Value: //input[@id=&#39;nickName&#39;]

<u> Step 15 </u>

Action type: Dynamic set

Description: Set the Nickname, using the previously created variable

Data: Nickname

Index:

Locator: xpath

Locator Value: //input[@id=&#39;nickName&#39;]

<u> Step 16 </u>

Action type: set

Description: set pets name

Data: InspectorGordon1!

Index:

Locator: xpath

Locator Value: //input[@id=&#39;petName&#39;]

<u> Step 17 </u>

Action type: click

Description: click dropdown arrow

Data:

Index:

Locator: Xpath

Locator Value: //select[@id=&#39;animal&#39;]

<u> Step 18 </u>

Action type: click

Description: click desired animal -dogbear

Data:

Index:

Locator: Xpath

Locator Value: //option[contains(text(),&#39;Llama&#39;)]

<u> Step 19 </u>

Action type: click

Description: click Enter or Submit

Data:

Index:

Locator: Xpath

Locator Value: //button[@id=&#39;submit-button&#39;]

<u> Step 20 </u>

Action type: click

Description: click the &#39;Generate Random Value&#39; button

Data:

Index:

Locator: ??

Locator Value: //button[@id=&#39;generate-button&#39;]

<u> Step 21 </u>

Action type: Dynamic verify Is Not

Description: Verify the Randomly generated value against the previously saved authentication value to make sure they differ.

Data: Authentication Key

Index:

Locator: xpath

Locator Value: (//\*[@class=&quot;main&quot;])/p