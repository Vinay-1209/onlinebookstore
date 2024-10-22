
### Software And Tools Required
- **Java JDK 8+**: [Installation Guide](https://www.youtube.com/watch?v=O9PWH9SeTTE)
- **Apache Maven**: [Installation Guide](https://www.youtube.com/watch?v=jd2zx3dLjuw)
- **Tomcat v8.0+**: [Installation Guide](https://youtu.be/mLFPodZO8Iw?t=903)
- **IntelliJ IDEA**

### Importing and Running The Project
1. **Download the project zip file** from the git repository.
2. **Open the file in IntelliJ**.
3. At the left corner, expand the main menu.
4. Select **Build > Build Project**.
5. **Set up the Tomcat server**:
   1. In the top navbar, click on **Current File**.
   2. Under that, select **Edit Configuration**.
   3. Click on the **+** on the top left and select **Smart Tomcat**.
   4. Name the server, select the Tomcat server you have installed, and select the folder for Catalina base.
   5. For the deployment directory, select the **WebContent** folder path.
   6. Provide any context path.
   7. If required, change the server ports.
   8. Click on **Apply** and then **OK**.
6. At the left corner, expand the main menu.
7. Select **Run > Run Tomcat**.
8. It will run and show you the URL to open.
9. You can see the website at [http://localhost:8080/online](http://localhost:8080/online).
