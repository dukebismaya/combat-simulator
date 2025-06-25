# 🚀 Cosmic Combat Simulator

A fast-paced 2D space shooter game built with Python and Pygame. Battle through waves of enemies, collect power-ups, and survive as long as possible in this retro-style arcade experience!

## ✨ Features

- **Intense Combat**: Face multiple enemy types with different behaviors and attack patterns
- **Power-ups System**: Collect rapid fire, shields, and other enhancements to boost your combat effectiveness
- **Progressive Difficulty**: Enemy waves become increasingly challenging as you advance
- **Retro Aesthetics**: Classic arcade-style graphics and sound effects
- **Smooth Controls**: Responsive keyboard controls for precise movement and shooting
- **Score System**: Track your performance and compete for high scores
- **Sound Effects**: Immersive audio feedback for all game actions

## 🎮 Controls

- **Arrow Keys** / **WASD**: Move your ship
- **Spacebar**: Fire weapons
- **ESC**: Pause game / Return to menu
- **R**: Restart (when game over)

## 🛠️ Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/dukebismaya/space-shooter-game.git
   cd space-shooter-game
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   
   # On Windows:
   venv\Scripts\activate
   
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the game:
   ```bash
   python src/main.py
   ```

## 🎯 Gameplay

### Objective
Survive as long as possible while destroying enemy ships and collecting power-ups. Each enemy destroyed increases your score, and surviving longer waves unlocks higher difficulty levels.

### Current Enemy Types
- **Basic Fighters**: Simple enemies that move toward the player
- **Advanced Ships**: (Not implemented yet) Faster enemies with improved AI
- **Boss Enemies**: Large, powerful enemies that appear in later waves

### Power-ups
- **🔫 Rapid Fire**: Increases your firing rate for a limited time
- **🛡️ Shield**: Provides temporary protection from enemy attacks
- **⚡ Speed Boost**: Increases movement speed
- **💥 Multi-Shot**: Fire multiple projectiles simultaneously

## 🐛 Debug Mode

The game includes a comprehensive debug system for development:

### Enable Debug Mode
```bash
# Windows
set DEBUG=True
set SHOW_CONSOLE_LOGS=True
python src/main.py

# macOS/Linux
export DEBUG=True
export SHOW_CONSOLE_LOGS=True
python src/main.py
```

### Debug Categories
- `GAME_EVENTS`: General game events
- `COLLISION`: Collision detection
- `ENEMY_AI`: Enemy behavior
- `PLAYER_INPUT`: Input handling
- `PERFORMANCE`: Performance timing
- `SOUND`: Audio events

## 📋 Requirements

- Python 3.7+
- pygame 2.0+
- Additional dependencies listed in `requirements.txt`

## 🚀 Building Executable

To create a standalone executable:

```bash
# Install PyInstaller
pip install pyinstaller

# Build executable
pyinstaller --onefile --windowed src/main.py

# The executable will be in the dist/ folder
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Development Notes

- All debug output is controlled via the debug configuration system
- Logs are automatically saved to the `logs/` directory
- Use the provided debug utilities for consistent logging
- Follow the existing code structure when adding new features

## 🎵 Audio Credits

Sound effects and music assets are sourced from:
- Pixabay & Mixkit

## 🖼️ Graphics Credits

Sprite and image assets are sourced from:
- [Spacecrafts and planets](https://pixelwolfog.itch.io/space-shooter-assets)
- Enemies

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎮 Screenshots
![Main menu](../preview/main_menu.png)
![Spacecraft selection menu](../preview/star_fighter_selection_menu.png)
![Gameplay](../preview/gameplay.png)

---

**Enjoy the cosmic combat! 🚀💫**

For questions, suggestions, or bug reports, please open an issue on GitHub.