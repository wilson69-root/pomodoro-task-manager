# Pomodoro Task Manager

A modern, user-friendly Pomodoro timer with task management capabilities to help you stay focused and productive.

![Pomodoro Task Manager](https://via.placeholder.com/800x400?text=Pomodoro+Task+Manager)

## Features

- **Pomodoro Timer**: Customizable work intervals with automatic break timers
- **Task Management**: Add, track, and manage your daily tasks
- **Difficulty Levels**: Choose between Easy (15 min), Medium (25 min), and Hard (45 min) tasks
- **Break Timer**: Automatic break timer that adjusts based on task difficulty
- **Email Notifications**: Get notified when you complete a task (simulated)
- **Focus Streak Tracking**: Visual representation of your productivity streak

## How It Works

### Pomodoro Technique

The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks. This application implements this technique with some enhancements:

1. **Work Intervals**: Choose from three difficulty levels:
   - Easy: 15 minutes of focused work
   - Medium: 25 minutes of focused work
   - Hard: 45 minutes of focused work

2. **Break Intervals**: Automatically adjusted based on task difficulty:
   - Easy/Medium tasks: 5-minute break
   - Hard tasks: 15-minute break

### Task Management

1. **Adding Tasks**:
   - Enter a task description
   - Select the difficulty level
   - Optionally provide your email for notifications
   - Click "Add" to add the task to your list

2. **Task Timer**:
   - When you add a task, the timer automatically sets to the appropriate duration
   - Click "Start" to begin the Pomodoro session
   - The timer will count down and alert you when it's time for a break

3. **Break Timer**:
   - After completing a work session, a break timer automatically starts
   - The break duration is based on your task difficulty
   - You'll receive an alert when the break is over

### Email Notifications

The application includes a simulated email notification system:
- When you complete a task, an email notification is "sent" to the email address you provided
- This is currently simulated with a console log and alert
- In a production environment, this would connect to an actual email service

## Getting Started

1. Clone this repository
2. Open `index.html` in your web browser
3. Start adding tasks and using the Pomodoro timer!

## Customization

You can customize the application by modifying the following files:
- `index.html`: Change the structure and content
- `styles.css`: Modify the appearance and styling

## Future Enhancements

- User accounts and data persistence
- Statistics and productivity insights
- Customizable timer durations
- Sound notifications
- Mobile app version

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements

- Inspired by the Pomodoro Technique developed by Francesco Cirillo
- Designed with a focus on user experience and productivity
- Developed using vibe coding tools: ChatGPT, Cursor IDE, and ME 