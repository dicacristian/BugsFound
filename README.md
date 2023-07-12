# BugsFound

Below you can see some of the bugs I found on the projects I worked on

______________________________________________________________________________________________________________________________________________________________________

Title : Functionality : Required "Hiring Manager" in "Vacancies" field can be left blank and submitted.

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
2. Type in username "Admin" and password "admin123"
3. Click "Login Button"
4. Click Recruitment
5. Click on "Vacancies" link
6. In “Vacancy” column click on “Analyst” link or any other “Vacancy” link
7. Push “Edit” button
8. Delete "Hiring Manager" text field
9. Push "Save" button

**Expected Result**: Saving should not be allowed with empty “Hiring Manager” text field since it is marked as required

**Actual Result**: Error message “Failed to Save” is shown, but text field is saved empty

Environment : Google Chrome 


______________________________________________________________________________________________________________________________________________________________________

Title : Functionality: “Job” in “My Info” cannot be edited.

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index
2. Type in username "Admin" and password "admin123"
3. Click "Login" button
4. Click on "My info" field
5. Push on "Job" button under the profile picture

 **Expected Result**: Job form can be edited by pushing green “Edit” like in “Personal Details”
 
**Actual Result**:  Job description form has no “Edit” button and cannot be edited

Environment : Google Chrome 


______________________________________________________________________________________________________________________________________________________________________

Inconsistency : Required field gest no validation in "Registration Number" unlike unrequired field

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index
2. Type in username "Admin" and password "admin123"
3. Click "Login" button
4. Click on "Admin" tab on top left
5. Click on "Organization"
6. Click on "General Information"
7. Click "Edit" tab on top right
8. Type "!#$%%@!#$@$" into "Registration Number" text field

Expected Result: Field should be validated just letter and numbers, not special characters
Actual Result: Field accepts all characters

Environment : Google Chrome 

   
   
