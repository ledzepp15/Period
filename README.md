# Period Tracker - Maggie's Application

A beautiful, polished period tracking application optimized for iPhone and mobile devices. Track your menstrual cycle, symptoms, moods, and get personalized insights.

## Features

### Core Functionality
- **Period Logging**: Easily log your period start date and duration
- **Calendar View**: Visual calendar showing period days, fertile windows, and ovulation
- **Cycle Predictions**: Intelligent predictions for your next period based on your history
- **Symptom Tracking**: Track common symptoms like cramps, headaches, bloating, fatigue, and more
- **Mood Tracking**: Log your daily mood to identify patterns
- **Notes**: Add personal notes for any day
- **Insights**: Get personalized insights about your cycle

### Technical Features
- **Progressive Web App (PWA)**: Install on iPhone home screen like a native app
- **Offline Support**: Works without internet connection
- **Data Privacy**: All data stored locally on your device
- **Mobile-First Design**: Optimized for iPhone and touch devices
- **No Registration Required**: Start using immediately
- **Export Data**: Download your data as JSON backup

## How to Use on iPhone

### Option 1: Host Locally (Simple Server)

1. **Install Python** (usually pre-installed on Mac):
   ```bash
   python3 --version
   ```

2. **Navigate to the app directory**:
   ```bash
   cd /path/to/Period
   ```

3. **Start a local server**:
   ```bash
   python3 -m http.server 8000
   ```

4. **Open on your iPhone**:
   - Make sure your iPhone is on the same WiFi network as your computer
   - Find your computer's IP address (on Mac: System Preferences > Network)
   - On your iPhone, open Safari and go to: `http://YOUR_IP_ADDRESS:8000`

5. **Add to Home Screen**:
   - Tap the Share button (square with arrow) in Safari
   - Scroll down and tap "Add to Home Screen"
   - Give it a name and tap "Add"
   - The app icon will appear on your home screen!

### Option 2: Deploy to GitHub Pages (Free Hosting)

1. **Create a GitHub repository** (if not already done)

2. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Under "Source", select "main" branch
   - Click Save

3. **Access your app**:
   - Your app will be available at: `https://YOUR_USERNAME.github.io/Period/`
   - Open this URL on your iPhone and add to home screen as described above

### Option 3: Deploy to Netlify (Free, Easiest)

1. **Sign up at [Netlify](https://netlify.com)**

2. **Deploy**:
   - Drag and drop the entire Period folder to Netlify
   - You'll get a free URL like: `https://your-app-name.netlify.app`

3. **Access on iPhone**:
   - Open the URL on your iPhone
   - Add to home screen

## Usage Guide

### Logging Your Period

1. Tap the "Log Period Start" button on the home screen
2. Select the start date
3. Enter the duration (how many days)
4. Tap "Save Period"

### Tracking Symptoms and Moods

1. Tap on any day in the calendar
2. Select symptoms you're experiencing
3. Choose your mood
4. Add optional notes
5. Tap "Save"

### Viewing History

1. Tap the "History" tab in the bottom navigation
2. View all your past periods and cycle lengths

### Adjusting Settings

1. Tap the "Settings" tab
2. Adjust your average cycle length and period duration
3. These help improve predictions
4. Tap "Save Settings"

### Exporting Your Data

1. Go to Settings tab
2. Tap "Export Data"
3. Your data will download as a JSON file

## App Calendar Legend

- 🌸 **Pink**: Period days (actual)
- 🌸 **Light Pink**: Predicted period days
- 💚 **Green**: Fertile window (best chances of conception)
- 💛 **Yellow**: Ovulation day

## Privacy & Security

- All data is stored locally on your device using browser localStorage
- No data is sent to any server
- No account or personal information required
- You have full control over your data with export/delete options

## Browser Compatibility

- ✅ Safari (iOS) - Optimized
- ✅ Chrome (Mobile)
- ✅ Firefox (Mobile)
- ✅ Any modern mobile browser

## Technical Details

- **Technology**: Pure HTML5, CSS3, and Vanilla JavaScript
- **Storage**: Browser localStorage
- **Size**: < 100KB total
- **No Dependencies**: Works standalone, no internet required after installation
- **PWA Features**: Service worker for offline functionality

## Development

The app is built as a single-page application with no build process required. All code is in:
- `index.html` - Main application (HTML, CSS, and JavaScript)
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline functionality

To modify, simply edit the files and refresh the page.

## Support

For issues or questions, please check:
- Make sure you're using a modern browser
- Clear cache if the app doesn't update
- For iOS Safari: Settings > Safari > Clear History and Website Data

## Credits

Created with care for Maggie 💝
