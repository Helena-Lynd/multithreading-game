# multithreading-game<br>
A Java program that utilizes multithreading to simulate an obstacle course game similar to wipeout.

![ProgramResults](https://github.com/Helena-Lynd/multithreading-game/blob/main/multithreading-output.png?raw=true)

## Description<br>
The game of wipeout is an obstacle course that a certain number of contenstants can attempt to clear at the same time, and if a contestant falls off the course they
have to restart. This program simulates that game with a "line" of contestants waiting to get in the course, and a synchronized method that controls how many
contestants can attempt to clear the course at the same time. There is a random chance for a contestant to fall of the course as they cross it, and if they do they
must enter the back of the line and try again. The simulation ends once all contestants have completed the course.

## Getting Started<br>
### Dependencies
- Java 18+
- IntelliJ IDE
### Installing
- Download the source files provided to your directory of choice
```
git clone git@github.com:Helena-Lynd/multithreading-game.git
```
### Executing
- Open the project in IntelliJ
- Play any of the given run configurations
## Common Errors
"Imports could not be resolved"
- Ensure that your JDK is configured for the project
- Right-click on the "src" folder and <i>Mark as Sources Root</i>
## Authors<br>
Helena Lynd
