# Laptop_Request_Catalog_Item_Project_1
Overview

This project automates the laptop request process within the organization by creating a Service Catalog item in ServiceNow.
It replaces the manual, time-consuming request process with a dynamic, guided, and efficient workflow that improves data accuracy, user experience, and governance.

Problem Statement

Employees in the organization need a quick and efficient way to request laptops for work.
The current process is manual and prone to delays, with no dynamic form behavior to guide users or ensure accurate data collection.

This project introduces a Service Catalog item that:

Allows employees to request laptops easily.

Uses dynamic fields and clear instructions.

Includes functionality to reset the form if needed.

Ensures all changes are tracked for governance and deployment.

Key Features

Dynamic Form Behavior — Fields update automatically based on user selections.

Form Validation — Prevents incomplete or incorrect data submission.

Form Reset Option — Allows users to clear and start again.

Approval Workflow — Routes requests through proper approval channels.

Audit & Tracking — Maintains a record of changes for governance and deployment.

Components

Catalog Item: Laptop Request

Variables: Request Type, Laptop Model, Justification, Manager Approval, etc.

Client Scripts: Dynamic field updates and form reset functionality.

UI Policies: Conditional display and mandatory field settings.

Workflow: Approval and fulfillment routing.

How to Use

Navigate to Service Catalog → Hardware → Laptop Request.

Fill in required fields such as Laptop Type, Business Justification, and Manager.

Submit the form.

Track your request status under My Requests.

Learning Objectives

This project helps you understand:

How to create and configure Catalog Items in ServiceNow.

How to use Client Scripts and UI Policies for dynamic forms.

How to design approval workflows and maintain governance.

How to manage update sets and deployment in a ServiceNow instance.

Tools & Technologies

Platform: ServiceNow

Modules Used: Service Catalog, Workflow, Update Sets, Client Scripts, UI Policies

Instance Type: Developer Instance
