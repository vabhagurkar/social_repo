CONSOLE BASED SOCIAL NETWORKING APPLICATION

A.	To run the application from the command line:
1.	Unzip the project folder
2.  Open the cmd prompt
3.	Change the directory to the project path
    Eg: >cd C:\social_networking_app
4.	Run >mvn clean install
5.	Change the directory to the target folder
    Eg: >cd target
6.	Run the jar file generated by maven
    Run >java -jar social_networking_app-0.0.1-SNAPSHOT-jar-with-dependencies.jar
7.	On the console a prompt symbol �>� will appear
8.	Enter the application commands to work with the application
9.	Enter �Exit� to close the application

B.	To run the application from the IDE (Eg Eclipse):
1.	Unzip the project folder
2.	Open the IDE and Import the project as Existing Maven Project
    File -> Import� ->Existing Maven Projects
    Browse to the project directory
3.	Update the project
    Right click the project -> Maven -> Update Project� -> Run
4.	Run the test cases (Go to the src\test\java\com\social_ntw\app\AppTest.java)
    Right click on the AppTest.java -> Run as -> Junit Test
5.	Run Maven build Run as -> Maven build -> specify �clean install� as goal -> Run
6.	Run the application (Go to the src\main\java\com\social_ntw\app\AppTest.java)
    Right click on the AppTest.java -> Run as -> Java Application
7.	On the console a prompt symbol �> � will appear
8.	Enter the application commands to work with the application
9.	Enter �Exit� to close the application

C.	Please run the following commands on the following scenarios:
Posting: Rita can publish messages to personal timeline
Rita -> I love the weather today
Bob -> Damn! We lost!
Bob -> Good game though.

Reading: Bob can view Rita�s timeline
Rita
I love the weather today (5 minutes ago)
Bob
Good game though. (1 minute ago)
Damn! We lost! (2 minutes ago)

Following: Sue can subscribe to Rita�s and Bob�s timelines, and view an aggregated list of all subscriptions
Sue -> I�m in Broadford today! Anyone wants to have a coffee? 
Sue follows Rita
Sue wall
Sue -  I�m in Broadford today! Anyone wants to have a coffee? (2 seconds ago)
Rita � I love the weather today (5 minutes ago)

Sue follows Bob
Sue wall
Sue -  I�m in Broadford today! Anyone wants to have a coffee? (15 seconds ago)
Bob - Good game though. (1 minute ago)
Bob - Damn! We lost! (2 minutes ago)
Rita � I love the weather today (5 minutes ago)