# 🎮 ⛧ Survivor Game ⛧

A thrilling top-down shooter game built with Pygame where you must survive against endless waves of enemies! Face the challenge in this dark, atmospheric arena where your shooting skills and movement strategy are key to survival.

## 🌟 Features

- 🏃 Smooth character movement with WASD/Arrow keys
- 🔫 360-degree shooting mechanics with mouse aim
- 👾 Dynamic enemy spawning system
- 🎯 Precise collision detection
- 🗺️ Custom-designed game map using Tiled
- 🎵 Immersive sound effects and background music
- 🎨 Animated character sprites and enemies
- 🎬 Stylish death animations

## 🎮 Controls

- **Movement**: WASD or Arrow Keys
- **Aim**: Mouse
- **Shoot**: Left Mouse Button
- **Gun Cooldown**: 100ms between shots

## 🛠️ Technical Details

### Game Components
- **Player System**: 
  - Hitbox-based collision system
  - Multi-directional animation states
  - Speed: 500 units/second

- **Enemy System**:
  - AI-driven movement towards player
  - Custom sprite animations
  - Varied spawn positions
  - Death animation with mask effects

- **Weapon System**:
  - Dynamic gun rotation following mouse position
  - Bullet lifetime management
  - Projectile collision detection

### 🏗️ Architecture

The game is built with several key components:
- `main.py`: Core game loop and initialization
- `player.py`: Player character mechanics
- `sprites.py`: Game object implementations
- `groups.py`: Sprite group management
- `settings.py`: Game constants and configurations

## 🎨 Visual Style

The game features a dark, atmospheric aesthetic with:
- Gothic-styled game caption: "⛧ 𝕾𝖚𝖗𝖛𝖎𝖛𝖔𝖗 ⛧"
- Custom pixel art sprites
- Dynamic lighting effects
- Smooth animation transitions

## 🔧 Requirements

- Python 3.10
- Pygame-ce
- PyTMX (for map loading)

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/carefreeone12/Survivor-Game.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt 
```

3. Run the game:
```bash
python main.py
```

## 🎯 Gameplay Tips

- Keep moving to avoid enemy contact
- Use obstacles for cover
- Manage your shooting cooldown wisely
- Watch for enemy spawn points
- Use the map layout to your advantage

## 🔮 Future Enhancements

- [ ] Power-up system
- [ ] Multiple weapon types
- [ ] Score tracking
- [ ] Different enemy types
- [ ] Boss battles
- [ ] Level progression system

## 🎵 Credits

- Game sound effects and music included
- Custom sprite animations
- Map design using Tiled editor

## 🤝 Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating your feature branch
3. Committing your changes
4. Pushing to the branch
5. Opening a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
Made with 💖 and lots of ☕
