# Introduction

An App User is a user of ODK Collect.  The main role of an App User is to collect data with the ODK Collect App

# Overview of ODK Central
ODK Central is the hub that controls the ODK Ecosystem. ODK Central manages users, forms, permissions and data flow. Forms are created in a computer using a template in Excel or Google Sheets using the XLSForm Standard. These XLSForms are are uploaded to ODK Central.  ODK Collect connects to ODK Central Projects and Forms using the QR Codes. Forms are then downloaded into the ODK Collect App as blank forms.  Data collected using these Forms are processed within ODK Collect and sent back to ODK Central.  These are called Submissions.  These Submissions can then be exported as data for analysis. 

<img width="300" height="672" alt="odk and central collect diagram" src="/assets/images/diagram_odk_collect.png" />

# Overview of ODK Collect

The ODK Collect App is designed to Download Project Settings from ODK Central.  Then, within that project, the user can download Specific Forms. ODK Collect Settings govern how it functions and handles data.  Settings require decisions to be made by the Project Manager.  

Here are some illustrations of settings focused on how forms are sent.

<img width="600" height="672" alt="shows odk collect flow of forms with no auto settings" src="/assets/images/odk_panela.png" />

Recall that ODK Central has Projects, and each Project has Users with Roles, Forms, Forms with Submissions, Entity Lists and Entities. Forms will contain data (called Submissions). Entity Lists will also contain data (called entities). Forms, Entity Lists and Entities are pre-defined by the Project. A Project Viewer can list forms and entities (where data is placed), download all submissions and entities, see individual entities in the browser.

# Tasks of App Users

* Install ODK Collect
* Connect to an ODK Project
* Download Project Forms
* Enter Data into Forms
* Save Submissions
* Send Submissions
* Sync with ODK Central

# Next Steps

* [About ODK Collect](./about-odk-collect.md)
* [Install ODK Collect](./install-odk-collect.md)
* [Try ODK Collect](./try-odk-collect.md)