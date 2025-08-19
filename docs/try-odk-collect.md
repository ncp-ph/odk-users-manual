# Try ODK Collect

## Introduction
ODK Collect works with a server that connects securely with the ODK Collect to send and receive information.  \The server we use is called ODK Central.  ODK Central stores the blank survey forms that you will use in your study.  You will use ODK Collect to download these blank forms.  After entering data in these forms, you will then send the data back to the ODK Central which receives and stores the data you collected. If the data collector does not send the data in ODK Collect to ODK Central, the data is not stored in the server. If you lose your Android Device, data not sent will be lost. As a data collector, you will not have access to ODK Central, but it is important for you to understand how this works with ODK Collect.  

ODK Collect can be used offline to collect data.  However, you must sync with the server as frequently as possible, preferably daily before collecting data and at least once a day to sync your data with ODK Central.  Each project will have its own protocols.

## The Demo
You will connect to the Training Project using a QR Code and learn how to navigate ODK Collect Questions.  We will be using a Form called "All Question Types" created by ODK developers to demonstrate what ODK Collect can do.  It is recommended to try this form at least once so that you are familiar with all the question types you may encounter in your study.  For Project Managers, seeing the question types will also help you decide on form design.  

You will learn how to answer the most common question types enumerated below  
- Text  
- Numerical  
- Range  
- Date and Time  
- Select one  
- Select multi  
- Less frequently encounter question types:  
  - Image  
  - Media  
  - Geospatial  
  - List  

## Steps
- Step 1. Install ODK Collect [Follows these steps if you have not installed ODK Collect](/install-odk-collect.md)
- Step 2. Open ODK Collect
- Step 3. Select Configure with QR Code 
- Step 4. Scan this QR Code with ODK Collect  
<img width="300" height="672" alt="collect_signatures" src="/assets/images/qr_training_20250710.png" />
- Step 5. Inspect the Home Page of the Project  
  -Inspect the icons  
     - project icon on the top right  
     - Start New Form - after entering data here, you can save and it goes to drafts  
     - Drafts - these are not finalized and can be edited.  Once finalized they go to the next icon  
     - Ready to Send - these are finalized forms that can be sent  
     - Sent - sent forms may be found here  
     - Delete Form  
-  Step 6 In the Home Page, go to Start New Form  
  - Select All Question types Form  
     - You are now in the questionnaire  
     - Navigate the questionnaire by:  
       - Swiping left or right  
       - Using the Next Button  
       - Jumping  
         - Look for the Icon with 3 horizontal lines at the top.  When you select this icon, it will take you to a list of **groups of questions** which are shown as folders.  Select a folder to see a list of questions.  You can select a question  or navigate out of the folder by selecting the "go up" button shown by the upward pointing arrow.  
         - Auto Advance  
           - Go to **groups of questions**
           - Go to Select one question types group.  
           - Choose the Select one autoadvance question.    
           - Answer it.  After answering, Collect automatically advances.  
         - Required Questions  
           - Go to **groups of questions** and selects the Other question types.  
           - Choose Trigger.  This type of question prompts you to confirm something.  If you do not confirm, you cannot advance.  

     - There are around 100 question types.  Jump to the following question groups as these are the most frequently used : Text, Numerical, Range, Date & Time, Select one, Select Multi.
     - Learn to Save and Send
       - Go to the Jump Icon
       - At the bottom, you can Go to the End
       - At the end of the questionnaire, you are given the option to 
       - Send or
       - Save as Draft : Choose this for now.  This takes you back to the Home page and you will see that there are now submissions in the Draft folder.
       - Select Drafts
         - This will show all your saved drafts
         - Select any saved draft
         - Now, you can still answer more questions if you want because the form is still editable
         - Go to the End .  Here you will see the Send option.
         - Select Send.
        - The submission goes to Ready to Send and then to Sent.  Now you will see that submission in Sent.  It is now possible to still edit forms that have been Sent, but this has to be configure by the Project Manager.  

- Step 7 That is the end !  Exit ODK Collect  
Exit ODK Collect the way you you would any other App.  
It is important to do this so that ODK Collect is not accessible by anyone your device is left unattended.  

## Next Steps
* If you are an App User, you can stop here.
* If you have other roles, see the [Must Read Table](./index.md#must-read-table)