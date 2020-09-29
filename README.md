### Refactoring Golf
`

_Refactoring Golf_ is a game designed to stretch your refactoring muscles and 
to get you to explore your IDE to see what's really possible using 
shortcuts and automation. The idea is to focus on one aspect of coding 
and see how far it can be pushed.

This repository contains multiple versions of a sotre management application.
Each version is a refactoring of the previous version. Sticking with the golf metaphor, 
each version is called a "hole". 

Your goal is to refactor from each _hole_ to the next safely and efficiently,
using the features of the IDE with as few "strokes" as possible, where a _stroke_ is 
an action that changes the code. Every stroke costs you points.

## Score table

- 0 points for formatting and selection
- 0 point for Ctrl + Z
- 0 for change access to methods or classes
- 1 point for every change made to the code using a shortcut or automated IDE feature 
  (e.g., an automated refactoring, code template, rename, or Find/Replace) 
- 1 delete a line with code
- 1 create classes, interfaces
- 2 point for every Copy + Paste 
- 2 points for every line manually edited.
- 2x point - _double points_ penalty for changes that leave the code failing the tests or not compiling.
- 3x point - penalty for changes while failing the tests or not compiling code.


## Hints
- Each version has a `notes.md` file that describes the motivation for the next refactoring.
- You might want to keep the target code open in another window, or perhaps on the partner's machine. 
It's easy to get confused about which file is which.
- Commit your code frequently, especially after each refactoring stage. That will make rolling-back easier 
if you want to make another attempt or if you get confused.
- Run the tests after each "stroke". You can do this by selecting the top-level *refactoring-golf* in 
the project view and selecting `Run 'All Tests'` from the pop-up menu. 
- Check your code in frequently so it's easier to try a refactoring more than once. Idea also has 
an excellent _Local History_ option. 


## Acknowledgements

<a href="https://github.com/jasongorman/RefactoringGolfJava">Refactoring Golf</a>.
https://github.com/sf105/refactoring-golf
