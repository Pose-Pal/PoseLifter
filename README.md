
# 🪑 PosLifter

PosLifter is a real-time posture tracking web app that helps you maintain healthy sitting habits using AI-powered pose detection and subtle on-screen feedback.

## 🚀 Features

- 🎥 Real-time webcam-based posture analysis using MediaPipe
- 📉 Smart detection of slouching via shoulder-ear alignment
- 🔔 Notification or visual blur when posture worsens
- 🖼️ Picture-in-picture webcam window to monitor posture while multitasking
- 🎮 Gamified experience with levels and streak tracking (planned)
- 🔧 Settings tab for controlling sensitivity, reminders, and behavior
- 🔗 Chrome extension integration to persist posture tab in the background

## 🧠 How It Works

1. **MediaPipe Pose** detects 3D landmarks on your upper body in real time.
2. **Posture Analysis Logic** compares ear and shoulder positions to determine slouching.
3. **Browser Feedback** sends alerts via blur, notifications, or sounds.
4. **Gamification System** tracks streaks and improvements over time.

## 🔌 Tech Stack

- JavaScript
- MediaPipe Pose (by Google)
- HTML5 + CSS3
- Chrome Extensions (MV3)
- Canvas API

## 🧠 Future Features

- 📊 **Advanced posture analytics** (e.g. total slouch time, posture trends, historical graphs)
- 🎯 **Streaks, XP, and level system** to gamify posture improvement
- 🧘 **Stretch reminders** and personalized micro-exercise suggestions
- 🔊 **Voice guidance** or tone-based alerts when posture is poor
- 👥 **Multi-user support** (e.g., family or classroom mode)
- 📱 **Mobile-friendly version** for front-facing camera use on phones
- 🌍 **Support for other browsers** like Firefox and Edge
- 🧩 **Chrome Web Store publication** with easy installation for all users

## 📂 Project Structure

```
posepal-tracking/
├── icons/ # Extension icons and assets
├── mediapipe.libs/ # MediaPipe posture tracking library files
├── background.js # Background script for Chrome extension lifecycle
├── content_script.js # Script injected into the webpage for posture detection
├── index.html # Entry page (if needed for testing)
├── manifest.json # Chrome extension manifest configuration
├── script.js # Core posture tracking and UI logic
├── settings.html # Settings page for user preferences
├── settings.js # JS for the settings interface
├── settings.html.new # (Placeholder/unused)
├── settings.js.new # (Placeholder/unused)
├── style.css # Styles for notification overlays and UI
```

## 🛠️ Setup

1. Download the repository: Press <Code> on github and download and extract ZIP file.
2. Go to chrome://extensions/ and Enable Developer Mode (top right corner).
3. Click "Load unpacked" and Select the main branch folder of the repository which you extracted from the ZIP.
4. On first use, Chrome will prompt for webcam access, so grant permission so PoseLifter can analyze your posture in real-time.
5. Start Using.

## 🔧 Tips
- Press the 🎯 button while in a good position to calibrate a good position
- Press the 📺 button to enable picture in picture mode while browsing
- Press the ⚙️ button to navigate to settings and set features like posture sensitivity, detection delay, notifications, picture in picture, and blur.

## 🤝 Credits

- Developed at 🪿JAMHacks 9 by @thinkfir
- Uses [MediaPipe Pose](https://google.github.io/mediapipe/)

## 📄 License
MIT License
