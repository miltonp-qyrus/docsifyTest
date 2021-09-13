<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">API Monitoring</h1>

# Adding Monitored APIs to a Collection
## Monitored API Form  {docsify-ignore}  

This guide shows how to build a basic Monitored API. See the Knowledge Base for additional information on how add additional options to a monitored API.

![](../../../_media/_apiMonitoringImgs/Aspose.Words.752ed8cd-8f62-4f5e-a43d-3af5acb4dbd1.009.png) 

A basic Monitored API requires a few settings:

- API Type: REST, SOAP, GRAPHQL

![](../../../_media/_apiMonitoringImgs/Aspose.Words.752ed8cd-8f62-4f5e-a43d-3af5acb4dbd1.0010.png) 

- Request Type: GET, POST, PUT, DELETE, PATCH

![](../../../_media/_apiMonitoringImgs/Aspose.Words.752ed8cd-8f62-4f5e-a43d-3af5acb4dbd1.0011.png) 

- Monitor Name: A name for the monitored API

![](../../../_media/_apiMonitoringImgs/Aspose.Words.752ed8cd-8f62-4f5e-a43d-3af5acb4dbd1.0012.png) 

**URL:** The exact URL to the API you will be testing. Include all path and query parameters.

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.013.png) 

- Time Period: The time interval between calls to your API. The minimum is 10 minutes, but can be set in minutes, hours or days.

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.014.png)

- Single Response Time Threshold: If an API call takes longer than the threshold set here, an alert can be sent to the email that was entered when setting up the collection

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.015.png) 

**Average Response Time Threshold:** If the average response time of a designated number of calls goes beyond the threshold set here, an alert can be sent to the email that was entered when setting up the collection

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.016.png) 

**Rolling Average:** The value set here determines the number of API calls that are used to determine the current average response time value

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.017.png) 

**Expected Status Code:** This is the status code the API must return in order for the API call to be considered successful

![](../../../_media/_apiMonitoringImgs/Aspose.Words.55549bf5-5cbd-4794-a8ae-ae7657cb7b04.017.png) 