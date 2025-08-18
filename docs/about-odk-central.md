# ODK Ecosystem

ODK consists of :

ODK Central Server  
ODK Projects  
Forms (Blank)  
Submissions (Data from Forms)  
ODK Collect App  
Blank Forms  
Finalized Forms with Data  

ODK Central is the hub that controls the ODK Ecosystem. ODK Central manages users, forms, permissions and data flow. Forms are created in a computer using a template in Excel or Google Sheets using the XLSForm Standard. These XLSForms are are uploaded to ODK Central.  ODK Collect connects to ODK Central Projects and Forms using the QR Codes. Forms are then downloaded into the ODK Collect App as blank forms.  Data collected using these Forms are processed within ODK Collect and sent back to ODK Central.  These are called Submissions.  These Submissions can then be exported as data for analysis. 

<img width="300" height="672" alt="collect_multiple" src="/assets/images/diagram_odk_collect.png" />

# ODK Central 
ODK Central is installed on a Linux Server with the latest Ubuntu version.  A study should have a dedicated server.  ODK Central can contain many ODK Projects, and each Project can have many Forms.  ODK Central can have many Users and each User can be assigned to any Project with specific Roles.  The Roles define what they can do within that Project.

Further below is a table taken from ODK Docs.  This is a comprehensive table of functions for each Web User Role for ODK Central. Critical differences are highlighted below and current issues and limitations are discussed for operational action.

The Administrator  is assigned at the ODK Central level with site-wide privileges across Projects.   The Administrator can do all roles of the Project Manager, the Project Viewer and the the Data Collector.  In addition, only the Administrator can create Projects and Create and Manage Web Users. 

Note that in ODK Central V2025, Administrators can perform functions on Submissions and there is no easy way to change that.   It would be good practice to ensure that an Administrator log-in with different credentials if they are performing project specific roles (eg as a Project Manager).  

The Project Manager can perform all functions except Create Projects and Create and Manage Web Users.  The critical roles are Form Creation and Management, Entity Creation and Updating, Creation and Management of App Users, Creation and editing of Submissions.  Essentially, the Project Manager fulfills a data manager's role. The Project Manager can edit Submissions.

The Project Viewer has a very focused function.  They can See and List Forms, Comment on Submissions, Download Submissions, Connect with Odata.  Project Viewers cannot edit.

The Web Data Collector cannot edit, but can create submissions.

# Overview of ODK Collect

The ODK Collect App is designed to Download Project Settings from ODK Central.  Then, within that project, the user can download Specific Forms. ODK Collect Settings govern how it functions and handles data.  Settings require decisions to be made by the Project Manager.  

Here are some illustrations of settings focused on how forms are sent.

<img width="300" height="672" alt="collect_multiple" src="/assets/images/diagram_odk_collect_panels.png" />

In **Panel A**, you will see that data collected is entered in Blank Forms.  When these forms are Saved, they are sent to Drafts.  When Draft Form Finalized, they are sent to Ready to Send.  When the Ready to Send Forms are Sent, data is sent to Sent Forms.  It is important to note that data is still in the Android Device and may have to be manually deleted.  

The lesson here is that:
1.  Data not sent to ODK Central can get lost and that is lost forever.

2  Data that remains in the Sent Folder may risk a privacy breach.

In **Panel B**, the **Auto-Send setting** is enabled.  ODK Collect sends the data to ODK Central and within Collect, data goes directly to Sent.  Data passes through, but does not remain in Ready to Send.  Data still has to be manually deleted.  This setting does not require manual sending by the data collector ensuring that data is always securely in ODK Central.

In **Panel C**, **Auto-delete upon sending** is enabled.  This means that upon sending, the data that was sent disappears from the device immediately.  

Project Managers have to decide which setting they want to have. 