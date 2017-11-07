# codeigniter-wordpress-bridge
Decode a codeigniter session from wordpress and automatically log in / create the user in wordpress

This code demonstrates how a user session base can be shared between Codeigniter and Wordpress. If the user is already logged into Codeigniter and visits the wordpress site, he will have his account created (based on the email address set in the Codeigniter session) OR if the user already has his account created, he will be logged in automatically to wordpress with that email address.

The folder structure for the demonstration :
--- codeigniter project
--- wordpress project 

both folders should be at the same level. 

the file SessionHandler.php is used for decoding a PHP session
