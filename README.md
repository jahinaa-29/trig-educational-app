# Angle Explorer
## Interactive MATLAB Triangle Learning App for Middle School Students

> Voted Best App & Overall Project by peers in Foundations of Engineering Design Thinking II (ENED 1120) course


## Description

Angle Explorer is a gamified educational app built in MATLAB App Designer. It teaches middle schoolers the Pythagorean Theorem and basic trigonometry (sin, cos, tan) through interactive visualizations, a lives system, and a friendly triangle mascot.

It was inspired by Duolingo and Khan Academy. The goal was to make math feel less like homework and more like a game.



## Features

- **Live Triangle Visualization**: Sliders and input fields dynamically update the 
  triangle in real time. Adjust a side length and watch the angles recalculate instantly, 
  and vice versa
- **Lives System**: Wrong answers cost a life, which adds game-like stakes without discouraging students
- **Hints and Cheat Sheet**: On-demand hints, a quick-reference cheat sheet, and 
  solution reveals to support different learning speeds
- **Lesson and practice modes**: Structured lesson pages for each concept, plus a practice mode with a list of problems.
- **Angle Explorer Mascot**: An original animated triangular character that guides 
  students through the experience.
- **Error Handling**: Empty or invalid inputs are caught so the app doesn't break mid-session.


## App Preview

<details>
<summary><b>Click to view Screenshots and Descriptions</b></summary>
  
### 1. Home Page/Menu
A simple, easy-to-navigate UI designed to be engaging and vibrant for middle schoolers. Students pick one of two concepts to learn in Lesson Mode.

<img width="1238" height="892" alt="Home Page" src="https://github.com/user-attachments/assets/38aa12f1-bf6a-4cfb-aefe-50740ad875a4" />

### 2A. Lesson Page: Pythagorean Theorem
An interactive lesson with live triangle rendering. Adjust any side and the visualization updates in real time, showing how changing one value affects the rest. A cheat sheet lists the key rules, including the Pythagorean formula and the types of triangles by angle.

<img width="1239" height="892" alt="Pythagorean Theorem Lesson Page" src="https://github.com/user-attachments/assets/a32f9880-2e04-4743-b540-73c153dd9414" />

### 2B. Lesson Page: Trigonometric Functions
An interactive lesson on sine, cosine, and tangent. Students draw a right triangle, then use the Playground sliders to change the opposite side, adjacent side, and angle θ. The hypotenuse and the sin, cos, and tan values update live. A cheat sheet covers SOH-CAH-TOA and the values for common angles (0°, 30°, 45°, 60°, 90°).

<img width="1239" height="892" alt="Trigonometric Function Lesson Page" src="https://github.com/user-attachments/assets/1e8d7111-8a32-45e9-800f-0bc7d28c9306" />

### 3. Practice Mode
Students answer triangle problems with three lives. Wrong answers cost a life and show encouraging feedback ("Not quite! Try again!"). A Hint button helps when they're stuck, and Show Solution reveals the answer with a step-by-step explanation.

<img width="1239" height="892" alt="Practice Launch Page" src="https://github.com/user-attachments/assets/d268b1cb-a72d-4cf6-9813-c2c73b03a75b" />
<img width="1239" height="892" alt="Practice Sample Page Features" src="https://github.com/user-attachments/assets/51822760-1f78-4a57-8f8c-746adef8690e" />

</details>

## How to Run

**Requirements:** MATLAB with App Designer. The app was built in R2025a, so use R2025a or newer. Older releases may not open the .mlapp files.

1. Clone or download this repository.
2. Open MATLAB and navigate to the project folder.
3. Open home_page.mlapp in App Designer. Each page has its own .mlapp file, so start from the home page.
4. Click Run ▶.



## Built With

- MATLAB App Designer
- MATLAB R2025a



## Author
Name: Aisha Arina Jahin  
Course: Foundations of Engineering Design Thinking II (ENED 1120) at University of Cincinnati  
Date: May 2025 - July 2025  

### My Contribution
This was a group project with three parts:
- The app (this repository): I coded the app's UI and all of the features listed above independently.
- Documentation: handled by teammates.
- Physical product: built by another teammate. As the course required, it was developed separately from the app and isn't connected to this codebase.

## Future Improvements
- Add more topics (e.g. angle sums, triangle classification, area)
- Difficulty levels in practice mode
- Progress tracking across sessions
- A standalone version so students don't need a MATLAB license

## Acknowledgments
Inspired by Duolingo and Khan Academy.
