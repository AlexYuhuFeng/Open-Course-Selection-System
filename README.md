# Open Course Registration System

GU2 Project by Feng, Yuhu 

1. Introduction

   Open Course Registration System(OCRS) is an open source course registration system built using PHP, HTML, CSS, JS(Standard and Ajax). 

   Note:

   The program has an early dev version built by JSP. The version is no longer maintained thus not included.

2. Dev Tools
   1. Editor: Visual Studio Code
      1. Version: VSCode-x64-1.55.2
      2. Usage: Edit php/html/sql files
   2. IDE: PhpStorm
      1. Version: PhpStorm-2021.1.1
      2. Usage: Development of the project
   3. web server stack package: XAMPP
      1. Version: xampp-windows-x64-8.0.3-0-VS16
         1. Sub Versions: 
            1. Apache Web Server 2.4
            2. MySQL 8.0.24
            3. PHP 8.0.3	
      2. Usage: hosting website(Apache), Database functionalities(MySQL) and Programming Language Support(PHP)

3. Environment Setup

   1. Install provided package of XAMPP or alternative package of XAMPP for supported operating systems(macOS and Linux)

   2. Copy the <u>orcs</u> folder under source code into <u>htdocs</u> folder under the root directory of XAMPP application.

   3. open XAMPP, start Apache and MySQL services.

   4. open the browser, go to <u>localhost/phpmyadmin</u>

   5. click open <u>database</u> tab and create a new database named "coursereg"

   6. click open database <u>coursereg</u> and import a new sql dumpfile.

   7. choose <u>coursereg.sql</u> under the root directory of the source code and import.

   8. open localhost/ocrs/login.php to see if the portal is correctly displayed. 

      

      Note:

      + Go back and check for missing steps if the page is incorrectly displayed.

      + As certain JS files are retrieved through Google hosting api, please provide viable internet connection. If the page fail to load, turn off internet connection to enable local JS files to be enacted.

      + There is not preset password for the database. Please feel free to add password for security purposes.

4. Demo Accounts(account/password)

   1. Student: csc141234/moses
   2. Admin: ADM101/qwerty
