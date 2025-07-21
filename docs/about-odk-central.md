ODK consists of :

ODK Central Server
ODK Projects 
Forms (Blank)
Submissions (Data from Forms)
ODK Collect App
Blank Forms
Finalized Forms with Data

ODK Central is the hub that controls the ODK Ecosystem. ODK Central manages users, forms, permissions and data flow. XLSForms created in a computer are uploaded to ODK Central.  These forms are then downloaded into the ODK Collect App as blank forms.  Data collected using these Forms  are processed within ODK Collect and sent back to ODK Central.  These are called Submissions.  These Submissions can then be exported as data for analysis. 

ODK Central is installed on a Linux Server with the latest Ubuntu version.  A study should have a dedicated server.  ODK Central can contain many ODK Projects, and each Project can have many Forms.  ODK Central can have many Users and each User can be assigned to any Project with specific Roles.  The Roles define what they can do within that Project.

Further below is a table taken from ODK Docs.  This is a comprehensive table of functions for each Web User Role for ODK Central. Critical differences are highlighted below and current issues and limitations are discussed for operational action.

The Administrator  is assigned at the ODK Central level with site-wide privileges across Projects.   The Administrator can do all roles of the Project Manager, the Project Viewer and the the Data Collector.  In addition, only the Administrator can create Projects and Create and Manage Web Users. 

Note that in ODK Central V2025, Administrators can perform functions on Submissions and there is no easy way to change that.   It would be good practice to ensure that an Administrator log-in with different credentials if they are performing project specific roles (eg as a Project Manager).  

The Project Manager can perform all functions except Create Projects and Create and Manage Web Users.  The critical roles are Form Creation and Management, Entity Creation and Updating, Creation and Management of App Users, Creation and editing of Submissions.  Essentially, the Project Manager fulfills a data manager's role. The Project Manager can edit Submissions.

The Project Viewer has a very focused function.  They can See and List Forms, Comment on Submissions, Download Submissions, Connect with Odata.  Project Viewers cannot edit.

The Web Data Collector cannot edit, but can create submissions.
