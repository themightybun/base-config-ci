README

Steps to configure project
1. Change .htaccess RewriteBase project url
2. Change base_url and secure_base_url to project url
3. Generate new $config['encryption_key'] here: http://randomkeygen.com/
4. Create session table - http://ellislab.com/codeigniter/user-guide/libraries/sessions.html
5. Change $config['sess_cookie_name'] to project session name
6. Change $config['sess_table_name'] to table name created
7. Change database settings
8. Change default route to site (usually)