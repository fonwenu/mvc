Java-MVC
========

RUNNING THE APPLICATION:

- Download and install JDK 7 (http://www.oracle.com/technetwork/java/javase/downloads/index.html). If you already have installed JDK 7, you can skip this step.
- Download and install Maven 3 (http://maven.apache.org/download.html#Installation). If you have already installed Maven 3, you can skip this step.
- Go the root directory of project (The one which contains the pom.xml file)
- Run command mvn clean jetty:run
- Start your browser and go to the location: http://localhost:8080

RUNNING TESTS:

- You can run unit tests by using this command: mvn test -P dev
- You can run integration tests by using this command: mvn verify -P integration-test

CODE REVIEW FEEDBACK:

Take the time to go through the entire codebase in the web application.  Provide feedback on what the application is doing from a high level, then proceed to analyze the code and describe in detail what you feel it's doing properly and not properly.  For the issues you may identify as being negative, describe what you'd do to refactor and fix the code in accordance to the coding standard you see is correct.

Below is a screenshot of the running application. To confirm that the application ran successfully, please provide a screenshot of your own with your review of the source code.

![Alt text](http://i.imgur.com/0KjHAFx.png "Optional Title")