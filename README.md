# Calendar-Management-System
This project is a Calendar Management System developed in Python with a user-friendly Tkinter graphical user interface (GUI). The system allows users to manage events efficiently, including adding, removing, and visualizing events on a calendar.

Features
Add Event: Users can add events to the calendar by specifying the date, start time, duration, and event name. The system checks for overlapping events and provides appropriate error messages.

Remove Event: Users can remove events from the calendar by providing the date and start time. The system handles multiple slots covered by the event and notifies the user if the event doesn't exist.

Print Calendar to Excel: The system can export the calendar to an Excel file with a visually appealing format. The file includes different colors for dates and events, proper cell widths, and text wrapping.

Event Statistics: Users can inquire about the number of events on a given day and the number of free hours available on a specific date.

Exit Functionality: The system allows users to exit the program, and upon exit, it saves the printed calendar to an Excel file with a timestamp.

Additional Notes
* The system prevents events from spanning multiple days.
* Error handling is implemented for various scenarios, such as adding to an occupied time slot or removing a non-existent event.
* The GUI provides an intuitive interface with entry fields, buttons, and a text widget for displaying the calendar.

How to Use
* Run the program.
* Use the provided entry fields to add or remove events.
* View the current state of the calendar in the text widget.
* Export the calendar to Excel for a visually appealing format.
* Inquire about event statistics for a specific date.
* Exit the program, and a timestamped Excel file of the printed calendar will be saved.

Requirements
* Python 3.x
* pandas
* tkinter
* openpyxl

Acknowledgments
This project was inspired by the need for a simple yet effective calendar management system. It showcases the integration of pandas for data handling and Tkinter for building a graphical user interface.

Feel free to contribute to the project, report issues, or suggest improvements!
