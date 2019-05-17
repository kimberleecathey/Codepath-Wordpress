# Codepath-Wordpress

1st attack - The XSS vulnerability
Wordpress version 4.2 is vulnerable to a xxs attack.
The Example "public" page can be attacked be inserting a simple script into the comments section under the reply area of the page.
As you can see in the example I inserted a simple script which exucuted as soon as the "Post Comment" button was pressed.
Then the XSS attack was successful.

2nd Attack - Stored XSS vulnerability
This attack is also using Wordpress version 4.2. By using the same method as above I inserted a script into the comments section of the page, this script was specically tageting the cookies. Once the script was exucted by presssing the "Post Comment" button the attck is succesful and the server is being attacked and giving up information.
