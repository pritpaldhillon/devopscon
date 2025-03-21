# Hi and Welcome to Pritpal's DevOpsCon CI/CD demo repository
## This repo contains basic Maven project with Hello-World war file 
In order to make it work, please do the following: 

<ul>
  <li>Make sure JAVA 8 (<b>JDK</b> and not only <b>JRE</b>) or higher is running on your laptop</li>
  <li>Get Tomcat 9 (not verison 10) - prefer the Core > Zip from <a href=https://tomcat.apache.org/download-90.cgi target=new>here</a></li>
  <li>Configure under <TOMCAT DIR>/conf/tomcat-users.xml the code below</li>
  <li>[LINUX / MAC] Make sure you have running permissions on the /bin/ directory and run chmod +x *.sh</li>
  <li>Restart tomcat <TOMCAT DIR>/bin/shutdown.sh & startup.sh (for non-Windows OS) or /bin/shutdown.bat & startup.bat</li>
  <li>The Tomcat URL is <a href=http://localhost:8080/>http://localhost:8080/</a></li>  
  <li>The application URL is <a href=http://localhost:8080/helloworld/>http://localhost:8080/helloworld/</a></li>  
  <li>Have fun!</li>
  <li>Hello from Italy!</li> 
</ul>

 > ```xml
 > <tomcat-users>
 >   <role rolename="manager-gui" />
 >   <role rolename="admin-gui" />
 >   <role rolename="manager-script" />
 >   <user username="admin" password="admin" roles="manager-gui,admin-gui,manager-script" />
 > </tomcat-users>
 > ```

The workshop PPT can be downloaded from below link: 
https://drive.google.com/file/d/1q0PTkTGBH5Q4ODCfJSJekZJ2Js5v7Dzq/view?usp=sharing

