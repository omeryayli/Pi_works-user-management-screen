# User Management Screen

---------------
## Overview

This specification document explains the sections of the user management screen. Each section includes details of corresponding sub-components.

----------------------------
### Header Section
* There are three components in this section.
* The 'New User' button is used for accessing to new user registration page.
* The 'Hide Disabled User' checkbox is used for hiding the user on the database section for the users who did not check the 'enabled' button.
* The 'Save User' button can be used after filling all the boxes properly in the New User Screen to save the user on database.

-------------------
### New User Section

* New User screen has four textboxes, one dropdown menu, and one checkbox.
* The 'username' and 'Display Name' box accept alphanumeric characters, and the given username must be unique. These fields are mandatory.
* The 'Phone' box accepts numeric characters.
* The 'Email' box accepts all kind of characters but must include '@'.
* The 'User Role' box has a dropdown menu and one out of three must be selected.
* The 'Enabled' button is False by the default, and can be checked to enable it.

-------------------------

### Database Section
* The Database Section is a table, and has four columns.
* The 'ID' column is increased automatically for each newly registered user.
* The 'User Name' column shows the user's chosen username.
* The 'Email' column represents the user's email address.
* The 'Enabled' column is True or False depending on the Enabled checkbox at the New User Section.

------------
