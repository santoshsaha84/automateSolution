Download Java 11 jdk
Add environment variable
JAVA_HOME C:\Program Files\Java\jdk-11.0.17
Add System variable
path C:\Program Files\Java\jdk-11.0.17\bin
Download apache maven 
Place in path C:\Program Files\apache-maven-3.8.6
Add environment variable
MAVEN_HOME C:\Program Files\apache-maven-3.8.6
Add System variable
path C:\Program Files\apache-maven-3.8.6\bin
Install Eclipse IDE
Create Maven Project
Add Selenium dependency from maven repository
Add Testng dependency from maven repository
Add testng plugin and maven integration plugin from market place
Convert project to testng that will create testng.xml
Add maven maven-surefire-plugin and maven-compiler-plugin to POM
Add source and target properties to pom
Inside maven-surefire-plugin plugin add testng.xml file in pom
Write your tests
Install jenkins 
Deploy jenkins with war file with commmad java -jar <pathot.warfile>/jenkins.war --httpPort=8084
Open jenkins on port localhost:8084
Add maven integration plugin from pluginmanager in jenkins
Create new job as maven project
Providd github repo url and credentials
Enter clean install in Goals
Build maven project

