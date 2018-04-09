# Jenkins_Config_with_Maven-
This repository belong to Setup jenkins and pass perameters to POM.xml from jenkins
//############################Jenkins installation###################################

The complete process to install Jenkins can be summarized in five steps:
1)By .War file
Install Java Version 8 – Jenkins is a Java based application, hence Java is a must.
Download Jenkins war File – This war is required to install Jenkins.
Deploy Jenkins war File – Jenkins war file needs to be deployed using Tomcat to run Jenkins.
Install Suggested Plugins – Install a list of plugins suggested by Jenkins.


2)You can also download windows installer for Jenkins


Useful links:- https://jenkins.io/download/

Please refer Image: Jenkins_download for reference under Jenkins installation folder.

//######################How to run###################################################

1)Open cmd 
2)go to jenkins.war directory
3)run command--> java -jar jenkins.war

Default port is 8080
If you want to specify other port 

Run command --> java -jar jenkins.war httpPort=8082

As i mention port number 8082 you can specify any port number.

But if you have installed by window installer you can directly launch you jenkins on localhost:8080 in your browser

//#################Launch in your browser############################
1)open you browser
2)enter url localhost:8080 if default port [otherwise localhost:XXyy if defined other]
3)After running this jenkins will ask for authentication keys which you will see on your cmd window or you can find in your jenkins folder in program files as a secret key.
4)After this you will see a window with option install suggested plugins.  click on it.


 



