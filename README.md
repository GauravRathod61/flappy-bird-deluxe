# 🐤 Flappy Bird Deluxe Edition (C++ Console Game)

Welcome to **Flappy Bird Deluxe Edition**, a feature-packed console-based game made with pure C++!  
This is a **console clone** of the classic Flappy Bird game with exciting new features, difficulty levels, skins, scoring, animations, and more — all built without any game engine!

---

## 🎮 Game Features

- 🚀 **Three Bird Skins** – Classic, Rocket, UFO
- ⚙️ **Three Difficulty Levels** – Easy, Medium, Hard
- 💥 **Power-Ups (Coming Soon)** – Speed boost, invincibility, etc.
- 🧱 **Animated Pipes** – Moving obstacles with gaps
- 💯 **Score and Level System**
- 🏆 **High Score Saving** – Automatically saves your highest score locally
- 🎨 **Colored Graphics using Console Colors**
- ⏸️ **Pause and Resume Functionality**
- ❌ **Game Over Screen with Custom Message**
- 🎬 **Animated Title Screen**
- 💡 **Clean and Structured Code** – Easy to read, edit, and expand!

---

## 🛠️ Tech Stack

- **Language:** C++
- **Libraries Used:** `<iostream>`, `<conio.h>`, `<windows.h>`, `<fstream>`, `<stdlib.h>`, `<string.h>`, `<time.h>`
- **Platform:** Windows Console Application

> Note: This game uses Windows-specific libraries (`<conio.h>` and `<windows.h>`) and may not work on non-Windows platforms without modification.

---

## 📂 Project Structure

**MAIN FILE** 1.cpp 
**STORE HIGHSCORE** highscore.txt
---

## 🕹️ How to Play

| Control Key | Action                     |
|-------------|----------------------------|
| \`Spacebar\`  | Bird Flies Up              |
| \`P\`         | Pause / Resume             |
| \`ESC\`       | Exit Game                  |

- Navigate the bird through the gaps in the pipes.
- Each successful pass earns you a point.
- Hit a pipe or the ground — and it's game over!

---

## 📈 Scoring and Levels

- Every pipe passed increases your score by **+1**
- Every **5 points**, the game level increases and the speed becomes faster.
- Your **highest score is saved** and displayed in the main menu.

---

## 🧵 Code Overview

Here are some important sections of the code:

- \`drawBird()\` – Renders the bird character on screen based on your selected skin
- \`drawPipe()\` / \`erasePipe()\` – Draws and clears the pipes
- \`collision()\` – Detects collisions with pipes
- \`play()\` – Main game loop handling input, drawing, logic, and score
- \`selectSkin()\` – Lets you choose your bird's appearance
- \`selectDifficulty()\` – Adjusts game speed
- \`updateScore()\` – Updates the UI on the right panel
- \`animatedTitle()\` – Intro animation before menu appears

> Want to customize? Go ahead and tweak the skins, colors, speeds, or scoring system!

---

## 🚀 Getting Started

### 1. Clone the Repository

\`\`\`bash
git clone https://github.com/your-username/Flappy-Bird-Deluxe.git
cd Flappy-Bird-Deluxe
\`\`\`

### 2. Compile the Game

Use any C++ compiler that supports Windows libraries. For example:

\`\`\`bash
g++ FlappyBirdDeluxe.cpp -o flappy.exe
\`\`\`

### 3. Run the Game

\`\`\`bash
./flappy.exe
\`\`\`

---

## 💡 Ideas for Improvement

- Add **sound effects** using `<mmsystem.h>`
- Introduce **multiple power-ups**
- Implement **leaderboard** using file I/O
- Convert to **cross-platform** version using SDL or ncurses
- Add **background music** and custom animations

Feel free to fork the project and try these out!

---

## 🤝 Contributing

This project is **open to contributions**!  
If you find a bug or have a cool new feature idea:

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

> All suggestions are welcome! Let’s make Flappy Bird Deluxe even better together.

---

## 📝 License

This project is **open-source** and free to use for learning and development purposes.

---

## 📣 Connect With Me

If you liked the project or want to contribute together on more cool C++ games or AI-based projects, feel free to connect!


- 🐙 GitHub: GauravRathod61(https://github.com/GauravRathod61)

---

✨ *Keep Flapping... and Don't Hit the Pipes!* ✨
