# Noti 
Get notified when your build/executable is complete

## To Use
```
Add a new PATH variable to the computer with the location of the shell file:
C:\...\noti\exec

To build project replace prefix build command or executable with noti:
> noti mvn clean install
> noti ./my_program

Default time out: 5s
Configurable inside noti file
```

## Issue
At work everytime I do mvn clean install it feels like i'm waiting a year and then I'll go look at some other stuff forget about it and then come back later when it's been done and waiting. 
Update: I was working with some rust stuff and thought this would be nice to have for running executables too when they take a bit to run, so now it works for that too!

## Solution
Program that builds the project and notfiy's the user when program is built/run with a sound and pop up that shows the build status.
