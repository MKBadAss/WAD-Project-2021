You can see most of PHP actions are in Old Project/ include 

For example of Login function. Logi.php file is just the front-end, login.inc.php respond to any interaction of user input.

- Procedure of login.inc.php 
    1. It call out to dbh.inc.php to connect to database in phpMyAdmin 
    2. It has If-else statement to validate the user input sysntax 
    3. If the user's input is lexically vadiate, it call out to function which already defind in "function.inc.php" that check the inputted date with database
    4. If the inputted data correct. The user log into 