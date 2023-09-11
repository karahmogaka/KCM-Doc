USER ADMINISTRATION
=====================
.. figure::
Figure : 

User Management
~~~~~~~~~~~~~~~
Here are some of the key user management features in DHIS2:

#. User Roles and Permissions: DHIS2 allows administrators to define user roles with specific permissions. These roles can range from data entry operators to data managers and administrators. Permissions can be granular, specifying which data elements, datasets, and organizational units a user can access and what actions they can perform.
#. User Registration: Administrators can create new user accounts and assign them to appropriate user roles. Users can also register themselves if allowed, with or without approval from administrators.
#. Password Management: Users can change their passwords and reset them if forgotten. Password policies, such as complexity requirements and expiration periods, can be configured to enhance security.
#. User Groups: Users can be grouped together for easier management. For example, you can create groups for specific programs or departments. Group memberships can be used to assign permissions collectively.
#. User Profile Management: Users can update their profiles, including personal information, contact details, and preferences. Profile data can be used for user identification and communication.
#. User Auditing: DHIS2 keeps an audit trail of user activities, including logins, data entry, and other system interactions. Auditing helps in tracking user actions and maintaining data integrity.
#. Multi-Factor Authentication (MFA). DHIS2 can be configured to support MFA for enhanced security. Users may need to provide an additional authentication factor (e.g., a one-time code from a mobile app) during login.
#. User Import and Export:Administrators can import and export user data, making it easier to manage large numbers of users as well as assign import and export rights to specific users.

Adding New Users
~~~~~~~~~~~~~~~~
#. In the User Administration section, look for an option to "Add New User". Click on this option to start the user creation process.
#. Fill in the user's details. This typically includes:
	* First Name
	* Last Name
	* Email Address (if required)
	* Username (this will be used for login)
	* Password (choose a secure password)
	* Contact Information (optional)
        * Account Expiration Date Optional
	* Any other relevant user information
#. User Roles and Permissions: Assign roles and permissions to the new user. DHIS2 usually allows you to select from predefined roles or create custom roles with specific permissions.Roles define what actions the user can perform within DHIS2, such as data entry, data analysis, or administrative tasks. Assign roles that align with the user's responsibilities and job function.
#. Organization Units and Data Access: Specify the organization units or data sets that the user should have access to. This step ensures that the user can work with the relevant health facilities, geographic areas, or datasets. You can assign specific organization units or grant access based on user roles.
#. User Group (Optional): If your DHIS2 instance uses user groups, you can add the new user. User groups are helpful for managing users collectively, especially if you have multiple teams or departments using DHIS2.
#. Save and Confirm: After entering all the required information, click the "Save" or "Create User" button to confirm the new user's creation.

User Roles
~~~~~~~~
A user role is a collection of specific permissions known as authorities. These authorities define what tasks a user with that role can perform within the system. 
Here's a breakdown of how user roles work in DHIS2:

#. Superusers: This is an administrator or user account with the highest level of system privileges, enabling them to perform extensive tasks such as system configuration, user management, data management, system maintenance, and access control. These accounts should be assigned appropriately due to their extensive authority.
#. Multiple User Roles: A user can be assigned multiple user roles. When a user has multiple roles, their total set of authorities is the combination of all authorities and data sets associated with those roles. This means that users can have a versatile set of permissions based on the roles assigned to them.
#. DHIS2 allows administrators to mix and match user roles to suit specific purposes. Instead of creating entirely new roles for every unique requirement, administrators can assign existing roles to users to grant them the necessary permissions for their tasks.
#. Data Set Association: Each user role is associated with a specific collection of data sets. This relationship has implications for the Data Entry app. Users can only enter data for the data sets that are registered for their user role. 

	
User Groups
~~~~~~~~~~~~~~

This refers to collections of individual user accounts organized together for administrative or access control purposes. User groups are a way to manage and grant permissions to multiple users simultaneously.
