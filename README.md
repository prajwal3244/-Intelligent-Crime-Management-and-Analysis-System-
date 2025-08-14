Steps to Run the Crime Management System

Install Required Software

XAMPP or WAMP (Windows)

MAMP (Mac)

LAMP stack (Linux)

Extract the Project

Unzip the file and rename the extracted folder (e.g., crime).

Move it to your web server’s root directory:

XAMPP (Windows): C:\xampp\htdocs\crime

WAMP: C:\wamp\www\crime

Linux LAMP: /var/www/html/crime

Set Up the Database

Start Apache and MySQL from your XAMPP/WAMP control panel.

Open phpMyAdmin in your browser:

http://localhost/phpmyadmin


Create a new database (e.g., crime_db).

Import the .sql file from your project folder (check inside for a .sql file, usually in a folder like database or sql).

Configure Database Connection

Open the PHP files that handle DB connection (likely named config.php or similar) in a text editor.

Update the database name, username, and password as per your local server settings:

$servername = "localhost";
$username = "root"; // default for XAMPP/WAMP
$password = ""; // default for XAMPP/WAMP
$dbname = "crime_db";


Run the Project

Open your browser and go to:

http://localhost/crime


Login using default credentials (check the SQL file for user data).

Explore the System

Different login roles may be available: complainer, police in-charge, head, etc.

Navigate to the respective pages (complainer_page.php, inchargelogin.php, headlogin.php) to test functionalities.
