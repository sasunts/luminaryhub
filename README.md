# luminaryhub
Guide to run local servers for WP development 

### Prerequisites (Preferably latest versions of each)
* [XAMPP](https://www.apachefriends.org/download.html)
* [WordPress](https://wordpress.org/download/)


## Steps
#### XAMPP Set up
##### Windows
When you open up XAMPP you must press start for Apache and for MySQL
Where it says MySQL press admin. 

##### MacOS
When you open XAMPP press Manage Servers and where it says MySQL press start and Apache Web Servers press start.
open this [link](http://localhost/phpmyadmin/) in your web browser: http://localhost/phpmyadmin/

Once the page opens press on the database tab.

Create a new database and take note of what you name it for our example WPtest, next to the name select the encoding list and scroll to the top and select Collation.

Once you have created the database download the wordpress files (link above).
Navigate to the XAMPP install folder.
* For windows its (C:\xampp)
* For mac its (~\Applications\XAMPP\xamppfiles)

You should see the htdocs folder. Open that.
In this folder you can create a new folder and this will be the directory of your website, for now lets call it test.
Extract the wordpress files in our test folder.

In your web browser open the link http://localhost/test *(Note, test should be what you name the folder in htdocs)* 
Here you will have your standard procedure to set up wordpress.
For database name enter what you named the database in this case WPtest.
User name is Root.
Password is blank.

If wp-config.php fails to install copy the code and make a new plain text file and paste it in and save it to the test folder. Save it as wp-config.php

Now make your wordpress log in details and you should be good to go!
