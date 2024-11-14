Overview

This document provides step-by-step instructions for setting up users, groups, user criteria, catalogs, categories, and catalog items in ServiceNow ITSM. These configurations are intended for streamlining the procurement process of IT hardware at TechGlobal Inc.

Prerequisites

Access to ServiceNow instance with appropriate permissions.

Activity 1: Create Users

Navigate to Users

Open ServiceNow.

Click on All.

Search for Users.

Select Users under System Security.

Create a New User

Click on New.

Fill in the required details for the new user.

Click on Submit.

Activity 2: Create Groups

Navigate to Groups

Open ServiceNow.

Click on All.

Search for Groups.

Select Groups under System Security.

Create a New Group

Click on New.

Fill in the details:

Name: Platform

Manager: Manne Niranjan

Click on Save.

Add Members to Group

Go to Group Members and click on Edit.

Add Manne Niranjan to the Platform group.

Click on Save.

Click on Update.

Activity 3: Create User Criteria

Navigate to User Criteria

Open ServiceNow.

Click on All.

Search for User Criteria.

Select User Criteria under Service Catalog.

Create a New User Criteria

Click on New.

Enter the following details:

Name: Apple 15 pro max criteria

Groups: Platform

Click on Save.

Activity 4: Create Catalog

Navigate to Maintain Catalog

Open ServiceNow.

Click on All.

Search for Maintain Catalog.

Select Maintain Catalog under Service Catalog.

Create a New Catalog

Click on New.

Enter the following details:

Name: Apple

Description: Apple catalog

Enable Wishlist.

Click on Submit.

Activity 5: Create Categories

Navigate to Maintain Categories

Open ServiceNow.

Click on All.

Search for Maintain Categories.

Select Maintain Categories under Service Catalog.

Create a New Category

Click on New.

Enter the following details:

Title: Mobiles

Catalog: Apple

Click on Submit.

Activity 6: Create Category Item

Navigate to Maintain Items

Open ServiceNow.

Click on All.

Search for Maintain Items.

Select Maintain Items under Service Catalog.

Create a New Item

Click on New.

Enter the following details:

Name: Apple 15 pro max

Catalogs: Apple

Category: Mobiles

Item Details:

Short Description: Apple 15 pro max

Description: Hey! The Apple 15 Pro Max is a super cool phone with a big 6.7-inch display, powerful A14 Bionic chip, and amazing camera capabilities. It's got a sleek design and offers a great user experience. It's definitely a top-tier phone!

Add an image for the item.

Pricing Details:

Price: 111

Recurring Price: 5

Recurring Price Frequency: Semi-annually

Click on Save.

Create Variables for Catalog Item

Under Variables, click on New.

Provide variable details and set Order Number as 100.

Click on Submit.

Create additional variables:

Name variable with Order Number as 200.

Email variable with Order Number as 300.

Set Availability:

Under Available for, click on Edit.

Select Apple 15 pro max criteria.

Click on Save.

Activity 7: Assign to Portal

Navigate to Portals

Open ServiceNow.

Click on All.

Search for Portals.

Select Portals under Service Portal.

Assign Catalog to Portal

Scroll down and click on Catalogs.

Click on Edit.

Move Apple to the selected box.

Click on Save.

Result Verification

Impersonate User

Go to Profile and click on Impersonate User.

Select the created user and click on Impersonate User.

Verify in Portal

Open the ServiceNow portal.

Copy the base URL (up to .com/) and append sp. Example: https://dev224762.service-now.com/sp.

Click Enter.

Search for Apple 15 pro max.

Confirm that the item appears as created.

Note: If you impersonate another user, the item should not be visible.

Conclusion

This guide has outlined the detailed process for setting up users, groups, user criteria, catalogs, categories, and catalog items in ServiceNow to support IT procurement at TechGlobal Inc.

