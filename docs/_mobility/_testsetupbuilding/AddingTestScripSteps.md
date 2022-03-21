<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Mobility</h1>

# Test Setup & Building

## Adding Test Script Steps <!-- {docsify-ignore} --> 

### Prerequisites
- Created Project 
- Created Suite
- Connected to Device Pool

### Adding Steps
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

## Build Steps

<video width="600px" height="400px" controls>
  <source src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/Mobile/Clip4-CreateSteps.mp4" type="video/mp4">
</video>
<!-- create steps video -->