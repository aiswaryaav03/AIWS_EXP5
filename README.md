# AIWS_EXP5
TASK_1
# JavaScript Utility Projects

A collection of interactive web applications focusing on **asynchronous JavaScript**, **DOM manipulation**, and **CSS3 animations**.

---

## 1. Speed Quiz App with Timer
A high-pressure MCQ application that tests user knowledge under a strict time limit.

###  Features
*   **Countdown Timer:** 10-second total duration using `setInterval()`.
*   **Visual Warnings:** Displays a "Only 5 seconds remaining!" alert when the clock hits 5s.
*   **Auto-Submission:** Automatically calculates and submits results if the timer reaches zero.
*   **State Management:** Disables all inputs post-submission to prevent late changes.
*   **Responsive Design:** Vibrant, mobile-friendly UI with gradient backgrounds.

###  Technical Implementation
- **Logic:** Uses `FormData` for efficient answer extraction.
- **Timing:** Implements `clearInterval()` to halt execution upon manual submission.
- **Styling:** CSS3 Flexbox and "Blink" keyframe animations.
