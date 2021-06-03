# DBMS-Project
DBMS project 2021 Sukkur IBA University when you build an java application project that has a  main class the IDE automatically copies all of the jar file on the project class path to your projects dist/lib folder. The IDE also adds each of the jar file to class path element in the application jar files login form.
To run the project from the command line go to the dist folder and type the following:
Java –jar “loginfrom.jar”
 To distribute this project, zip up the dist folder and distribute the zip file and also import sql file in Mysql.
Notes:
•	First import Sql file in mysql or any DBMS software.
•	If two JAR files on the project classpath have the same name, only the first JAR file is copied to the lib folder.
•	Only JAR files are copied to the lib folder. If the classpath contains other types of files or folders, none of the classpath elements are copied to the lib folder. In such a case, you need to copy the classpath elements to the lib folder manually after the build.
•	If a library on the projects classpath also has a Class-Path element specified in the login form, the content of the Class-Path element has to be on the projects runtime path.
•	To set a main class in a standard Java project, right-click the project node in the Projects window and choose Properties. Then click Run and enter the class name in the Main Class field. Alternatively, you can manually type the class name in the login form Main-Class element.

