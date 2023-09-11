USER ADMINISTRATION
=====================
.. figure::
Figure : 

User Management
~~~~~~~~

Simultaneous Access: Multiple users can access DHIS2 at the same time, allowing for collaborative work and data management.
User, User Roles, and User Groups: You have the flexibility to create and manage user accounts, user roles, and user groups to organize and control access effectively.
User authorities can be assigned at different levels. You can grant specific authorities to user groups or individual users through user roles.
You can create multiple user roles, each with its own set of authorities. This allows for precise control over user permissions based on their responsibilities.
Assign user roles to users based on their roles and responsibilities within the organization. This defines what they can do in DHIS2.
You can also assign each user to specific organizational units. This ties users to specific areas or entities they are responsible for, enabling them to enter data for those assigned units.


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
