# WizardCodeAssigmentNaor
Assigment number 1 Jenkins with Docker compose 
Steps to make it work:

1  for the docker compose assigment first you need to a mkdir named jenkins  --The command is mkdir jenkins

   2 and then make another dir for jenkins_home in order to preserve the data it is the path of the volume --with mkdir ~/jenkins_home

   3 you need to move to the jenkins dir with cd jenkins

   4 you need to create a file for the docker-compose and docker compose can only read ceritan kind of syntax so we will be useing yaml

5 the command is // vim docker-compose.yaml 

6 last step is to copy and paste the syntax i created for the yaml inside the docker-compose file 
The file should look like that


![image](https://user-images.githubusercontent.com/105611672/202925104-4386af14-b3ac-42bd-8982-f6eb51eb08c9.png)




after that that administraitor passowrd is requierd for the ui in order to acceses so we need to check the log and take only the pass with that command is easier

 7 docker exec jenkins-lts cat /var/jenkins_home/secrets/initialAdminPassword

 8 then just get in the web write localhost:8080 and start with install pluging and etc..




Assigment Number 2 Ldap server 

 i know the mfa is possible with freeRadius service and they got a few options with aws or with docker but im not at that level yet.. its alot of presetting
 but i could find ldap server with an Php ui to authorize accses within your network 
 
 User name to access the Ldap Server is cn=admin,dn=ramhlocal,dn=com  
 Password to access the Ldap Server is admin_pass
 again the web is based Php the only normal doco i could find to go with it and build it 
