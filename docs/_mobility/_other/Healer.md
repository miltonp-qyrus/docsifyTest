<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Mobility</h1>

# Other 
## Using Healer <!-- {docsify-ignore} --> 
Healer is an advanced AI tool that users can enable before they execute their test scripts. It helps prevent test flakiness and brittleness. Healer gives a response on a failing test that provides the user with the element information needed in order to fix their broken test. Below will be an example of running tests with Healer enabled. 

### Prerequisites
- Created Project 
- Created Suite
- Created Script
- Knowledge on how to run scripts
- Knowledge on how to look at reports

### Setup

1. Navigate inside your completed script. We will use this one step script as an example

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images//_mobileimages/Healer_1.png">

2. Execute run the script
3. Click the toggle to turn healer on or off. At default, healer will be on

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images//_mobileimages/Healer_2.png">

4. Execute the script
5. In the reports section, the ‘Bandage’ symbol will indicate that healer was used for the script
   - **Note**: Script must pass in order for healer to have a baseline

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_3.png">

### Usage
When element locators change, healer will return the correct element locator value which would correctly navigate through the application as it normally does. To show this, we will change an element locator value in the script to an incorrect value. 

1. Navigate back into the test script and change the element value to an incorrect one.
   * Example: com.ctclogindemo:id/et\_username -> com.ctclogindemo:id/et\_user

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_4.png">

2. Execute run the script with the healer option turned on
3. Go inside the failed test
4. Click on the ‘Healer’ button in the Actions section

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_5.png">

5. The Healer Response shows the correct value of the element

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_mobileimages/Healer_6.png">

6. Replace the element locator value in the script with this value in order for the script to correctly navigate through the application

## Healer ##

<video width="600px" height="400px" controls>
  <source src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/Mobile/Clip13-Healer.mp4" type="video/mp4">
</video>
