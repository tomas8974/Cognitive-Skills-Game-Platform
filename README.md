# Cognitive Skills Game Platform

**Team members:** Tomas Kazonas, Artiom Garbul, Linas Baužys

This project was part of the Software Engineering 1 course at Vilnius University in 2024 Autumn semester.

## Project Description

A web-based platform for improving cognitive skills through games. The platform targets students looking to improve academic performance, working professionals seeking productivity gains, and older adults wanting to maintain mental sharpness.

Users can create an account, play games across different cognitive domains, and track their weekly progress through interactive charts.

[Demo (Youtube)](https://youtu.be/JFUmXtkABJ0)

---

## Games

| Game | Skills Trained |
|---|---|
| **Math Game** | Logical thinking, problem solving — solve as many math problems as possible within a time limit |
| **Aim Trainer** | Reaction speed — click as many targets as possible before time runs out |
| **Pair Up** | Memory and attention — match all card pairs in the shortest time with fewest mistakes |
| **Sudoku** | Logic and focus — fill a 9×9 grid so each row, column, and 3×3 box contains digits 1–9 |

Aim Trainer, Pair Up, and Sudoku each offer multiple difficulty levels. Sudoku also supports non-standard 4×4 and 16×16 grid modes.

---

## Features

- **Anonymous playing** - users can play games without creating an account. Scores are saved in the local browser storage
- **Account system** — register and log in to save your progress
- **Leaderboard** - compare your results with other players
- **Privacy settings** - users can set privacy settings to hide their highscore from the leaderboard
- **Progress tracking** — view your results and weekly improvement per game
- **Interactive charts** — visualizes your performance over time

---

## Used Technologies

- **Blazor**  — Frontend (C#, HTML/CSS)
- **Chart.js** — JavaScript library for rendering progress charts
- **ASP.NET Core** - REST API backend (C#)
- **SQLite** — lightweight database for storing user data and results

---

## How to Run

1. Clone the repository
2. Open the solution in Visual Studio
3. Build and run — **Debug → Start Without Debugging** (`Ctrl + F5`)

---

## Possible Future Improvements

- Achievements system to boost motivation and engagement
- Additional games targeting creativity (e.g. story builder)
- Expanded difficulty options and game modes
