# Analog-Clock-Project<br>
This script creates a graphical analog clock using the Tkinter library in Python. The clock has a customizable background image, and the positions of the hour, minute, and second hands are updated every second based on the current time. The code demonstrates the use of basic GUI elements, canvas drawing, and real-time updates in Tkinter.<br><br>
**Project Overview:** <br>
**1.Import Libraries**<br>
**tkinter:** For creating the GUI.<br>
**math:** For mathematical calculations to position the clock hands. <br>
**time:** For getting the current time.<br><br>
**2. Define the Clock Class**<br>
**Clock Class:** Inherits from Tkinter.Tk.<br>
**Initialization:** Sets up the main window and calls methods to create the canvas, background, clock hands, and starts the clock update.<br><br>
**3. Create Canvas**<br>
**create_canvas:** Initializes a canvas widget with a black background.<br><br>
**4. Create Background**<br>
**create_background:** Attempts to load and display a background image for the clock. If the image file is not found, an error message is printed.<br><br>
**5. Create Clock Hands**<br>
**create_sticks:** Creates three line elements (representing hour, minute, and second hands) on the canvas and stores them in a list.<br><br>
**6. Update Clock Hands**<br>
**update_clock:** <br>
Gets the current local time.<br>
Converts the hour, minute, and second to appropriate angles for the clock hands.<br>
Updates the position of each clock hand based on these angles.<br>
Schedules the update_clock function to run again after 1000 milliseconds (1 second).<br><br>
**7. Main Execution**<br>
Main Execution: Instantiates the Clock class and starts the Tkinter main event loop, which keeps the application running.<br>
