(Copy and Paste from old git account Gpannu78)

# 🎮 Trivia Game

A collaborative Java-based trivia/quiz game built with a graphical user interface (GUI) as part of the **CP213 – Object-Oriented Programming** course project.

---

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

---

## About the Project

Trivia Game is an interactive quiz application where players answer multiple-choice trivia questions across various categories and difficulty levels. The project was developed collaboratively to demonstrate core OOP principles including encapsulation, inheritance, and event-driven programming using Java's GUI libraries.

---

## Features

- 🖥️ Graphical user interface built with Java Swing / JavaFX
- ❓ Multiple-choice trivia questions
- 📊 Score tracking across rounds
- 🗂️ Questions organized by category and/or difficulty
- 🔄 Randomized question order per game session

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- **Java JDK 17+** — [Download here](https://www.oracle.com/java/technologies/downloads/)
- **Git** — [Download here](https://git-scm.com/)
- *(Optional)* An IDE such as [Eclipse](https://www.eclipse.org/) or [IntelliJ IDEA](https://www.jetbrains.com/idea/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/GPannu78/CP213CollabProject.git
   cd CP213CollabProject
   ```

2. **Open in your IDE** (recommended) or compile via terminal.

### Running the Game

**Using an IDE:**
- Import the project as an existing Java project
- Locate the `Main.java` (or equivalent entry point) file
- Click **Run**

**Using the terminal:**
```bash
# Compile
javac -d out src/**/*.java

# Run
java -cp out Main
```

> ⚠️ If you encounter any classpath issues, ensure your IDE's build path includes all `src` folders.

---

## Project Structure

```
CP213CollabProject/
├── src/
│   ├── application/        # Entry point (Main.java)
│   ├── model/              # Data models (Question, Player, Score, etc.)
│   ├── view/               # GUI screens and panels
│   └── controller/         # Game logic and event handling
├── resources/
│   └── questions/          # Trivia question data files
├── README.md
└── .gitignore
```

> 📝 *Folder names may vary slightly — refer to the actual source tree after cloning.*

---

## Contributors

| Name | GitHub |
|------|--------|
| Gurnoor Pannu (old account)| [@GPannu78](https://github.com/GPannu78) |
| Gurnoor Pannu | [@Thebossnoor](https://github.com/Thebossnoor) |
| Gurbeer Pannu | [@GurbeerPannu4](https://github.com/GurbeerPannu4) |

---

> Built for **CP213 – Object-Oriented Programming** · Wilfrid Laurier University