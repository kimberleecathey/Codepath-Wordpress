# Codepath-Wordpress

The first step was to make Wordpress version 4.2 the current version used in the Admin wordpress account. This was done by setting up a WPDistillery VM in conjuction with downloading Vagrant software. Then by changing the defaults in the config file of the WPDistillery to version 4.2 of wordpress and changing other defaults such as themes,posts, plug ins, files. etc. 

1st attack - The XSS vulnerability
The Example "public" page can be attacked be inserting a simple script into the comments section under the reply area of the page.
As you can see in the example I inserted a simple script which exucuted as soon as the "Post Comment" button was pressed.
Then the XSS attack was successful.

2nd Attack - Stored XSS vulnerability
By using the same method as above I inserted a script into the comments section of the page, this script was specically tageting the cookies. Once the script was exucted by presssing the "Post Comment" button the attck is succesful and the server is being attacked and giving up information.
