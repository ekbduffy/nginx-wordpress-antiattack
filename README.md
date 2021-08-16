# nginx-wordpress-antiattack
Small group of tweaks for nginx config to prevent a big portion of web attacks 

Use wordpress-site.conf file as the website config file. 
Place wordpress.conf somewhere outside of sites-configured folder, and adjust the path in wordpress-site.conf to include it

Additionally, i would strongly suggest to disable write permissions for the www-user into the whole wp-content folder, except uploads subfolder, and enable write permissions only when you're working on the installing/updating etc.
