This is an example for spring security.

To use this project, you need to install java and gradle

Check out the project, and go to the project root directory
1. Run "gradle idea" to download the dependencies
2. Run "gradle jettyRun" to start the server



http://localhost:8080/springSecurity
http://localhost:8080/springSecurity/welcome
These two urls are not secured, you can access them without any roles.

http://localhost:8080/springSecurity/admin
This url has been secured by spring security. You can access it with the user who have "ROLE_USER" role
you can find the user is in "spring-security-context.xml" file
