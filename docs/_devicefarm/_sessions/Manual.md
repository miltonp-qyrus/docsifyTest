<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Device Farm</h1>

# Sessions
## Manual Testing<!-- {docsify-ignore} --> 
Interactively test and debug mobile applications that use development and testing environments. Gesture, swipe, interact, and further actions can be performed with devices in real time, directly from your web browser.

**Note:** User can always enable element explorer to ease their testing needs, it can help determine and identify the elements accurately.

### Prerequisite:
- Having a project created
- Uploading an application file

### Creating a Manual Session:
1. Under Projects, click on “Sessions” for your project

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.013.png)

2. Click on “New Session”

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.014.png)

3. Choose a device from the list

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.015.png)

4. Enter a “Session Name”

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.016.png)

5. Choose the application to test from the dropdown list

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.017.png)

6. Click “Start Session”

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.018.png)
### Navigation Bar:
Once a manual session is created, next to the device there is a control bar that has various actions that can be used. ![](Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.019.png)

**Note:** Some of these actions will be dependent on the operating system.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.020.png) Power on and off the device.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.021.png) Increase the volume on the device.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.022.png) Decrease the volume on the device.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.023.png) Navigate back to the previous screen.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.024.png) Navigate back to the main screen.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.025.png) Overview button that will show all the open applications on an android device.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.026.png) Take a screenshot of the screen. This will be saved to the local device.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.027.png) When something needs to be typed, press the keyboard rather than tapping on the alphanumeric keys on the screen.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.024.png) Invoke a call on the current device.

**Note:** This is call interrupt that will simulate a call being received on the device when testing an application.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.028.png) Invoke a text message to be sent to the device. 

**Note:** This is text interrupt that will simulate a text message being received on the device when testing an application.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.029.png) Lock the device. 

**Note:** This action is only displayed when using iOS devices.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.030.png) Unlock the device. 

**Note:** This action is only displayed when using iOS devices.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.031.png) This button will end the current session that is running. All of the actions from this session will be recorded and displayed under the reports.
### Device Logs:
A dump of system messages being logged. It provides the ability to track, check app activity and monitor from the moment the device is connected. This includes traces if the device throws an error. 

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.032.png)

On the top right of the logs, there are a few actions that can be performed.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.033.png)

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.022.png)Clear the logs for the existing session.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.034.png) The logs can be paused/locked. The reports will continue to generate even with the screen locked. The same icon can be used to unlock as well.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.035.png)When no logs are being generated, this can be used to refresh the logs without having to end the session.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.036.png)This will disconnect the logs if you do not want to view the logs in parallel during a session.

### Network Shaping:
Network shaping allows you to simulate different network conditions. Using network profiles, you can control the bandwidth, latency and packet loss of the network connection. This allows you to test functionalities of your apps that are dependent on network conditions.

![](../../../_media/_devicefarmimgs/Aspose.Words.a5ba35ee-3494-4720-8f8c-7cedbeae1812.037.png)

**Note:** Here you will be able to use custom network profiles. To see how to make one, go to project setup and network profiles. 