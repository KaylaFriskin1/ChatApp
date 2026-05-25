#QuickChat Java Application part 2:
##Overview
QuickChat is a Java messaging application for a Programming POE project.

The application allows users to:
-Send messages
-Store messages
-disregard messages
-Create message ID's
-Create message hash
-Validate recipient numbers
-Store messages in a JSON file
-Unit test using the JUnit
---
feat: Initial commit - Set up ChatApp Maven project structure
Added Login.java, Main.java, Message.java,pom.xml, and gitignore.
Project structure set up with JUnit and org.json dependencies.
feat: Added a Message class with including a ID generation and hash generated.
feat: for loop was implemented to send user defined number of messages.
test: Used JUnit test for message the message number counter
ci: The test.java was updated to run the messageTest and the LoginTest
