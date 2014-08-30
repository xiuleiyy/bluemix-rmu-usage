bluemix-rmu-usage
=================

This is used to show the usage of Runtime Management Utility function in IBM Bluemix


Set Trace and Generate Dump for Java application running on Bluemix -- Rumtime Management Utility(RMU) function
================================================================================================================

Trace and Dump are very useful materials to make problem determination. Bluemix support to set trace and generate dump file during the application is running. In this Blog, I will show you step by step to how to use this function to set trace and generate dump files for your Java application.

1. Log in Bluemix UI
Log in Bluemix UI with your Bluemix ID, if you don't have Bluemix ID yet, you need to register first.

2. Create an test application and set trace/generate dumpfiles
We will use to Bluemix UI to create an Java application, then will show to how set trace and generate dump files for this application.
After log in Bluemix UI( https://ace.ng.bluemix.net/?cm_mmc=developerWorks-_-dW%20CloudOE%20content-_-cl-oauthregistry-app-_-article ), click "DASHBOARD" 

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828203358.png)

Click "CREATE AN APP" to create a Java application 

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828203606.png)

Select "Liberty for Java" to create a Java application

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828203713.png)

Set the application name to "Test-RMU", and click "Create". You need to set any another name different with this one.

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828203825.png)

After click "Create", the application will be created for you and the application's Overview page will show up. 
 
From the "Overview" page, click "Runtime" to go into the Runtime detail page

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828204146.png)

In the Runtime page, find the Instance Details section, and select the instance which you want to set trace or generate dump files. Form example:

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828204320.png)

Then Click the "ACTIONS" button, to choose "TRACE" or "DUMP"

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828204545.png)

Click "TRACE" first, take a look below pictures, you can set trace in the red region for this this application and click "SUBMIT TRACE" to save your action.

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828204753.png)

After set trace, we choose to click "DUMP" to generate dump files for this application.

![image](https://raw.githubusercontent.com/acostry/bluemix-rmu-usage/master/bluemix-rmu-usage/rmu/20140828205012.png)

From above pictures, select which type of dump you want to generate and click "GENERATE DUMP", then a dump files will be generated and listed in the "File" section, then you can download the dump files to your local machine to make a analysis.
