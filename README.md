Software And Tools Required 
: Java JDK 8+ [https://www.youtube.com/watch?v=O9PWH9SeTTE]
: Apache Maven [https://www.youtube.com/watch?v=jd2zx3dLjuw]
: Tomcat v8.0+ [https://youtu.be/mLFPodZO8Iw?t=903]
: Intellij
 Importing and Running The Project 
 . Download the project zip file from the git repo.
 .open the file in Intellij.
 .At left corner expand the main menu.
 .Select build > build project.
 . Now we need to setup the tomcat server
   1.In top navbar we see Current File click on it.
   2.under that select Edit Configuration.
   3.click on the + on the left top and select "smart tomcat"
   4.Name the server,select tomcat server that you have installed and select folder for catalina base.
   5.For deployment directory select WebContent folder path
   6.Give any context Path.
   7.If require change the server ports.
   8.Click on Apply and then ok.
 .At left corner expand the main menu.
 .Select run>run tomcat
 .It will run and show you the url to open 
 .you can see the website at http://localhost:8080/online
