# WebSec Lab
A php web application which contains a lot of common critical security flaws (like xss, sql injection, local file disclosure, etc.). This application was developed only for study purposes.

# Requirements
You will need a server running apache + php + mysql.
Basically, if you use windows, install wamp. If you use linux, install lamp and if you use mac, install mamp.

I do not recommend install this application in your production server because as you know, there's a lot of known vulnerabilities that can be exploited by script kiddies. In another words, if you do it, consideer the risk of being hacked by a 12 years old guy.

# Installation
First of all, create a schema in your mysql and import the file "schema/webseclab.sql". After this, open the class "classes/db.class.php" and edit the line five setting your database parameters correctly. If you did it correctly, the webseclab will be working correctly and all you have to do at this point exploit the vulnerabilities. 

Enjoy it :)