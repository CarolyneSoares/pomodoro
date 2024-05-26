# Pomodoro Timer Project

This project is a simple implementation of a Pomodoro timer using Python's Tkinter library. The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. This timer follows that method and includes features for resetting the timer, starting the timer, and displaying session completion with check marks.

## Key Features:

### Timer Setup:
- Work session: 25 minutes
- Short break: 5 minutes
- Long break: 20 minutes
- The timer cycles through work and break sessions, with a long break after four work sessions.

### User Interface:
- A Canvas widget displays a timer on top of an image of a tomato.
- Labels are used to show the current timer status (work or break) and check marks for completed sessions.
- Buttons to start and reset the timer.

### Timer Mechanism:
- `start_timer()`: Determines whether to start a work session, short break, or long break based on the number of completed sessions (`reps`).
- `count_down(count)`: Handles the countdown for each timer interval and updates the display.

### Reset Functionality:
- `reset_timer()`: Stops the current timer, resets the session count, and updates the display.
