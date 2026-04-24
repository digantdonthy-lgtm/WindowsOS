# WindowsOS
MaxOS is a fully interactive, browser-based operating system built using HTML, CSS, and JavaScript. It simulates a real desktop environment by combining a multi-window interface, system-like controls, and built-in applications, all running inside a single web page.

The project features a Windows-inspired UI, including a bottom taskbar, desktop icons, and draggable application windows. Each app behaves like a standalone program, allowing users to open, move, and manage multiple windows simultaneously, closely mimicking the experience of a real operating system.

A custom window management system powers the core of MaxOS, enabling features such as window layering, boundary-restricted dragging, maximize/restore functionality, and controlled screen positioning to ensure a smooth and realistic user experience.

MaxOS includes several built-in applications:

Notes App with persistent storage using localStorage
Calculator with keyboard support and interactive UI
Browser capable of loading web pages within an iframe
Paint App using HTML5 canvas for drawing
Game Hub, a mini launcher that hosts multiple games with seamless in-app navigation

The Game Hub has been enhanced with a structured navigation system where games open within the OS and communicate with the main hub using message-based interaction, allowing users to return smoothly without breaking the interface.

The project emphasizes:

Realistic OS behavior inside a browser
Modular app design
Interactive UI/UX improvements
Problem-solving for browser limitations (like iframe restrictions and window control)
