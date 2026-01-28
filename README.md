# 🌱 Plants vs Zombies - Custom Edition

A browser-based Plants vs Zombies game featuring custom characters and enhanced gameplay!

![Game Preview](https://img.shields.io/badge/Status-Playable-green)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

## 🎮 Play Now

Simply open `index.html` in any modern web browser to start playing!

## ✨ Features

### **Defenders (Plants)**
- 🌱 **Peashooter** ($100) - Classic green pea shooter
- ❄️ **Freeze Shooter** ($175) - Slows zombies for 3 seconds
- 🎯 **Sniper** ($200) - High damage, slow fire rate
- 💣 **Bomber** ($150) - Splash damage to nearby zombies
- 🌻 **Sunflower** ($50) - Generates sun resources
- 🥜 **Wall-nut** ($50) - High HP tank

### **Game Mechanics**
- Grid-based 9x5 lawn battlefield
- Real-time combat system
- Resource management (sun collection)
- Progressive difficulty (zombies spawn faster)
- Health bars for all units
- Special effects (freeze, splash damage, etc.)

### **Visual Features**
- Beautiful gradient backgrounds
- Animated projectiles with glow effects
- Shadow effects for depth
- Pulsing sun collection
- Frozen zombie visual effects
- Custom character portraits

## 🎯 How to Play

1. **Start with 200 sun** and generate more over time
2. **Place Sunflowers** early to boost your economy
3. **Select a plant** from the top menu
4. **Click on the lawn** to place your defender
5. **Collect sun tokens** by clicking on them
6. **Defend your lawn** from zombie waves!

### Strategy Tips
- Place Sunflowers in the back rows for safety
- Use Wall-nuts to protect your offensive plants
- Freeze Shooters are great for slowing zombie rushes
- Bombers work well when zombies group up
- Snipers are expensive but deal massive damage

## 🛠️ Technical Details

- **Pure HTML5 Canvas** - No external dependencies
- **Vanilla JavaScript** - ES6+ features
- **Single file** - Easy to share and deploy
- **Responsive design** - Works on different screen sizes

## 🚀 Deployment

### GitHub Pages (Free Hosting)
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your game will be live at `https://yourusername.github.io/plants-vs-zombies-game`

### Local Development
```bash
# Simply open the file
open index.html

# Or use a local server (recommended)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

## 📝 Game Balance

### Plants
| Plant | Cost | HP | Special |
|-------|------|----|----|
| Peashooter | 100 | 150 | Basic damage |
| Freeze Shooter | 175 | 150 | Slows enemies |
| Sniper | 200 | 100 | High damage |
| Bomber | 150 | 150 | Splash damage |
| Sunflower | 50 | 150 | Generates 50 sun/5s |
| Wall-nut | 50 | 600 | Tank |

### Zombies
- **Basic Zombie**: 100 HP, 20 damage
- **Cone Zombie**: 200 HP, 20 damage (slower)

## 🎨 Customization

The game features custom character portraits! You can easily modify:
- Plant stats in `PLANT_TYPES` object
- Zombie behavior in `ZOMBIE_TYPES` object
- Visual effects in drawing functions
- Replace character images by updating image paths

## 📄 License

This is a fan project inspired by Plants vs Zombies. All rights to the original game belong to PopCap Games / Electronic Arts.

## 🤝 Contributing

Feel free to fork this project and add your own features:
- New plant types
- New zombie varieties
- Power-ups
- Multiplayer mode
- Sound effects
- Animations

## 🐛 Known Issues

- Image loading requires absolute paths (may need adjustment for GitHub Pages)
- No mobile touch controls yet
- No sound effects

## 💡 Future Ideas

- [ ] Add more plant types
- [ ] Add more zombie varieties
- [ ] Level progression system
- [ ] Achievement system
- [ ] Local leaderboard
- [ ] Sound effects and music
- [ ] Mobile-friendly controls
- [ ] Save/load game state

---

**Enjoy defending your lawn!** 🌱🧟
