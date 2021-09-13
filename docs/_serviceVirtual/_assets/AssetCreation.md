<h1 style="text-align: center; text-decoration:underline; font-weight: bold;">Service Virtualization</h1>

# Assets

## Asset Creation<!-- {docsify-ignore} --> 

We need an asset folder to keep track of all the different Assets or data for our RESTFUL APIs in one folder.

When creating a new Asset you this is where you are given the choice to import a **Swagger URL** or manually create your own. 

![](../../../_media/_serviceImgs/Aspose.Words.3902605c-4b30-4b77-afc9-c9fa959b2fd5.006.png)

This is where you fill out the form with necessary information that relates with the project i.e:

1. **Asset Name:** Any given name that generalizes your Asset
1. **Asset Description:** Brief explanation on what the Asset does
1. **Select Methods:** Choice of verbose for your asset 
   1. POST – Create data
   1. PUT – Update/Replace data
   1. PATCH – Update/Modify data 
   1. GET – Read data
1. **Context Path:** A path that will hold your assets in the end of the URL
1. **Body Type:** What type of input you will give for your response
   1. JSON – Javascript object annotation
   1. Text – String annotation
   1. XML - eXtensible Markup Language
1. **Header:** this is where you will create access to the API call, through apikey or authentication
1. **Requests:** you will give **status codes** that will give different Reponses, for now it should be **200** with a **delay of 0** for the purpose of simple testing
1. **Response:** this is where you will give a JSON body to test the request was successful, I.e. 

*{"patient": {"firstName": "John","lastName": "Doe","id": 1}}*

9. **Query Parameter:** this is where you fill out the parameter that will call an object with its unique path out of all the data in its response, I.e: /test/user/**id/1
![](../../../_media/_serviceImgs/Aspose.Words.3902605c-4b30-4b77-afc9-c9fa959b2fd5.007.png)**