# Xero_test_adding_bank_account
User story 
-As a Xero User,
-In order to manage my business successfully,
-I want to be able to add an “ANZ (NZ)” bank account inside any Xero Organisation.

Using Python unittest framework to write the tests, using selenium webdriver. Have used the Page Object model, in which I have created files for different pages and stored under the Pages folder, a folder for locators, and another folder as 'Driver' to save the browser paths.

I have added 2 functional tests - test_Adding_new_bank_Account and test_Add_Dup_Bank_Account and have added the explanation on the tests itself

# Setup 
Need to download -  Python - https://www.python.org/downloads/
- Selenium Webdriver - http://www.seleniumhq.org
- Used pycharm IDE (Professional version) - https://www.jetbrains.com/pycharm/download/#section=windows

# Running tests
On pycharm, Go to the TestXeroProject/Demo/Tests directory, select the test Test_Add_Bank_Account.py file and using the Run option in the menu bar, you can run it with unittest
- Through command line, you can use python -m unittest Test_Add_Bank_Account.py




# Improvments
I would definetly try not to use time.sleep or implicit waits and replace with wait functions, and would not like to use elements with dynamic ids.


