# Introduction

A Project Viewer is one type of Web user of ODK Central. The other Web Users are Administrators, Project Managers and Web Data Collectors. With the exception of the Administrator, all the other roles are project specific. 

Recall that ODK Central has Projects, and each Project has Users with Roles, Forms, Forms with Submissions, Entity Lists and Entities. Forms will contain data (called Submissions). Entity Lists will also contain data (called entities). Forms, Entity Lists and Entities are pre-defined by the Project. A Project Viewer can list forms and entities (where data is placed), download all submissions and entities, see individual entities in the browser.

In summary, a Project Viewer can work with Submissions and Entities.  A Project Viewer can see but cannot change.

# Role of Project Viewers
- List All Forms
- Comment on Form Submissions
- View and Download Form Submissions
- Access OData Feed for Form Submissions
- List all Project Entity Lists
- View and Download Project Entities
- Access OData Feed of Project Entities

## These are some examples of what a Project Viewer cannot do
- Create Projects - only the Administrator can do this
- Create Forms and Entities - this is the role of the Project Manager only
- Edit Form Submission - this is the role of the Project Manager only
- Create Project Form Submissions - Data Collectors (and Project Manager)
- View Raw Data Online - you must first download these and view them in a spreadsheet or other software.

## Overlapping Roles
- The Project Manager can do every role of the Project Viewer.
- The Web Data Collector can also list all forms.

## Possible assigned tasks of a Project Viewer in Data Collection
- Review any possible ID Conflicts
- Review any other data errors such as missing data or wrong entry.
- Comment on submissions
- Create summary tables after downloading entities or submissions

# Navigating Central as a Project Viewer

This is a Site Map showing where you can do each task

ODK Central Home [View Projects , Forms , Entity Lists]

-- Project Summary | Docs | Forum

-- News

-- Projects

     ---- Forms [List all Forms]

           ---- Submissions [View Submissions]

                   ---- Filter Views

                 ----  Submission Details and Activity [Comment on Submissions]

                 ----  Download [Download  Submissions]

     ---- Entity Lists [View all Entity Lists]

         ---- Entities [View Entities and Data]

                 ----  Entity Details and Activity  [View Metadata and Data]

                 ----  Download [Download Entities]


