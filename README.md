# Year Progress

A minimalist, single-file web application that visualizes the current year as a grid of dots. It serves as a visual reminder of time passed, time remaining, and the importance of focusing on the present.

## Features

* **Visual Time Grid:** See the whole year at a glance. Past days are green, the current day pulses cyan, and future days are dark gray.
* **Focus Mode:** Toggle to dim past days, keeping your visual focus entirely on today and tomorrow.
* **Live Clock & Midnight Transitions:** A real-time clock that automatically shifts the "present" dot at midnight without needing a page refresh.
* **Stat Tracker:** Click the progress text to toggle between "% Complete" and "Days Left".
* **OLED-Friendly:** Pure black background with a subtle, automatic "pixel shift" animation after 2 minutes of idle time to prevent screen burn-in.
* **Zero Dependencies:** Built entirely with vanilla HTML, CSS, and JavaScript. No frameworks or external libraries required.
* **Responsive Design:** Automatically adjusts the grid layout for mobile and desktop screens.

## Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** CSS Variables, Grid, Flexbox, and Keyframe Animations.
* **Vanilla JavaScript:** DOM manipulation, date calculations, and `localStorage` for saving user preferences.

## Motivation

This project was inspired by stoic philosophy—specifically the idea of visualizing our most finite resource: time. It includes rotating quotes to remind us to make the best use of the present moment.
