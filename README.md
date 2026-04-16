# 🎯 Family Feud - Customizable Game

A fully customizable Family Feud game built with HTML, CSS, and JavaScript. Single file, no dependencies — host it anywhere!

## 🎮 Features
- 🎨 Custom Questions with point values
- 👥 Two-Team Play with score tracking
- 📦 Preset Packs (General, Food, Workplace)
- 💾 Import/Export question packs as JSON
- 🎮 Hidden Host Controls panel
- ⌨️ Full Keyboard Shortcuts
- 🔊 Sound Effects (dings, buzzers, fanfare)
- 📱 Responsive (desktop, tablet, mobile)
- 🎊 Confetti celebration for winners

## ⌨️ Shortcuts
| Key | Action |
|-----|--------|
| `X` | Strike | `W` | Award points |
| `S` | Switch team | `1-8` | Reveal answer |
| `→→`/`]]` | Next round | `←←`/`[[` | Redo game |
| `Y` | Steal success | `N` | Steal failed |
| `Esc` | Toggle help |

## 🚀 Host on GitHub Pages
1. Create a new public repo on GitHub
2. Upload `index.html` and `README.md`
3. Go to Settings → Pages → Source: `main`, `/ (root)` → Save
4. Visit `https://YOUR-USERNAME.github.io/REPO-NAME/`

## 🎲 How to Play
1. Set up teams and add questions (or load presets)
2. Click answers or press 1-8 to reveal
3. Press X for wrong answers (3 strikes = steal)
4. Press W to award points, double-tap → for next round
5. Highest score wins! 🏆

## 📦 Question JSON Format
```json
[{"q":"Your question","answers":[{"t":"Answer","p":35}]}]
```

## 📄 License
MIT — Free to use, modify, and share. Have fun! 🎉

