# BugsFound

Below you can see some of the bugs I found on the projects I worked on

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF-1

Title : Functionality : Required "Hiring Manager" in "Vacancies" field can be left blank and submitted.

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/auth/login
2. Type in username "Admin" and password "admin123"
3. Click "Login Button"
4. Click Recruitment
5. Click on "Vacancies" link
6. In “Vacancy” column click on the first “Vacancy” link 
7. Push “Edit” button ![image](https://github.com/dicacristian/BugsFound/assets/85904271/4041d35e-42a4-486c-ba6f-50cf54883c46)

8. Delete "Hiring Manager" text field
9. Push "Save" button

**Expected Result**: Saving should not be allowed with empty “Hiring Manager” text field since it is marked as required

**Actual Result**: Error message “Failed to Save” is shown, but text field is saved empty
![photoooo](https://github.com/dicacristian/BugsFound/assets/85904271/868fb29d-2c53-47cc-9605-f1d493dd5943)

Environment : Google Chrome 





______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 2

Title : Functionality: “Job” in “My Info” cannot be edited.

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index
2. Type in username "Admin" and password "admin123"
3. Click "Login" button
4. Click on "My info" field
5. Push on "Job" button under the profile picture

 **Expected Result**: Job form can be edited by pushing green “Edit” like in “Personal Details”
 
**Actual Result**:  Job description form has no “Edit” button and cannot be edited

![bugsFOUNDDD](https://github.com/dicacristian/BugsFound/assets/85904271/09798d76-c650-4acb-acb4-9dba365be2d7)





Environment : Google Chrome 




______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 3


Title : Inconsistency : Required field gest no validation in "Registration Number" unlike unrequired field

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
![adsqqwwq](https://github.com/dicacristian/BugsFound/assets/85904271/f2759694-8e85-4d4d-9a85-0e1545a88f4a)

Environment : Google Chrome 


______________________________________________________________________________________________________________________________________________________________________


Bug ID : BF - 4

Title : The message was written, but I didn't write anything

1. Go to https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on "Contact"
4. Write anything on Contact Email/Name
5. Do not write in the message section

Expected result : They should have not let you send the message and warn you that it is an empty field

Actual result: Nothing special happens on the website. 

Test data : username : 123123 | password : 123123

   ![image](https://github.com/dicacristian/BugsFound/assets/85904271/e36a7ee8-bd4c-4125-920f-c18880c664fc)
 ______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 5

Title : Successful transaction on an expired card

1. Go to https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on "Samsung Galaxy S6"
4. Click on "Add to Cart"
5. Click on "Cart", then on "Place Order"
6. Introduce the test data
7. Press on "Purchase" 

Expected result : The website should warn you about your card

Actual result : The transaction was successfully completed

Test data :  username : 123123 | password : 123123 | Name : Cristian | Country : Spain | Credit card : 3660 6684 5071 2301   
Month : 01 | Year : 2021 
![image](https://github.com/dicacristian/BugsFound/assets/85904271/f78a07fd-d4f6-4772-bde1-09acd4e9d388)
