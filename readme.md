# Alien Invasion

In *Alien Invasion*, the player controls a rocket ship that appears at the bottom center of the screen. The player can move the ship right and left using the arrow keys and shoot bullets using the spacebar. When the game begins, a fleet of aliens fills the sky and moves across and down the screen. The player shoots and destroys the aliens. If the player destroys all the aliens, a new fleet appears that moves faster than the previous fleet. If any alien hits the player's ship or reaches the bottom of the screen, the player loses a ship. If a player loses three ships, the game ends.

## Project Setup

### 1. Create a virtual environment (Python 3.13)

```bash
py -3.13 -m venv .venv
```

### 2. Activate the virtual environment

**PowerShell (Windows):**

```powershell
.venv\Scripts\Activate.ps1
```

**Command Prompt (Windows):**

```cmd
.venv\Scripts\activate.bat
```

### 3. Upgrade pip

```bash
python -m pip install --upgrade pip
```

### 4. Install dependencies

```bash
pip install pygame
```

### 5. Verify the installation

```bash
python -c "import pygame; print(pygame.__version__)"
```

## Deactivate the virtual environment

```bash
deactivate
```