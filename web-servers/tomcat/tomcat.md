***yum install -y tomcat***<br>
***systemctl start tomcat***

**To make modifictations in tomcat's config**<br>
***vi /etc/tomcat/webserver.xml***<br>
***systemctl restart tomcat***
# CHANGE TOMCAT'S PORT
![alt text](scs/image.png)
# FINALLY
***Copy your .war file to tomcat's webapps locations -> /usr/share/tomcat/webapps***