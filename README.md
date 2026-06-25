# To-Do List Reminder App

Prioritize Tasks and work smarter!

A simple web-based To-Do Reminder application built using HTML, CSS, and JavaScript. It helps users manage tasks, track deadlines, and receive reminders when tasks become overdue.

## Features

- Add tasks with a title, description, and deadline.
- Automatically categorize tasks into:
  - Upcoming Tasks
  - Tasks Due Within 24 Hours
  - Past Deadline Tasks
- Visual alert for overdue tasks.
- Audio notification when a deadline is reached.
- Delete tasks individually.
- Tasks are stored using browser Local Storage.
- Automatically removes tasks 3 days after their deadline.
- Responsive and user-friendly interface.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Local Storage API

## How It Works

- Users create tasks by entering a title, description, and deadline.
- Tasks are saved locally in the browser.
- The application continuously checks task deadlines.
- Overdue tasks are highlighted and moved to the Past Deadline section.
- Tasks overdue for more than 3 days are automatically removed.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/todo-reminder-app.git
```

2. Open the project folder.

3. Run `index.html` in your browser.

## Project Structure

```text
todo-reminder-app/
│
├── index.html
└── README.md
```
