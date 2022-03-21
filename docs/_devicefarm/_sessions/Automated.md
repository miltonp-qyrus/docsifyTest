<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Device Farm</h1>

# Sessions

## Automated Testing<!-- {docsify-ignore} --> 
Already have tests built? We can run them using our devices with automation testing and provide video reporting, device vitals and Appium logs.
### Prerequisite:
- Having a project created
- Uploading an application file
### Creating an Automation Session:
1. Under Projects, click on “Sessions” for your project

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.013.png">

2. Click on the “Automation” tab

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.038.png">

3. Click on “Quick Setup Guide”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.039.png">

4. Choose a device to execute the test on
   1. Sort the devices by region, platform, or search for a specific device.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.040.png">

5. Select an application file to test
   1. Android
      1. Choose the “APK File”
      1. Choose the “App Activity”
   1. iOS
      1. Choose the “IPA File”
6. Click “Generate JSON”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.041.png">

7. Click “Copy JSON”

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.042.png">

**Note:** This is the JSON generated for the device and application that you picked. This will be copied in to your testing framework

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.043.png">

**Note:** This is the server information that will be added to the testing framework.

8. To run the tests on your framework using the Qyrus infrastructure, provide the desired capabilities in to the testing framework.
   1. Below is a link to view the formatting for other languages supported by Appium.
      1. <http://appium.io/docs/en/writing-running-appium/web/mobile-web/>

**Note:** This is an example using java and an iOS device.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.044.png">

**Note:** This is an example using java and an Android device.

<img src="https://dmdug58z0ycm2.cloudfront.net/production/pub-site/images/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.045.png">

9. After adding the server and device capabilities, run the test.

**Note:** When the test is executing you can view a live preview under the “Automation” tab. When the session is complete, click on “View Details” to view the reports.