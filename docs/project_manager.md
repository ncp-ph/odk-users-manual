# Introduction

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
    * [App Users]
    * [Form Access]
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


 ### How to Edit an Entity
In the Entities tab, you can Create an New Entity List, View Entities, Download Entities.

1. To edit an entity, first select an Entity List.

2.  The select an entity within that list.

3. Hover over the Actions column in the row of the entity you want to edit.  

4. Choose edit (pen icon).

5. Choosing More will take you to Entity details and an edit entity ink.

6. Either  way, an edit pop-up window will show up.

Selecting and Entity List

Selecting an entity to edit

The Editing pop-up Window


 ### How to Delete an Entity

 In the Entities tab, you can Create an New Entity List, View Entities, Download Entities.

1. To delete an entity, first select an Entity List.

2.  The select an entity within that list.

3. Hover over the Actions column in the row of the entity you want to delete.  

4. Choose delete (trash icon).

5. Choosing More will take you to Entity details and an delete entity ink.

6. Either  way, an edit pop-up window will show up to ask you to confirm.

Selecting and Entity List

Selecting an entity to delete

The Delete pop-up Window

## How to Assign Users to Projects

### Assigning Web Users to Projects

1. Ask the Administrator to Create Web Users for your Project (provide e-mail address).

2.  As Project Manager go to Project > Project Roles Tab

3.  In the Search Box, place the exact email address.

4.  Select the User and Assign a Role

Search for the Web User

Assigning Roles

### Assigning App Users

## Form Access

In the Forms Access tab, all the tasks are unique to the **Project Manager and Administrator**.  There are two main tasks.  The first task is to set the Form State.  The second task is to set the Form Access.  You  will see all your Forms as rows.  In the columns, you will see the Different App Users in the Project. 

In this tab, you can do the following:

* Set the Form State as Open, Closing or Closed using the Dropdown Menu beside each Form.  

    | Form State   | Download Form | Submit Data |
    |--------------|-----------|-------------|
    | Open         | **Yes**       | **Yes**         |
    | Closing      | No        | **Yes**         |
    | Closed       | No        | No          |

* Give Form Access to App Users using the Checkbox under each App User.  
    * One scenario for this is that you may have a form that you want to test with a few App Users before scaling up.  
    * Another scenario is that you may want to suspend data entry from specific areas or App Users.  

## Settings

In the Settings Tab, all the tasks are unique to the **Project Manager and Administrator**.  These are very sensitive tasks because it contains some tasks **that cannot be undone**. That is why the Project Manager role should be assigned with care.  

In this tab, you can do the following:

* Change Basic Details (Name and Description)
* Enable Encryption
* Archive the Project
    * This Action Cannot be Undone. 
