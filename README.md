# WizardCodeAssigmentNaor
Assigment number 1 Jenkins with Docker compose 

for the docker compose assigment first you need to a mkdir jenkins and then make another dir for jenkins_home with mkdir ~/jenkins_home
after that that administraitor passowrd is requierd for the ui in order to acceses so we need to check the log and take only the pass with that command is easier
docker exec jenkins-lts cat /var/jenkins_home/secrets/initialAdminPassword

then just get in the web wirte localhost:8080 and start with install pluging and etc..

Assigment Number 2 Ldap server 
 i know the mfa is possible with freeRadius service and they got a few options with aws or with docker but im not at that level yet.. its alot of presetting
 but i could find ldap server with an Php ui to authorize accses within your network 
 
 User name to access the Ldap Server is cn=admin,dn=ramhlocal,dn=com  
 Password to access the Ldap Server is admin_pass
 again the web is based Php the only normal doco i could find to go with it and build it 
