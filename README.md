# Gradle

#gradle -v list information about gradle and it also confirm that gradle is installed and environment variable is set correctly
------------------------------------------------------------
Gradle 2.2.1
------------------------------------------------------------

Build time:   2014-11-24 09:45:35 UTC
Build number: none
Revision:     6fcb59c06f43a4e6b1bcb401f7686a8601a1fb4a

Groovy:       2.3.6
Ant:          Apache Ant(TM) version 1.9.3 compiled on December 23 2013
JVM:          1.8.0_20 (Oracle Corporation 25.20-b23)
OS:           Windows 7 6.1 amd64

#also we can list all the task of gradle by passing the command
gradle tasks
#but it list only main task and the default task provided by gradle 
------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------

Build Setup tasks
-----------------
init - Initializes a new Gradle build. [incubating]
wrapper - Generates Gradle wrapper files. [incubating]

Help tasks
----------
components - Displays the components produced by root project 'HelloWorld'. [incubating]
dependencies - Displays all dependencies declared in root project 'HelloWorld'.
dependencyInsight - Displays the insight into a specific dependency in root project 'HelloWorld'.
help - Displays a help message.
projects - Displays the sub-projects of root project 'HelloWorld'.
properties - Displays the properties of root project 'HelloWorld'.
tasks - Displays the tasks runnable from root project 'HelloWorld'.

Other tasks
-----------
groupTherapy
helloWorld

#here other task is defined by developer and to list all dependent task as well 
gradle tasks --all

#also we can run a task as below
gradle hellowWorld,
 or 
gradle hWorld,
 or
gradle hW

# above all three command will return same o/p
