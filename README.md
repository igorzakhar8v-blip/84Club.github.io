# Eva's 84 Club - Progressive Web App 🌟

A fun, interactive math game for practicing multiplication tables (1-12). Now available as a Progressive Web App that can be installed on iPad, iPhone, and Android devices!

## 🎮 Game Features

- **Random Problem Selection:** 84 problems randomly selected from 144 (complete 1-12 times tables)
- **Study Mode:** View all 144 answers before starting
- **12-Minute Timer:** Complete as many as you can in time
- **Smart Mistake Tracking:** Remembers all wrong answers and reviews them at the end
- **Two-Strike System:** After 2 incorrect attempts, shows the answer and moves on
- **Progress Tracking:** See how many problems completed and remaining
- **Beautiful Animations:** Confetti, stars, and smooth transitions
- **Offline Support:** Works without internet after installation

## 📦 What You Have

1. **eva-math-game.html** - The main game (PWA-enabled)
2. **manifest.json** - App configuration
3. **service-worker.js** - Enables offline functionality
4. **icon-generator.html** - Tool to create app icons
5. **icon.svg** - Source icon design
6. **INSTALLATION-GUIDE.md** - Detailed setup instructions

## 🚀 Quick Start

### Step 1: Generate Icons
1. Open **icon-generator.html** in your browser
2. Download both icons (icon-192.png and icon-512.png)
3. Save them in the same folder as the game

### Step 2: Host the Files
Upload all files to a web server. Free options:
- **GitHub Pages** (easiest)
- **Netlify** (drag & drop)
- **Vercel**
- **Firebase Hosting**

### Step 3: Install on iPad
1. Open the game URL in Safari
2. Tap Share button
3. Select "Add to Home Screen"
4. Tap "Add"
5. Done! 🎉

## 📱 PWA Features

When installed as a PWA, the game:
- ✅ Appears as an app icon on home screen
- ✅ Opens in full screen (no browser bars)
- ✅ Works offline after first load
- ✅ Feels like a native app
- ✅ Fast loading and smooth performance

## 🎯 How to Play

1. **Study Phase:** Review all 144 multiplication problems
2. **Press Start:** Game randomly selects 84 problems
3. **Answer Questions:** Type your answer and press Enter or click "Check!"
4. **Two Chances:** Get 2 attempts per problem
5. **Complete All 84:** Try to finish before time runs out!
6. **Review Mistakes:** See all problems you got wrong with correct answers

## 🔧 Technical Details

- **Framework:** Pure HTML, CSS, and JavaScript (no dependencies)
- **Storage:** No data stored (everything in-memory)
- **Offline:** Service Worker caches files for offline use
- **Compatible:** Works on iOS Safari, Chrome, Edge, Firefox
- **Size:** ~100KB total (very lightweight)

## 📋 File Structure

```
your-folder/
├── eva-math-game.html      (Main game)
├── manifest.json            (PWA configuration)
├── service-worker.js        (Offline support)
├── icon-192.png            (Small icon - generate this)
├── icon-512.png            (Large icon - generate this)
├── icon-generator.html      (Icon creation tool)
├── icon.svg                (Icon source)
├── INSTALLATION-GUIDE.md   (Setup instructions)
└── README.md               (This file)
```

## 💡 Tips

- Use Safari on iOS for best results
- Visit the page once online before going offline
- Clear Safari cache if app doesn't update
- Each game is unique (random 84 from 144)
- Perfect for daily math practice!

## 🎨 Customization

Want to customize? You can edit:
- **Colors:** Change the gradient in eva-math-game.html (search for #667eea and #764ba2)
- **Timer:** Change 720 (seconds) to adjust from 12 minutes
- **Problem Count:** Change 84 to any number up to 144
- **Icon:** Edit icon.svg and regenerate PNGs

## 🐛 Troubleshooting

**Can't install on iPad?**
- Make sure you're using Safari (not Chrome)
- Files must be on HTTPS server
- Try clearing Safari cache

**Offline mode not working?**
- Must be hosted on web server
- Visit page once while online
- Check service worker registration in console

**Icon not showing?**
- Generate icon-192.png and icon-512.png using icon-generator.html
- Ensure filenames match exactly
- Clear cache and reinstall

## 📖 Full Documentation

See **INSTALLATION-GUIDE.md** for detailed setup instructions including:
- Step-by-step hosting setup
- iOS installation walkthrough
- Icon generation guide
- Troubleshooting tips

## 🌟 Enjoy!

Eva can now practice multiplication tables anytime, anywhere - even without internet!

Made with ❤️ for math practice
