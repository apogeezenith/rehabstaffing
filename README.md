To deploy, once your SSH key is added to the server, you can simply:

From project root:
```
middleman build
cd build
scp -r . <account_name>@<server_ip_address>:/var/www/site_directory/html/
```
