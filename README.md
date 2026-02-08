# 7 Pleasures

A Progressive Web App for tracking life's pleasures - intimacy, food, rest, and more.

## ✨ Features

### Current Features (Intimacy Tracker)
- 🎯 **Visual Entry System**: Tap emojis to select positions, tap numbers to rate
- 📊 **Smart Dashboard**: See your combined stats, individual preferences, and comparisons
- 👥 **Multi-User Support**: Each partner tracks independently, then syncs data
- 💾 **Export/Import**: Share JSON files to merge your data together
- 📱 **Mobile-Optimized**: Works perfectly on iOS and Android
- 🔒 **Privacy First**: All data stored locally on your device
- 📴 **Works Offline**: Use the app without internet after first load

### Coming Soon
- 🍽️ Food: Meal tracker, recipe favorites, meal prep
- 💰 Wealth: Purchase tracker, wish lists
- 😴 Rest: Sleep quality, nap tracking
- ⚡ Energy: Workout logging, PR tracking
- 💚 Growth: Goal tracking, inspiration board
- 👑 Achievement: Milestones, celebrations

## 🚀 Quick Setup (5 Minutes)

### Option 1: GitHub Pages (Recommended - FREE)

1. **Create a GitHub account** (if you don't have one): https://github.com

2. **Create a new repository**:
   - Click the "+" in top right → "New repository"
   - Name it: `7-pleasures`
   - Make it **Private** (important for privacy!)
   - Click "Create repository"

3. **Upload files**:
   - Click "uploading an existing file"
   - Drag and drop these files:
     - `index.html`
     - `manifest.json`
     - `sw.js`
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to Settings → Pages (left sidebar)
   - Under "Source", select "main" branch
   - Click Save
   - Wait 1-2 minutes for deployment

5. **Get your URL**:
   - Your app will be at: `https://YOUR-USERNAME.github.io/7-pleasures/`
   - Visit this URL on your phones to use the app!

### Option 2: Netlify (Also FREE)

1. Go to https://www.netlify.com/
2. Sign up (free)
3. Drag and drop the folder with all files into Netlify
4. Get your URL (like: `https://random-name.netlify.app`)

### Option 3: Vercel (Also FREE)

1. Go to https://vercel.com/
2. Sign up with GitHub
3. Import your repository
4. Deploy (takes 1 minute)
5. Get your URL

## 📱 Installing on Your Phones

### iOS (iPhone/iPad)
1. Open Safari (must use Safari, not Chrome)
2. Visit your app URL
3. Tap the Share button (box with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Name it "7 Pleasures" and tap "Add"
6. App icon will appear on your home screen!

### Android
1. Open Chrome
2. Visit your app URL
3. A popup will appear asking to "Install"
4. Or tap the three dots menu → "Add to Home screen"
5. App icon will appear on your home screen!

## 🔄 How to Sync Data Between Devices

Since you don't need real-time syncing, here's the simple process:

### Step 1: Each person tracks independently
- Open the app on your device
- Enter your name when first launching
- Add entries as you go

### Step 2: When you want to compare/sync
**Person 1 (e.g., You):**
1. Tap the Share icon (top right)
2. Tap "Export My Data"
3. Save the JSON file
4. Share it with your partner via:
   - Text message
   - Email
   - AirDrop (iOS)
   - Any messaging app

**Person 2 (e.g., Your Wife):**
1. Receive the JSON file
2. Open the 7 Pleasures app
3. Tap the Share icon
4. Tap "Import Partner's Data"
5. Select the JSON file
6. Done! You'll see both your entries combined

**Person 1 can then import Person 2's data the same way!**

### When to sync?
- Weekly review sessions
- Monthly check-ins
- Whenever you want to compare preferences
- Before a special occasion to plan

## 🎨 Using the App

### Adding an Entry
1. Tap the pink + button (bottom right)
2. Select the date
3. **Tap an emoji** to select position/activity
4. **Tap numbers 1-10** to rate your experience
5. **Tap duration buttons** to select how long
6. **Tap tags** to add context (romantic, spontaneous, etc.)
7. Add optional notes
8. Tap "Save Entry"

### Viewing Insights
The dashboard automatically shows:
- Total encounters this year
- Your personal stats and average rating
- Partner's stats and average rating
- Monthly frequency
- Top rated activities for each person
- Side-by-side comparison

### Privacy
- All data stored locally on each device
- Nothing sent to any server
- Export/import files are only shared directly between you two
- GitHub/Netlify/Vercel only host the app code, not your data

## 🛠️ Technical Details

**Built with:**
- React 18
- Tailwind CSS
- Lucide Icons
- LocalStorage for data persistence
- Service Workers for offline functionality

**File structure:**
```
7-pleasures/
├── index.html          # Main app file
├── manifest.json       # PWA configuration
├── sw.js              # Service worker for offline support
└── README.md          # This file
```

## 🔒 Security & Privacy

- **No database**: Everything is stored on your devices only
- **No accounts**: No passwords, no login, no tracking
- **No analytics**: We don't see anything you track
- **Encrypted**: Use HTTPS (GitHub Pages/Netlify/Vercel all provide this)
- **Private repo**: Keep your GitHub repo private
- **Shareable only by you**: Only export/import what you want to share

## 🐛 Troubleshooting

**App not installing:**
- iOS: Must use Safari browser
- Android: Must use Chrome browser
- Make sure you're using HTTPS (not HTTP)

**Data not syncing:**
- Each person must export their data
- Both people must import each other's files
- Make sure you're importing a .json file

**Lost data:**
- Data is stored per device
- Clearing browser data will erase entries
- Export your data regularly as backup!

**Can't see partner's entries:**
- You need to import their exported JSON file
- They need to export and share it with you first

## 🎯 Roadmap

### Phase 1 (Current)
- ✅ Intimacy tracker with visual entry
- ✅ Export/import functionality
- ✅ Mobile-optimized interface
- ✅ Offline support

### Phase 2 (Coming Soon)
- 🍽️ Food: Meal tracker, recipe favorites, meal prep
- 💰 Wealth: Purchase tracker, wish lists
- 😴 Rest: Sleep quality, nap tracking
- ⚡ Energy: Workout logging, PR tracking
- 💚 Growth: Goal tracking, inspiration board
- 👑 Achievement: Milestones, celebrations

### Phase 3 (Future)
- Cloud sync option (optional Firebase)
- QR code sharing
- PDF export for reports
- Custom position/activity creator with photos

## 💡 Tips for Best Experience

1. **Set a reminder**: Track entries soon after for accuracy
2. **Be honest with ratings**: This helps find patterns
3. **Use tags**: They make insights more meaningful
4. **Export regularly**: Backup your data monthly
5. **Review together**: Use the comparison view for discussions
6. **Custom positions**: Use "Other/Custom" for your unique activities

## 📞 Support

Having issues? Here's what to check:
1. Are you using HTTPS? (Lock icon in browser)
2. Did you install it properly? (Should be on home screen)
3. Is your browser up to date?
4. Did you grant necessary permissions?

## 📜 License

This is your private app for personal use. Feel free to modify and enhance it!

---

## Quick Start Checklist

- [ ] Upload files to GitHub/Netlify/Vercel
- [ ] Get your app URL
- [ ] Install on both phones
- [ ] Each person enters their name
- [ ] Start tracking!
- [ ] Export/import when ready to compare

**Enjoy tracking life's pleasures together! 💕✨**
