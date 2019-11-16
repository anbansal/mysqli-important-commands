# important-commands
mysql important commands 

1.Login into Mysql as root 
>mysql -u root -p

Then type this command

>ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password'; 

MacOS Catalina broken stuff command
>sudo chown -R $(whoami):admin /usr/local/* && sudo chmod -R g+rwx /usr/local/* 
