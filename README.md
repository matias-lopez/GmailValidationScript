# GVS - GmailValidationScript



This Apps Script extension allows automating several office tasks, through Gmail’s elements manipulation, making different kinds of requests to its API, analyzing and responding to incoming emails and extracting their attachments to validate them. The script also uses a labelling system in order to identify previously processed threads and classify them according to validation results.

Given that the project was developed for a specific real-world context, the aim of sharing this code is to help beginners determine Google Apps Scripts platform’s scope and flexibility, not only by understanding and getting involved with it, but also by working with JavaScript standard built-in objects, methods and properties. 

I would also like to mention that even though the code is properly commented, these comments are written in Spanish, so feel free to contact me on [LinkedIn](https://www.linkedin.com/in/matias-lopez-revoreda/) if you have any questions.




## GVS - Step by step installation and configuration guide:


* Access the relevant Google Drive account.
* If the service is not installed: go to Connect more apps and search for Apps Scripts.
* Install the service by clicking on the Connect button.
* New > More > Google Apps Script to open editor.
* To enter the Developer Hub (console), just paste: https://script.google.com/home on the navigation bar.
* Creating and running a Trigger: from the console, go to My Projects and select the desired project.
* Then Project Details > Triggers > Add Trigger.
* A new window will open where configuration settings can be applied.
* In this project context, a time-driven trigger with a 5 minutes timer was executed on the main function (validate).
