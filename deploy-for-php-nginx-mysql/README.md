Deploy source php with following services
+ PHP any version
+ mysql server
+ nginx
+ certbot (optional)

-- Folder structure explain
+ workspace: mapping folder source in container 
    + Functional: folder source code
+ nginx: mapping folder /etc/nginx in container
    + Functional: folder contains config of nginx
+ mysql: mapping folder 
    + Functional: folder contains mysql data

