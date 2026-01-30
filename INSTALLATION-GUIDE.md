# Eva's 84 Club - Installation Guide 📱

Your math game is now a **Progressive Web App (PWA)**! This means it can be installed on phones and tablets like a real app.

## 📦 What's Included

1. **eva-math-game.html** - The main game file
2. **manifest.json** - App configuration
3. **service-worker.js** - Enables offline functionality
4. **icon.svg** - App icon (needs to be converted to PNG)

## 🚀 How to Install on iPad/iPhone

### Method 1: Using Safari (Recommended)

1. **Upload files to a web server:**
   - You need all files on a web server (see hosting options below)
   - Open the game URL in Safari

2. **Install the app:**
   - Tap the **Share button** (square with arrow pointing up)
   - Scroll down and tap **"Add to Home Screen"**
   - Tap **"Add"**
   - The game icon will appear on your home screen!

3. **Open the app:**
   - Tap the icon on your home screen
   - It will open full-screen like a real app
   - Works offline after first load!

### Method 2: Direct File Installation (Limited)

If you don't have web hosting:
1. Open **eva-math-game.html** in Safari
2. Tap Share → "Add to Home Screen"
3. Note: Offline functionality won't work without a server

## 🌐 Hosting Options (FREE)

To get the full PWA experience, you need to host the files online. Here are free options:

### Option 1: GitHub Pages (Easiest for Free)
1. Create a GitHub account (free)
2. Create a new repository
3. Upload all files
4. Go to Settings → Pages
5. Enable GitHub Pages
6. Your game will be at: `https://username.github.io/repository-name/eva-math-game.html`

### Option 2: Netlify (Drag & Drop)
1. Go to netlify.com
2. Drag and drop all files
3. Get instant URL
4. Free forever for basic sites

### Option 3: Vercel
1. Go to vercel.com
2. Sign up free
3. Deploy your files
4. Get instant URL

### Option 4: Firebase Hosting (Google)
1. Go to firebase.google.com
2. Create free project
3. Use Firebase CLI to deploy
4. Fast and reliable

## 🎨 Creating App Icons (Required)

The icon.svg file needs to be converted to PNG format:

### Using Online Tools:
1. Go to cloudconvert.com or any SVG to PNG converter
2. Upload **icon.svg**
3. Convert to PNG at these sizes:
   - **icon-192.png** (192x192 pixels)
   - **icon-512.png** (512x512 pixels)
4. Save both files in the same folder as the game

### Using Design Software:
- Open icon.svg in Figma/Photoshop/Illustrator
- Export as PNG at 192x192 and 512x512

## ✅ Testing Your PWA

1. Open the game URL in Safari on iPad
2. Check for the Share button functionality
3. Add to Home Screen
4. Open from home screen
5. Try turning off internet - it should still work!

## 📱 Features After Installation

✨ **Works like a native app:**
- Full screen (no browser bars)
- App icon on home screen
- Works offline after first load
- Fast loading
- Smooth animations

✨ **All game features:**
- 12-minute timer
- Random 84 problems from 144
- Mistake tracking
- Progress monitoring
- Study mode with answer key

## 🔧 Troubleshooting

**Problem:** Can't add to home screen
- Make sure you're using Safari (not Chrome)
- Files must be served over HTTPS (use hosting)

**Problem:** Offline mode doesn't work
- Files must be on a web server (not local files)
- Visit the page once while online first

**Problem:** Icon doesn't show
- Make sure icon-192.png and icon-512.png exist
- Check that filenames match exactly in manifest.json

**Problem:** App doesn't update
- Clear Safari cache
- Delete old app from home screen
- Reinstall fresh

## 📝 File Structure

Make sure all files are in the same folder:
```
your-folder/
├── eva-math-game.html
├── manifest.json
├── service-worker.js
├── icon-192.png (you need to create this)
└── icon-512.png (you need to create this)
```

## 🎯 Quick Start (If You Have Hosting)

1. Convert icon.svg to PNG (192x192 and 512x512)
2. Upload ALL files to your web host
3. Open the URL in Safari on iPad
4. Tap Share → Add to Home Screen
5. Done! 🎉

## 💡 Tips

- The game saves no personal data
- All progress is lost when closing the app
- Each game randomly selects 84 from 144 problems
- Perfect for daily math practice!

## Need Help?

Common issues:
- Files must be on HTTPS (secure) server
- Use Safari browser on iOS (not Chrome)
- Make sure all files are uploaded
- Icon files must be PNG format

Enjoy the game! 🌟
