---
layout: project
type: project
image: images/sudoku3.png
title: Recursive Sudoku Solver
permalink: projects/SudokuV1
# All dates must be YYYY-MM-DD format!
date: 2021-10-01
labels:
  - Github
  - Java
summary: A recursive Sudkou Solver with holiday ASCII art
projecturl: https://hnlcory.github.io/projects/SudokuV1
---

<img class="ui medium left floated rounded image" src="https://hnlcory.github.io/images/sudoku2.jpeg">

With a necessary quarantine period leaving me with several days of isolation with my laptop, I figured the best way to pass the time would be to revisit an older project that revolves around a pastime of Sudoku. This recursive sudoku solver was built in Eclipse using Java. It is based around a similar project from a previous ICS course I took in my freshman year. 

While the original was hardcoded to solve a handful of problems, had several bugs, and partially followed a proper code style guideline, this version now included a user interface where the user has the ability to input any sudoku problem to be solved via recursion.

<img class="ui medium right floated rounded image" src="https://hnlcory.github.io/images/sudoku1.png">

The program can also detect invalid sudoku problems as well as invalid user input. Because of its proximity to the holidays, the program also included some ASCII art. 

This project also included my first introduction to the AppleScript Programming language in order to get the .jar file to properly run on a Mac. Getting the .jar file to open on 
mac took a small script shown below.
<br />
```
tell application "Terminal"
	if not (exists window 1) then reopen
	activate
	
  set the bounds of the front window to {0, 0, 1100, 538}
	-- x - x position in pixels
	-- y - y position in pixels
	-- w - width in pixels
	-- h - height in pixels
	
  do script "cd desktop" in front window
	do script "cd SudokuSolver" in front window
	do script "clear" in front window
	
  do script "java -jar Sudoku.jar" in front window
end tell
```

You can learn more at [this Github link](https://github.com/hnlcory/projectPrograms/tree/main/Final%20Sudoku).


