# Maven Notification
Get notified when your maven build has completed

## To Use
```
Add a new PATH variable to the computer with the location of the shell file:
C:\...\maven_noti\exec

To build project replace mvn clean install with:
> mvnc

Default command: mvn clean install
Default time out: 5s
Both are configurable inside mvnc file
```

## Issue
At work everytime I do mvn clean install it feels like i'm waiting a year and then I'll go look at some other stuff forget about it and then come back later when it's been done and waiting. 

## Solution
Program that builds the project and notfiy's the user when program is built with a sound and pop up that shows the build status.
