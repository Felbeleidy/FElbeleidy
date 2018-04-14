# FElbeleidy
Steps:
1. Download Java 1.8, Selenium package,Chrome driver and Eclipse (more help can be found here https://www.guru99.com/installing-selenium-webdriver.html)
2. Setup TestNG (https://www.guru99.com/all-about-testng-and-selenium.html)
3. Run the Java application first as you advised.
4. Open the TestNG project in by Eclipse
5. Run the scripts in the src folder

Tests:
- Login to the application
- Logout from the application
- Create a new account
- Create new account validation page without filling all fields.
- View and edit account info.
- View, edit, search, delete branches.
- View, edit, search, delete Staff.


Assumptions:
- The URL used to access the application is http://127.0.0.1:8080/#/. If you have it differently in your local then you need to change it in my scripts.
- Pagination will work when there are more than 20 records created in the page. 
- Project is done by Selenium, Java and on Chrome browser only.

Findings:
- The Delete button in the confirmation message is not working for Branches even if I tried to do it manually by myself. However, I automated it as well.
