# BugsFound

Below you can see some of the bugs I found on the projects I worked on

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF-1

Title : Functionality : Required "Hiring Manager" in "Vacancies" field can be left blank and submitted.

Severity : Low 

Priority : Low 

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


Severity : Low 

Priority : Low 

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


Title :  Required field gest no validation in "Registration Number" unlike unrequired field

Severity : Normal

Priority : Normal 

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

 Title : Date of birth can work with the dates from the future

 Severity : Normal 

 Priority : Normal

1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index
2. Log in with correct username and password
3. On the left side, click on "My Info"
4. Scroll down until you see "Date of Birth"
5. Put birthday 30 December 2023

Expected result : Cannot save changes and user is required to enter a date of birth now or in the past

Actual result : A new message: "Successfully Updated" 

Test data : username : Admin | password : admin123

______________________________________________________________________________________________________________________________________________________________________
Bug ID : BF - 5

 Title : The main language it is not English 

 1. Go to https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index
 2. Log in with correct username and password

    Expected result : The orangeHRM page should be displayed in English

    Actual result : The site is displayed in spanish

    Note : The site goes back to being displayed in English, on refreshing the page

   Test data : username : Admin | password : admin123

   ![image](https://github.com/dicacristian/BugsFound/assets/85904271/9ca39f36-7c49-4ec1-bfea-edb058705006)


 


______________________________________________________________________________________________________________________________________________________________________
Bug ID : BF - 6

Title : The message was written, but I didn't write anything

Severity : Low

Priority : Low 

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

Bug ID : BF - 7

Title : Successful transaction on an expired card

Severity : Critical

Priority : Critical 

1. Go to https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on "Samsung Galaxy S6"
4. Click on "Add to Cart"
5. Click on "Cart", then on "Place Order"
6. Introduce the test data
7. Press on "Purchase" 

Expected result : The website should warn you about your card

Actual result : The transaction was successfully completed

Test data :  | username : 123123 | password : 123123 | Name : Cristian | Country : Spain | Credit card : 3660 6684 5071 2301   
Month : 01 | Year : 2021 

![image](https://github.com/dicacristian/BugsFound/assets/85904271/f78a07fd-d4f6-4772-bde1-09acd4e9d388)

 ______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 8

Severity : Low

Priority : Low 

Title : The "Welcome User" button has no special functionality for users

1. Go to https://www.demoblaze.com/
2. Log in with correct username and password
3. Click on "Welcome user", on the right corner

Expected result: User should be redirected to the settings of the account.

Actual result: Nothing special happens on the website.

Test data: | username: 123123 | Password: 123123 |

______________________________________________________________________________________________________________________________________________________________________
Bug ID : BF - 9 

Title : The Copyright of the website for current year

Severity : Low

Priority : Low 

 1. Go to https://www.demoblaze.com/
 2. Scroll down to the footer of the website

Expected result: The Copyright have to be updated to the current year (2022).

Actual result: The Copyright is not updated to the current year, in this case 2022, but for 2017.

______________________________________________________________________________________________________________________________________________________________________
Bug ID : BF - 10

Severity : Normal 

Priority : Normal

Title : Zip code written with letters

1. Go to https://www.saucedemo.com/
2. Log in with correct username and password
3. Select a product
4. In the right side, click on "Checkout"
5. Write your First/Last name and Zip code and click on "Continue" 

Expected result : The site should not let you to continue 

Actual result : Proceed further towards completion of order

Test data: | username: standard_user | Password: secret_sauce | First Name : test | Last name : test | Zip Code : abcd

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 11

Title : Selecting the same product more than once

Severity : Normal 

Priority : Normal

1. Go to https://www.saucedemo.com/
2. Log in with correct username and password
3. On the top right side, press the shopping cart icon
4. Try to select the product several times

Expect result : Select the number of desired products

Actual result : The website doesn't let you select how many products you want 

Test data: | username: standard_user | Password: secret_sauce |

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 12

Severity : Low

Priority : Low 

Title : Same photo for different products

1. Go to https://www.saucedemo.com/
2. Log in with correct username and password
3. Try putting 2 different products in your cart

Expected result : Each product should have an individual picture

Actual result : All products has the same photo

Test data :  | username: problem_user | Password: secret_sauce |

![image](https://github.com/dicacristian/BugsFound/assets/85904271/0b93f877-aa54-446f-8d1c-5ffc1c28c928)

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 13

Severity : Critical

Priority : Critical

Title : "Last name" field does not let you write

1. Go to https://www.saucedemo.com/
2. Log in with correct username and password
3. Select a product
4. In the right side, click on "Checkout"
5. Write your First/Last name and Zip code and click on "Continue"

Expected result : Website continues towards finalization of order

Actual result : At the "Last name" field I cannot write, so I cannot finish the order

Test data :  | username: problem_user | Password: secret_sauce |

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 14 

Severity : Low 

Priority : Low 

Title: The required symbol (*) is not displayed in no field on the Registration Form

1. Go to https://demoqa.com/elements
2. Click on "Web Tables"
3. Click on "Add" button
4. Add "abc" into "First Name" field
5. Add "cde" into "Last Name" field
6. Add "test.example@gmail.com" into "Email" field
7. Add "19" into "Age" field
8. Press the "Subtmit" button

Expected results: All new data should be successfully saved

Actual results: The blank fields have become red, as if they were mandatory, but without being mentioned by that symbol (*)
   
______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 15 

Severity : Low 

Priority : Low 

Title : Copyright is not actualized for the current year (2023) 

1. Go to https://demoqa.com/

Expected result: The Copyright have to be updated to the current year (2023)

Actual result: The Copyright is not updated to the current year, in this case 2023, but for 2013 - 2020

![image](https://github.com/dicacristian/BugsFound/assets/85904271/61518fb8-8af6-4988-8f98-7a899034eee8)  

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 16 


Severity : Normal 

Priority : Normal 

Title : Shopping cart is empty even though I added something

1. Go to https://demo.opencart.com/
2. Scroll down until you see the products
3. Select one of them
4. Press the shopping cart icon
5. In the top right side. click on "shopping cart" 

Expected result: Product has been successfully added

Actual result: No products have been added and our shopping cart is empty 

______________________________________________________________________________________________________________________________________________________________________

Bug ID : BF - 17 

Severity : Critical 

Priority: Critical 

Title : Add account credentials and nothing happens

1. Go to https://demo.opencart.com/
2. On the top side, hover on "My Account", then click on "Register"
3. Add First/Last Name, email and password with test data
4. Click on the left button on "I have read and agree to the Privacy Policy"
5. Press on "Continue" button

Expected result: The account has been successfully created

Actual result: No account has been created


