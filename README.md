# Flappy Bird 🐦

A recreation of the classic **Flappy Bird** game built using Python and Pygame. Control the bird, navigate through randomly positioned pipes, avoid collisions, and try to achieve the highest score!

## 🎮 Features

- **Bird Animation:** Animated bird sprites with rotation based on vertical movement.
- **Gravity and Jump Mechanics:** Make the bird flap using mouse clicks.
- **Random Pipe Generation:** Pipes spawn at varying heights to keep the gameplay challenging.
- **Collision Detection:** Detect collisions with pipes, the upper boundary, and the ground.
- **Score Tracking:** Earn points by successfully passing pipe pairs.
- **Scrolling Environment:** Moving ground and pipes recreate the classic gameplay experience.
- **Restart Functionality:** Restart the game after a game-over event.
- **Customizable Gameplay:** Adjust the pipe gap, spawn interval, scrolling speed, and frame rate.

## 🛠️ Tech Stack

- **Language:** Python 3.12
- **Game Library:** Pygame 2.6.1
- **Development Environment:** Visual Studio Code
- **Version Control:** Git and GitHub

## 📁 Project Structure

```text
flappy-bird/
├── flappy_bird_assets/
│   └── img/
│       ├── bg.png
│       ├── bglong.png
│       ├── bird1.png
│       ├── bird2.png
│       ├── bird3.png
│       ├── ground.png
│       ├── pipe.png
│       ├── restart.png
│       └── spritesheet.png
├── .dockerignore
├── .gitignore
├── Dockerfile
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.12
- pip
- Git (optional, for cloning the repository)

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd flappy-bird
```

Replace `<https://github.com/vishnu-s-tripathi06/flappy-bird.git>` with the URL of your GitHub repository.

### 2. Create a virtual environment

**Windows (PowerShell):**

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the game

```bash
python main.py
```

The game window should open, and you can start playing!

## 🕹️ Controls

| Action                  | Control                  |
| ----------------------- | ------------------------ |
| Start the game          | Left mouse click         |
| Make the bird flap      | Left mouse click         |
| Restart after game over | Click the restart button |
| Exit the game           | Close the game window    |

## 🔧 Game Configuration

The following variables near the top of `main.py` control the game's behavior.

| Variable         | Current Value | Purpose                                 |
| ---------------- | ------------: | --------------------------------------- |
| `screen_width`   |         `764` | Game window width                       |
| `screen_height`  |         `820` | Game window height                      |
| `fps`            |          `40` | Target frame rate                       |
| `scroll_speed`   |           `4` | Movement speed of pipes and ground      |
| `pipe_gap`       |         `170` | Vertical gap between pipes              |
| `pipe_frequency` |     `2500` ms | Interval between pipe-generation events |

You can adjust these values to experiment with the game's difficulty and performance.

## 📚 What I Learned

Through this project, I practised:

- Object-oriented programming with Python classes.
- Creating a game loop and handling user input.
- Working with sprites, animation, and image transformations.
- Implementing gravity and jump mechanics.
- Detecting collisions using Pygame sprite groups.
- Generating game obstacles dynamically.
- Tracking scores and managing game states.
- Organizing project assets and dependencies.

## 🚀 Future Improvements

- Add sound effects and background music.
- Save high scores between sessions.
- Add a start menu and difficulty levels.
- Introduce keyboard controls and a pause feature.
- Improve the user interface and gameplay feedback.

## 📄 License

This project is intended for learning and educational purposes. Before redistributing it, verify the licensing terms of any third-party images or other assets included in the project.

---

**Built with Python and Pygame.**
