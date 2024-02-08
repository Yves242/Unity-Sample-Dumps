# C Pointer Concept Illustrator

## Project Preview

![image](https://github.com/Yves242/Unity-Sample-Dumps/assets/70612985/7b0fff68-7db4-417b-a5d8-fabfdcfd0876)


## Project Overview

The "C Pointer Concept Illustrator" project is a Unity application designed to provide an interactive and educational experience for understanding C pointer concepts. This README file provides instructions on how to run the executable files for the game on both Windows and Linux operating systems. This program is currently in development for Yves' special problem (SP). These are simply snapshots of his current SP for showcasing. 



## Getting Started

### Running on Windows

1. Navigate to the `windows` folder. 
2. Select the specific folder version you would like to view.
3. Double-click on the executable file named `C Pointer Concept Illustrator.exe`.
4. The application should launch on your Windows machine.
5. You can import sample codes from the `main/Windows/Code Presets` GitHub repository.  

### Running on Linux

1. Navigate to the `linux` folder.
2. Select the specific folder version you would like to view.
3. Open a terminal in this directory.
4. Run the following command to give execute permissions to the Linux executable:
   ```
   chmod +x <file_version>.x86_64
   ```
5. Run the game using the following command:
   ```
   ./<file_version>.x86_64
   ```
6. The application should launch on your Linux machine.
7. You can import sample codes from the `main/Linux/Code Presets` GitHub repository.  

## Finished Developments
- Adding of controls pane buttons with clickability functionality.
- Creating own cursor icons and assigning the appropriate icons at appropriate events.
- Setting up of the codes pane with dynamically-allocated line numbers.
- "Mastering" of the GUI for the 963x507 SP program resolution.
- Notification panel implmentation, with event-driven checks on string inputs in the codes pane.
- Go-to-line feature with appropriate animations and warning and error handlers.
- Go-to-line error message handling.
- Normal highlighting function on a given specific line number. Believe it or not, I implemented these using textboxes and strings.
- Go-to-line and codes pane highlight syncing.
- Error-specific highlighting when a character limit error is detected. Believe it or not, again, implemented using textboxes and texts.
- Native pop-up file dialogues for importing and saving files. I used an open-source unity package for this one.
- Lexical analysis for preparation of syntactical analysis.
- Frequent optimization of codes for improving the run-time of the program while having code organizations and modularizations as well for efficient application management.


## Currently in Development
- Clicking the `[line xx]` button must show the given line with appropriate highlight and syncing at the appropriate event.
- The raycasted area in the `[line xx]` button must adjust dynamically to make the clickable area "natural".


## Future Developments
- Syntactical Analysis  
- Add error handlers for syntactically-incorrect lines.
- Create the internal architecture for the virtualization of memory of variables, pointers, and references.
- Create meaningful sample-debug files.
- Code-specific animations for the play, pause, and stop buttons.
- Code-specific animations for the next, previous, and go-to-line buttons.
- Implement saving of code files.
- Add the credits page.
- Resolve unforeseen bugs which will inadvertently reveal itself during the app development process.
- Acquire feedback from student-users and professor-users (target is somewhere as early as March, 2024).
