## Qyrus Web testing Q-torial

Throughout this Q-torial, you will perform a series of web tests which will familiarize you with the Qyrus web testing platform. Follow the videos, and work through the provided worksheets to become more versed with the features and functionality that Qyrus web testing has to offer. Make sure to read the prior documentation and go through project creation and setup, if required, before begenning this tutorial. 

## Action types breakdown 

This video discusses the array of web action types, many of which we will be using throughout this course. Feel free to refer to the action types documentation page for more detailed explanations on each action type

<video width="600px" height="400px" border-style= "solid" border-size= 3px border-color= "#E98305" controls>
  <source src= "https://vidww.s3.us-east-2.amazonaws.com/Clip+8+-+worksheet+1.mp4">
</video>

## Introduction - Worksheet I 

<video width="600px" height="400px" controls>
  <source src="/_webrepo/_projectcreation/../../_media/_videos/_webVideos/Clip8-worksheet1.mp4" type="video/mp4">
</video>


### Description:

This worksheet acts as an introduction to some of our standard action types. In this test script, we will be launching the Qyrus web application and navigating into the resources tab. Two important things to note are, primarily, the launch step. This is the step that allows the web application to open, and will, more often than not, be the first step of any web script. Secondly, the resources tab. This a Qyrus hosted location for all who desire to learn more about the current testing processes and options, the future of test building and automation, AI and ML entering the testing space, and even Qyrus testing specifics. A great place to expand your knowledge on the past, present, and future of testing. We will end this introduction by navigating to the Qyrus practice testing domain where the remainder of this course will take place.

References: Qyrus documentation

Action types:

- Go to url
- Click
- scroll

### Step Key

<u> Step 1 </u>

Action type: Go to url

Description: Go to Qyrus web testing practice page

URL: [https://qyrus.com](https://qyrus.com/)

<u> Step 2 </u>

Action type: click

Description: click on resources tab

Data:

Index:

Locator: Xpath

Locator Value: //div[@id=&#39;button\_five&#39;]

<u> Step 3</u>

Action type: scroll

Description: scroll to center of the page

Data:

Index:

Locator: Xpath

Locator Value: //h2[contains(text(),&#39;Latest Posts&#39;)]

<u> Step 4 </u>

Action type: click

Description: click into desired article (Why automate mobile testing)

Data:

Index:

Locator: ??

Locator Value: //h3[contains(text(),&#39;WHY AUTOMATE MOBILE TESTING? - HOW TO SAVE MONEY &amp;&#39;)]

<u> Step 5 </u>

Action type: scroll

Description: scroll to directory tab

Data:

Index:

Locator: Xpath

Locator Value: //li[contains(text(),&#39;Directory&#39;)]

<u> Step 6 </u>

Action type: click

Description: click the Qyrus practice test page

Data:

Index:

Locator: Xpath

Locator Value: //a[contains(text(),&#39;Tutorial Page&#39;)]