# 🎯 Family Feud Game

A fully customizable Family Feud game built with HTML, CSS, and JavaScript. Single file, no dependencies, works anywhere.

## 🎮 Features

- **Customizable Questions** — Add your own questions, answers, and point values
- **Two-Team Play** — Name your teams and track scores
- **Classic TV Theme** — Dark blue + orange oval board with dot lights
- **3-Strike System** — Strikes trigger steal opportunities
- **Steal Mechanic** — Other team gets a chance to steal points
- **Preset Question Packs** — General Knowledge, Food & Drinks, Workplace Fun
- **Import/Export** — Save/load question sets as JSON files
- **Sound Effects** — Ding on reveal, buzzer on strikes
- **Host Controls** — Collapsible panel (hidden from audience)
- **Keyboard Shortcuts** — Run the whole game from your keyboard
- **Auto-Sort Answers** — Highest points displayed first (column-order)
- **Mobile Responsive** — Works on smaller screens too

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `X` | Strike (wrong answer) |
| `W` | Award points to active team |
| `S` | Switch active team |
| `1`-`8` | Reveal specific answer |
| `→→` or `]]` | Next Round (double-tap) |
| `←←` or `[[` | Redo Game (double-tap) |
| `Y` | Steal successful (during steal) |
| `N` | Steal failed (during steal) |

## 🚀 How to Host on GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `family-feud` (or anything you like)
3. Set it to **Public**
4. Check **"Add a README file"** (optional, since we have one)
5. Click **Create repository**

### Step 2: Upload Files
1. Click **"Add file"** → **"Upload files"**
2. Drag and drop both `index.html` and `README.md`
3. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main` and folder to `/ (root)`
4. Click **Save**

### Step 4: Access Your Game
- Wait 1-2 minutes for deployment
- Your game will be live at: `https://YOUR-USERNAME.github.io/family-feud/`
- Share this link with anyone to play!

## 🎲 How to Play

### Setup
1. Open the game in your browser
2. **Teams tab**: Name your two families/teams
3. **Questions tab**: Add custom questions with answers and point values
4. **Presets tab**: Or load a ready-made question pack
5. Click **🎬 START GAME!**

### During the Game
- Click answer slots or press `1`-`8` to reveal answers
- Press `X` for wrong answers (strikes)
- 3 strikes = steal opportunity for the other team
- Press `W` to award the round's points to the active team
- Press `S` to switch the active team
- Double-tap `→` or `]` to move to the next round

### Host Controls
- Click **"🎮 Host Controls"** at the bottom-right to open the control panel
- Hide it when presenting to keep the display clean for the audience

## 📦 Custom Questions (JSON Format)

Export your questions to reuse them later. The JSON format is:

```json
[
  {
    "q": "Name something people do in the morning",
    "answers": [
      { "t": "Check Phone", "p": 35 },
      { "t": "Brush Teeth", "p": 25 },
      { "t": "Drink Coffee", "p": 20 },
      { "t": "Shower", "p": 12 },
      { "t": "Eat Breakfast", "p": 8 }
    ]
  }
]
```

## 📄 License

Free to use for personal and team events. Have fun! 🎉

