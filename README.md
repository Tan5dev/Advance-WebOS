# WebOS

A desktop-like operating system implemented in a web browser, using React, TypeScript, Vite and Zustand. No backend or database required.

Main Features

Desktop
WebOS has a desktop where you can move icons around
Apps can be opened in windows
Windows can be moved, resized, minimized, maximized and closed
Taskbar with running and pinned apps
Start Menu to open apps
Right-click for extra options
Dark, Light and Midnight themes
Boot animation and lock screen
Simple sound effects included

Keyboard Shortcuts

Ctrl + ` to open/focus Terminal
Ctrl + E to open/focus File Explorer
Ctrl + , to open/focus Settings
Escape to close Start Menu

File System

WebOS has its own virtual file system
Files and folders are stored in localStorage
Cannot create two files or folders with the same name in one location
System files and folders are protected
The System Apps folder cannot be modified
Can reset file system if saved data becomes corrupted

Apps

File Explorer
View and manage files and folders
Create files and folders

Move files by dragging them
Rename, move, open and delete files
Text Editor
Write and edit text
Save a file, or use Save As to save a file with a new name
Shows word and character count
Paint
Draw on a canvas
Choose color, brush size and eraser
Undo drawings
Save drawings and download as PNG
Open previously saved image files
Terminal
Simple command-line utility
Includes commands like help, whoami, date, echo, clear, pwd, ls, cd, cat, mkdir, touch, rm, open and neofetch
Use open to open apps
Calculator
Can calculate simple and complex mathematical expressions
Includes addition, subtraction, multiplication, division, exponents, percentages and parentheses
Can be used with keyboard shortcuts
Browser
Start page with clock, search bar and quick links
Search Wikipedia or enter a web address
Includes a home button and loading bar
Clock
Includes World Clock, Stopwatch and Timer
World Clock shows the time in 5 different time zones
Stopwatch can track lap times
Timer has a countdown and sound effect when done
Task Manager

Shows all open apps
Can focus or close apps
Shows some system information like uptime, window count, theme and memory usage
Can close all tasks
Settings
Change theme, wallpaper, username, accent color and sound effects
Can reset WebOS to factory settings
About Me
A simple page with portfolio information
Can be edited as a text file
Saving and Safety

WebOS uses Zustand to save the file system and settings
The open window list is not saved on page reload
WebOS has version updates to add new features without losing files
Factory reset option available
WebOS can recover if saved data becomes corrupted
Design
WebOS works on different screen sizes
Has reduced motion option for people who do not want animations
The taskbar, Start Menu and menus have a blurred background
Active windows can have a glow
Desktop icons move slightly when hovered over
Dragging files shows where they can be dropped<br>
Technology Used
React 18, 
TypeScript 5,
Vite, 
Zustand,
Lucide React,
CSS,
Web Audio API,
localStorage,
Vercel.

How to Run<br>
Clone the project from GitHub<br>
Open the project folder<br>
Run npm install to install the necessary packages<br>
Run npm run dev to start the project<br>
Run npm run build to build the production version<br>
Run npm run preview to preview the production version<br>

Project Folders

The src folder contains the main code<br>
The apps folder contains all the apps<br>
The lib folder contains shared code<br>
The shell folder contains the desktop, taskbar, menus and windows<br>
The stores folder contains saved data and settings<br>
The styles folder contains CSS<br>
The types folder contains TypeScript types<br>
App.tsx is the main app component<br>
main.tsx starts the application<br>

License

WebOS uses the MIT License.