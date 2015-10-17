#Ansible for setting up basic server setup
for now it includes two roles basic and mysql

#Basic Role
* Will install basic tools (screen, vim, git)
* Will setup an admin user (with sudo access)
* Will create an application level user
* Will modify sshd config to disable root logins
* Will update ulimits

#Mysql Role
* Will install mysql
* Will create a application level db user
* Will create a db for application and give * access to application
  level user for this database

This is under development
