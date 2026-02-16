# Pomodoro Timer

A simple and elegant Pomodoro Timer desktop application built with Electron.

## Features

- 25-minute work sessions
- Start, Stop, and Reset controls
- Alert notification when the session ends
- Clean, modern UI with gradient background
- Compact, frameless window design

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lorddrago12/Pomodoro-Timer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pomodoro-timer
   ```

3. Install dependencies:
   ```bash
   npm install electron --save-dev
   ```

## How to Run

Start the application:
```bash
npm start
```

## How to Use

- Click **Start** to begin your 25-minute Pomodoro session
- Click **Stop** to pause the timer
- Click **Reset** to reset the timer to 25:00
- When the session ends, an alert appears and the timer automatically resets to 25:00

## The Pomodoro Technique

1. Work for 25 minutes
2. Take a 5-minute break
3. Repeat
4. After 4 cycles, take a longer 15–30 minute break

## Project Structure

```
pomodoro-timer/
├── main.js          # Electron main process
├── index.html       # Application UI structure
├── script.js        # Timer logic (start, stop, reset, countdown)
├── styles.css       # Styling and layout
├── package.json     # Project configuration and dependencies
└── README.md        # Project documentation
```

## Technologies Used

- **Electron** - Desktop application framework
- **HTML/CSS/JavaScript** - Core web technologies
- **Pixeboy Font** - Custom pixel font for retro aesthetic

## License

This project is open source and available under the [MIT License](LICENSE).

## Preview 

<img width="350" height="307" alt="image" src="https://github.com/user-attachments/assets/510819fa-e061-417b-8f52-4924da6c5812" />
