Problemica

Problemica is a browser-based adaptive arithmetic training application designed to improve mental math speed and accuracy. The application dynamically adjusts difficulty based on user performance and provides real-time feedback, performance metrics, and visual analytics.

Features

Adaptive Difficulty Engine

Automatically increases or decreases difficulty based on correct and incorrect answers.

Configurable difficulty scaling (Easy, Normal, Hard).

Operation Selection

Supports:

Addition (+)

Subtraction (−)

Multiplication (×)

Division (÷)

Users may select one or multiple operations.

Real-Time Feedback

Immediate visual feedback for correct and incorrect answers.

Audio feedback using sound effects.

Performance Metrics

Score tracking

Accuracy percentage

Correct calculations per minute (CPM)

Analytics Visualization

CPM progression plotted using Chart.js.

Mistake Review

Displays all incorrect answers at the end of a session.

Technologies Used

HTML5 – Application structure

CSS3 – Responsive UI and theming

Vanilla JavaScript (ES6) – Application logic and state management

Chart.js – Performance visualization

No backend or frameworks are required.

How It Works

Select one or more arithmetic operations.

Choose a difficulty level:

Easy (slow adaptation)

Normal

Hard (fast adaptation)

Press Start.

Answer questions using the keyboard and press Enter.

The difficulty adapts automatically based on performance.

Press Finish to view detailed results and analytics.

Difficulty System (Technical Overview)

Difficulty is controlled using a difficulty factor.

Correct answers increase difficulty by a configurable rate.

Incorrect answers decrease difficulty.

Difficulty values are clamped to prevent unrealistic number ranges.

Division questions are generated to always produce whole-number results.

File Structure
/
├── index.html        # Main application file
├── p2.png            # Favicon
└── README.md         # Project documentation

Browser Compatibility

Chrome (recommended)

Firefox

Edge

Safari

Future Improvements (Planned)

Persistent user profiles

Session history storage (LocalStorage / IndexedDB)

Timed challenge mode

Mobile-first optimizations

Multiplayer or leaderboard support

License

This project is released for educational and personal use.
You may modify and distribute it freely.

Author

Mohammed Ali
