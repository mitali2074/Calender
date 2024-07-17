# Calendar Application

This project is a fully functional calendar application built with JavaScript, HTML, and CSS. It allows users to navigate through months, view the current date, and manage events. The calendar dynamically generates the current month and includes days from adjacent months for full week rows. Users can switch months using navigation buttons or jump to a specific date by entering it in MM/YYYY format.

Event management features let users add, view, and delete events, with highlighted days showing scheduled activities. Event data is stored in the browser’s local storage for persistence across sessions. The code initializes key HTML elements and date variables, calculates the necessary days for display, and dynamically updates the calendar. Functions for month navigation, day selection, and event updates ensure smooth interaction. Events are validated for correct input and formatted in 12-hour AM/PM time. The application provides a user-friendly experience for managing events in a browser-based calendar.

## Features

- Navigate through months using navigation buttons.
- Jump to a specific date by entering it in MM/YYYY format.
- Add, view, and delete events.
- Events are highlighted on the calendar.
- Event data is stored in the browser’s local storage for persistence.
- Responsive design for various screen sizes.
- Accessible with ARIA labels and keyboard navigation support.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/calendar-application.git
    ```
2. Navigate to the project directory:
    ```bash
    cd calendar-application
    ```
3. Open `index.html` in your preferred web browser.

## Usage

1. Use the navigation buttons to switch between months.
2. Enter a date in MM/YYYY format to jump to a specific date.
3. Click on a day to add an event.
4. View and delete events by clicking on highlighted days.

## Development Progress

### Week 1

#### Day 1 (22/5/2024):
- **Project Initialization:** Set up the project repository and created initial project structure with HTML, CSS, and JavaScript files.
- **Research:** Researched best practices for creating a calendar application.

#### Day 2 (23/5/2024):
- **Basic HTML Structure:** Developed the basic HTML structure for the calendar including divs for the header, month navigation, and the calendar grid.
- **CSS Styling:** Started basic styling for the calendar layout and navigation buttons.

#### Day 3 (24/5/2024):
- **JavaScript Setup:** Initialized JavaScript variables and functions to handle the current date and month display.
- **Current Date Display:** Implemented functionality to display the current month and year in the header.

#### Day 4 (27/5/2024):
- **Calendar Grid Generation:** Created a function to dynamically generate the days of the current month in the calendar grid.
- **Adjacent Month Days:** Added functionality to include days from the previous and next months to ensure full week rows.

#### Day 5 (28/5/2024):
- **Month Navigation:** Developed navigation buttons to switch between months.
- **Date Calculation:** Implemented date calculations to correctly update the calendar when navigating months.

#### Day 6 (29/5/2024):
- **Jump to Date:** Added an input field and button to allow users to jump to a specific date by entering it in MM/YYYY format.
- **Validation:** Implemented input validation for the date format.

#### Day 7 (30/5/2024):
- **Event Management UI:** Designed the user interface for adding, viewing, and deleting events.
- **Event Form:** Created a form for users to input event details including date, time, and description.

### Week 2

#### Day 8 (31/5/2024):
- **Local Storage:** Set up local storage to save event data persistently across sessions.
- **Event Data Structure:** Defined the data structure for storing events in local storage.

#### Day 9 (3/5/2024):
- **Add Event Functionality:** Developed functionality to add events to the calendar and save them in local storage.
- **Event Highlighting:** Implemented highlighting of days with scheduled events in the calendar grid.

#### Day 10 (4/5/2024):
- **View Events:** Added functionality to display a list of events when clicking on a highlighted day.
- **Event Display:** Styled the event list display for better user experience.

#### Day 11 (5/6/2024):
- **Delete Events:** Implemented functionality to delete events from the calendar and local storage.
- **Confirmation Dialog:** Added a confirmation dialog before deleting an event.

#### Day 12 (6/6/2024):
- **Event Validation:** Ensured events are validated for correct input, including date, time, and description.
- **Time Formatting:** Implemented 12-hour AM/PM time format for event times.

#### Day 13 (7/6/2024):
- **Code Refactoring:** Refactored code for better readability and maintainability.
- **Bug Fixes:** Fixed bugs related to month navigation and event management.

#### Day 14 (10/6/2024):
- **UI Enhancements:** Improved the overall user interface and user experience based on initial user feedback.
- **Accessibility:** Ensured the calendar is accessible by adding ARIA labels and keyboard navigation support.

### Week 3

#### Day 15 (11/6/2024):
- **Testing:** Conducted thorough testing of the calendar application including edge cases for date calculations and event management.
- **Bug Fixes:** Addressed issues found during testing.

#### Day 16 (12/6/2024):
- **Documentation:** Started writing documentation for the project, including how to set up and use the calendar application.
- **Code Comments:** Added comments to the code for better understanding and future maintenance.

#### Day 17 (13/6/2024):
- **Performance Optimization:** Optimized JavaScript code for better performance, especially in calendar rendering and event handling.
- **UI Performance:** Improved UI performance by minimizing reflows and repaints.

#### Day 18 (14/6/2024):
- **Feature Addition:** Added a feature to edit existing events.
- **UI Update:** Updated the event form to handle editing of events.

#### Day 19 (17/6/2024):
- **User Feedback:** Collected feedback from initial users and identified areas for improvement.
- **Enhancements:** Implemented minor enhancements based on user feedback.

### Week 4

#### Day 20 (18/6/2024):
- **Cross-Browser Testing:** Tested the application across different browsers to ensure compatibility.
- **Responsive Design:** Ensured the calendar layout is responsive and works well on various screen sizes.

#### Day 21 (19/6/2024):
- **Final Touches:** Made final adjustments and improvements to the application.
- **Final Testing:** Conducted a final round of testing to ensure all features work as expected.

#### Day 22 (20/6/2024):
- Prepared the project for deployment and published it on a web server.
- **Launch:** Officially launched the calendar application.


## Contact

For any questions or suggestions, please reach out to [22it073@charusat.edu.in].

---

### Acknowledgments

Thanks to everyone who provided feedback and suggestions during the development of this project.
