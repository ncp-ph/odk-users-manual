# Project Manager

The Project Manager (PM) Role is a critical control center for ODK Central.  Only the PM can Assign ODK Central Users to the Project with specific Roles.  Only the PM can create App Users.  Only the PM can create Forms and decide on access to the forms.  Only the PM can assign App Users to Forms.  Only the PM can enable encryption.  Only the PM can edit the data.  Only the PM can archive the project. The PM can perform tasks that cannot be undone (like deleting forms and data)  

Note that the Administrator can also do all of these, but none of the above are ODK Central Administrative Functions.  All of the Project Viewer (PV) roles can also be performed by the PM.  If you have an ODK Central User that you want to assign to see the data but not change the data, they should be given a PV role and not a PM role.  

When you log-in as a Project Manager, you will see your Home Page.  From the Home Page you can navigate to other parts of ODK Central that you have access to. 

# Project Manager Home Page

There are four sections:  

* A - ODK Central System and User   
    * The first dropdown shows the ODK Central Version and Links to ODK Docs and ODK Forum.  
    * The second dropdown is for language  
    * The third dropdown is the user profile and logging out.  
* B - Projects and Documentation
    * The first box shows the number of projects  
    * The second box is a link to ODK Docs  
    * The third box is a link to ODK Forum  
* C - News from ODK 
    * latest releases of ODK Central)
* D - Projects  
    * This lists the projects (in blue)
        * On the left side, you can see the Forms (file icon); Entity Lists (database icon); and Entities. 
        * On the right side, there are five columns that refer to data (Submissions or Entities)
            * Received Data
            * Data with Issues / Comments
            * Edited Data
            * Latest Modification
            * Total Data 
            * Received Data, Sissues and Edited date are collectively called "Review States" 
    * Clicking on a Project will take you to a [Project Page](#the-project-page)

# The Project Page

All of tasks of a Project Manager are accessible from the Project Page.  The tasks can be divided into tasks that are related to Users and Access; tasks related to Data; and tasks related to the Project.
There are 2 sections: 

* A - Tabs to Subsections 
    * [Forms](#form-subsection)
    * [Entities](#entities) 
    * [Project Roles]
    * [App Users](#assigning-app-users)
    * [Form Access](#form-access)
    * [Settings](#settings)
* B - Subsection Details  
    * This will be different for each subsection
    * Select each subsection above to see what you can in each subsection

## Form Subsection
The form subsection has 6 tabs.  This outline shows what the **Project Manager** can do in each hierarchical section.  In **[brackets and bold]** are ODK Users with lower permissions where this role is shared with.  This means that this action can be **delegated** 

* Forms
    * [Create New Forms](#how-to-create-a-new-form)
    * [Preview Forms]
    * Access Data (Submissions) in each Form
        * [Create New Submission]
        * View All Data with filtering options **[Project Viewer]**
        * View and Act on individual Submissions
            * View Submission Details **[Project Viewer]**
            * Comment on an individual Submission **[Project Viewer]**
            * [Delete an individual Submission]
            * [Edit an individual Submission]
            * [Change Review Status of an individual Submission]
        * Connect Data **[Project Viewer]**
        * Download Data **[Project Viewer]**
* Entity Lists
    * [Create New Entity Lists]
    * [Download Entities Data] **[Project Viewer]**
* Project Roles
* App Users
* Form Access
* Settings

shows an overview of Form Review States and Totals and **two specific actions**
* **Create New Form** Button
* List of Forms specific to Project
    * Columns for Review States, Last Modified Date and Total Submissions
    * Action Column - to **Preview a Form** 
        * Selecting this allows you to see what your Form looks like.
    
### How to Create a New Form
- From the Project Page, select the Forms tab
- Select "New" and a Create Form pop-up page will appear  
- Upload or drag a previously created XLSForm.  

### How to Delete a Form

- From the Project Page, select the Forms tab
- Select the Form you want to delete
- In the Form Page, select Settings tab
- In Settings, on the Right Side, you will find a Red "Delete This Form" Button

## Entities
 
In the Entities tab, you can Create an New Entity List, View Entities, Download Entities.

### How to Create a New Entity List
*  Choose New Entity
*  Enter a unique list name. 

### How to Create a New Entity

To be added. 

### How to Edit an Entity
In the Entities tab, you can Create an New Entity List, View Entities, Download Entities.
* To edit an entity, first select an Entity List.
* The select an entity within that list.
* Hover over the Actions column in the row of the entity you want to edit.  
* Choose edit (pen icon).
* Choosing More will take you to Entity details and an edit entity ink.
* Either  way, an edit pop-up window will show up.


### How to Delete an Entity

In the Entities tab, you can Create an New Entity List, View Entities, Download Entities.

* To delete an entity, first select an Entity List.
* The select an entity within that list.
* Hover over the Actions column in the row of the entity you want to delete.  
* Choose delete (trash icon).
* Choosing More will take you to Entity details and an delete entity ink.
* Either  way, an edit pop-up window will show up to ask you to confirm.

### Assigning Web Users to Projects

* Ask the Administrator to Create Web Users for your Project (provide e-mail address).
* As Project Manager go to Project > Project Roles Tab
* In the Search Box, place the exact email address.
* Select the User and Assign a Role

## App Users

In the App Users tab, all the tasks are unique to the **Project Manager and Administrator**.  There are two main tasks.  The first task is to **Create an App User**.  Once an App User is created, a QR Code is automatically generated  the QR Code must be treated like a password.  It should be sent securely to an App Users secure email.  Sharing QR Codes should be discouraged.  

The second task is to **Download the QR Code**.  This QR Code is unique for the App User for whom it was generated.  The Project Manager needs to have a system for filing and naming the QR Codes. 

The third task is that you may **Revoke Access** of an App User to the Project.  This means that the App User can no longer download forms or Submit Data.  

Below are steps for tasks specific to this tab:

### How to Create an App User

* In the App User tab, select the blue "Create an App User" Icon.  
* Provide a Display Name for the App User.  This can be used to Display App Users when they submit data using ODK Collect.  In a Submission, this will show up under "Submitted by".
* Click Create. 
* The User should now show up in the list of App Users in this tab and in the Form Access Tab.
* The next step would be to assign Forms to created App Users in the Form Access Tab.  

[Back to App Users](#app-users)

### How to Download an App User's QR Code for Distribution
* Decide on your QR Code naming protocol for the Project.
* In the App User tab, look for the User's Display Name.
* Under the "Configure Client" Column, click on the QR Code Icon or "See Code"
* In the pop-up window "Client Configuration Code", Right-click the QR Code.
* Select "Save Image As.."
* Save the QR Code based on your project's QR Code naming protocol. 
* The next step is to securely send the QR Code to each App User.  
    
[Back to App Users](#app-users)
    
### How to Revoke an App User's Access to the Project
* In the App User tab, look for the User's Display Name.
* Under the "Actions" Column, click on the Gear Icon.
* In the "Revoke User Access" pop-up window, you will be warned that **Action** cannot be undone**
* Select "Yes, Proceed".  

[Back to App Users](#app-users)

## Form Access

In the Forms Access tab, all the tasks are unique to the **Project Manager and Administrator**.  Briefly, the Form Access tab defines what you can do with the Form (Form States) and who among the App Users have access to the Form (Form Access) regardless of its State.  Note that even if the App User has Access to the Form, the Form States dictate what action the App User can do with that access.  

There are two main tasks.  The first task is to **set the Form State**.  This is where you can control whether the form can be downloaded by ODK Collect and whether you can still Submit Data to ODK Central from ODK Collect.  

The second task is to **set the Form Access**.  You  will see all your Forms as rows.  In the columns, you will see the Different App Users assigned to the Project. By default, a newly created App User cannot access any form.  **This is a feature, not a bug.**  This allows the Project Manager to provide granular access to Forms such that App Users can only access Forms explicitly assigned to them.  This way, ODK Central reduces the risk that newly created App Users have access to Forms that they are not supposed to access.  

There may also be situations when you would want to toggle access to Forms.  One scenario for this is that you may have a form that you want to test with a few App Users before scaling up. Another scenario is that you may want to suspend data entry from specific areas or App Users (For example, to stop recruitment).  

Below are steps for tasks specific to this tab:

### How to Set the Form State 

* In the Form Access tab, identify the form.  
* In the column "State" Select one of the Form States from the Dropdown Menu.  
* The table shows what each Form State allows.  

    | Form State   | Download Form | Submit Data |
    |--------------|-----------|-------------|
    | Open         | **Yes**       | **Yes**         |
    | Closing      | No        | **Yes**         |
    | Closed       | No        | No          |

 [Back to Form Access](#form-access)

### How to Assign Forms to App Users

* In the Form Access tab, identify the form.  
* In the column "App Users", Identify the App Users you want to assign Forms to.
* Tick the Check box, to allow access to the Form.  

[Back to Form Access](#form-access)

## Settings

In the Settings Tab, all the tasks are unique to the **Project Manager and Administrator**.  These are very sensitive tasks because it contains some tasks **that cannot be undone**.  

In this tab, you can do the following:

* Enter Basic Details (Project Name and Description)
* Enable Encryption
* Archive the Project
    * This Action Cannot be Undone. 
