# Coding-Domain-Task
This Repo include Content related to : 
1. Basic Of Linux
2. Git and GitHub
3. Arduino for Blinking of LED
# Basic Of Linux : 
# Git and GitHub :

## About

This section covers the basics of Git and GitHub. The objective of this task was to understand how version control works and how code can be managed, tracked, and shared using Git and GitHub.

## What I Learned

1. Git is a Version-Control software used to Track Changes made to Code.
2. GitHub is a Web-Based platform used to host Git Repo online.
3. Changes in code are saved in the form of Commits, which store When and What and When changes were made.

## Commands Practiced

 1. git clone
 2. git status
 3. git add
 4. git commit
 5. git push
 6. git pull
 7. git branch
 8. git log
 9. git reset  

## Conclusion

1. This task helped me understand how developers manage code versions and collaborate using Git and GitHub.
2. Working in the terminal using Git commands was a new and valuable learning experience.

#  Arduino for Blinking of LED
## About
This project demonstrates LED blinking using Arduino, where a push button toggles the LED blinking ON and OFF.

## Components Used
1. Arduino Board
2. Arduino IDE
3. LED
4. Push Button

## Concept
1. Digital input and output
2. Toggle logic using push button
3. INPUT_PULLUP for stable input
4. Delay for blinking speed

## Working Principle
1. Button press toggles the LED blinking state.
2. Once ON, the LED keeps blinking without holding the button.
3. A small delay is used for debouncing to avoid false triggers.

```cpp
if (button == LOW && lastButton == HIGH) {
    ledOn = !ledOn;
    delay(100);
}
lastButton = button;
```
