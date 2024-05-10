# food

#1 Install Java Development Kit (JDK):
```sql
sudo apt update
sudo apt install default-jdk
```
#2 Install Apache Tomcat:
```arduino
sudo apt-get install tomcat9
```
#3 Start Tomcat:
```sql
sudo systemctl start tomcat9
```
#4 Verify Tomcat Installation:
Open a web browser and go to http://localhost:8080. If Tomcat is installed and running correctly, you should see the Tomcat welcome page.

#5 Deploy Your Web Application:
Place your JSP file(s) inside the Tomcat webapps directory. By default, it's located at /var/lib/tomcat9/webapps/.
Optionally, you can create a new directory under webapps for your application, for example, /var/lib/tomcat9/webapps/myapp/, and place your JSP file(s) there.

#6 Access Your JSP Page:
If you placed your JSP file in the root directory of Tomcat's webapps folder, you can access it by going to http://localhost:8080/yourjspfilename.jsp in your browser.

#7 To Stop Tomcat:
```arudino
sudo systemctl stop tomcat9
```
###Remember to replace yourjspfilename.jsp with the actual filename of your JSP file.
