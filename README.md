# Pong Game with AI Opponent

Classic Pong implementation in C using Allegro 5, featuring an automated AI opponent for Player 2.

## Requirements
- Allegro 5 libraries
- Clang compiler (or GCC)
- GNU Make

## Installation
### Linux (Debian/Ubuntu)
```bash
sudo apt-get install build-essential clang liballegro5-dev liballegro-acodec5-dev liballegro-audio5-dev liballegro-font5-dev liballegro-ttf5-dev
```

### Linux (Fedora)
```bash
sudo dnf install clang allegro5-devel allegro5-acodec-devel allegro5-audio-devel allegro5-font-devel
```

## Building & Running
1. Clone repository:
```bash
git clone https://github.com/Trysdan/Pong.git
cd Pong
```

2. Compile project:
```bash
make
```

3. Start game:
```bash
./main
```

4. Clean build files:
```bash
make clean
```

## Controls
- **Player 1 (Left):** `W/S` keys to move paddle up/down
- **Player 2 (Right):** AI-controlled (automated movement)

Project created for video game programming practice course.