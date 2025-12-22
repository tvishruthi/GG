# Grateful & Grounded (G&G) 🌿✨

A beautiful, calming mental wellness web application that provides a safe digital space for journaling, daily affirmations, creative doodling, AI conversations, relaxing games, and personal diary entries.

![G&G Banner](https://img.shields.io/badge/Mental_Wellness-App-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-success)

---

## 📋 Table of Contents

- [Features](#-features)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Dependencies](#-dependencies)
- [Installation & Setup](#-installation--setup)
- [Running Locally](#-running-locally)
- [Usage Guide](#-usage-guide)
- [Browser Compatibility](#-browser-compatibility)
- [Customization](#-customization)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

### 🏠 Interactive Dashboard
- **Bubble Navigation System**: 6 interconnected features with smooth hover effects
- **Glassmorphism Design**: Frosted glass UI with soft shadows and blur effects
- **Animated Connections**: Color-coded lines light up on hover (red, yellow, pink, green, purple, blue)
- **Parallax Mouse Tracking**: Elements move dynamically based on cursor position
- **3D Tilt Effect**: Cards rotate in 3D space when you hover over them
- **Profile Panel**: Slide-out sidebar with demo profile information

### 📖 Journal
Daily reflection and gratitude tracking with a clean, distraction-free interface.

### 💛 Affirmations
Positive daily affirmations to boost mental wellness and self-confidence.

### 🎨 Doodle Canvas
**Full-featured drawing application:**
- Tools: Pencil ✏️, Eraser 🧼, Heart Stamp ❤️, Star Stamp ⭐
- Adjustable brush size (2-24px)
- 5 preset colors + custom color picker
- 3 template themes:
  - 🌿 Green chill
  - 🌌 Purple night
  - 🍓 Pink candy
- Save drawings as PNG files
- Dotted paper background effect

### 💬 AI Chatbox
Conversational AI companion for mental health support (ready for API integration).

### 🎮 Games
Relaxing mini-games designed to reduce stress and improve focus.

### 📝 Diary Entry
**Rich text editor with advanced features:**
- Formatting: **Bold**, *Italic*, <u>Underline</u>
- Text colors: Black, Pink, Blue, Green
- Highlight colors: Yellow, Pink, Blue (toggle on/off with double-click)
- Page background color picker
- Mood bubbles: 🌿 Calm, 🌈 Bright, 😴 Tired, 💭 Spinning, 🌧️ Heavy, 🏅 Proud
- Entry tags: School, Family, Health
- Character counter
- Save entries as `.txt` files with date stamp
- Dotted paper aesthetic

---

## 🚀 Quick Start


1. Download the project
git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
2. Open in browser
Just double-click index.html OR use a local server:
python -m http.server 8000
3. Visit in browser
http://localhost:8000
text

**That's it! No build process, no npm install, no configuration needed.**

---

## 📁 Project Structure


grateful-grounded/
│
├── index.html # Main dashboard (landing page)
│ └── Features: Interactive bubble navigation, profile panel
│
├── journal.html # Daily journal interface
│ └── Features: Reflection tracking, gratitude logging
│
├── affirm.html # Affirmations page
│ └── Features: Daily positive messages
│
├── doodle.html # Drawing canvas
│ └── Features: Freehand drawing, stamps, themes, save PNG
│
├── diary.html # Diary text editor
│ └── Features: Rich text formatting, mood tracking, save TXT
│
├── ai-chat.html # AI chatbot interface
│ └── Features: Conversational UI (ready for API)
│
├── games.html # Mini-games collection
│ └── Features: Stress-relief games
│
├── contact.html # Contact/feedback page
│ └── Features: Get in touch form
│
├── README.md # This file
├── LICENSE # MIT License
└── .gitignore # Git ignore rules
text

### File Relationships


graph TD
A[index.html
Dashboard] --> B[journal.html]
A --> C[affirm.html]
A --> D[doodle.html]
A --> E[ai-chat.html]
A --> F[games.html]
A --> G[diary.html]
A --> H[contact.html]
text

---

## 📦 Dependencies

### External CDN Resources

This project uses **zero npm dependencies** and loads everything via CDN:

| Resource | Version | Purpose | CDN Link |
|----------|---------|---------|----------|
| **TailwindCSS** | Latest | Utility-first CSS framework | `https://cdn.tailwindcss.com` |
| **Lucide Icons** | Latest | Icon library | `https://unpkg.com/lucide@latest` |
| **Google Fonts** | - | Typography (Plus Jakarta Sans, Playfair Display) | `https://fonts.googleapis.com` |

### Why CDN?

✅ **No build process** – Just open files in a browser  
✅ **Always up-to-date** – Automatically uses latest versions  
✅ **Fast loading** – Leverages global CDN caching  
✅ **Zero configuration** – Works immediately  

**Offline Alternative:**  
If you need offline support, download these libraries and update the `<script>` and `<link>` tags to point to local files.

---

## 🛠️ Installation & Setup

### Prerequisites

- **Web Browser** (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Text Editor** (VS Code, Sublime Text, Atom, etc.) – optional, for customization
- **Python 3** or **Node.js** – optional, for running a local server

### Step 1: Download the Project

**Option A: Clone with Git**

git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
text

**Option B: Download ZIP**
1. Click the green "Code" button on GitHub
2. Select "Download ZIP"
3. Extract to a folder

### Step 2: Verify File Structure

Ensure you have all 8 HTML files:

ls -1 *.html
Expected output:
affirm.html
ai-chat.html
contact.html
diary.html
doodle.html
games.html
index.html
journal.html
text

### Step 3: Test in Browser

**Quick Test:**
1. Double-click `index.html`
2. Your default browser should open the dashboard

**If that doesn't work, see [Running Locally](#-running-locally) below.**

---

## 💻 Running Locally

### Method 1: Direct File Open (Simplest)

1. Navigate to project folder
2. Double-click `index.html`
3. The app opens in your default browser

**Limitations:**  
- May have CORS issues with some features
- File URLs (`file://`) are less secure

---

### Method 2: Python HTTP Server (Recommended)

**Python 3.x:**

cd grateful-grounded
python -m http.server 8000
text

**Python 2.x:**

python -m SimpleHTTPServer 8000
text

**Then visit:**

http://localhost:8000
text

**Why this is better:**  
✅ Proper HTTP server (not file://)  
✅ No CORS issues  
✅ Mimics production environment  

---

### Method 3: Node.js HTTP Server

**Install `http-server` globally:**

npm install -g http-server
text

**Run:**

cd grateful-grounded
http-server -p 8000
text

**Visit:**

http://localhost:8000
text

---

### Method 4: PHP Server

**If you have PHP installed:**

cd grateful-grounded
php -S localhost:8000
text

---

### Method 5: VS Code Live Server Extension

1. Install **Live Server** extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

**Auto-reloads on file changes!**

---

## 📖 Usage Guide

### Dashboard Navigation

1. **Open `index.html`** – You'll see the main dashboard
2. **Hover over bubbles** – Watch the connecting lines light up
3. **Click any bubble** – Navigate to that feature
4. **Click the cat** – All lines glow + opens profile panel
5. **Profile chip** (top-right) – Opens profile sidebar

### Doodle Canvas

1. **Select tool**: Pencil, Eraser, Heart, or Star
2. **Choose color**: Click a color dot or use custom picker
3. **Adjust size**: Drag the brush size slider
4. **Draw**: Click/drag on canvas
5. **Change theme**: Click theme buttons (green/purple/pink)
6. **Clear**: Click 🧻 Clear button
7. **Save**: Click 💾 Save doodle (downloads PNG)

### Diary Entry

1. **Select mood**: Click a mood bubble (changes background)
2. **Type text**: Click in the paper area and start writing
3. **Format text**:
   - Select text → Click **B** (bold), *i* (italic), or <u>U</u> (underline)
   - Select text → Click color dot to change text color
   - Select text → Click highlight color to highlight
   - Click same highlight again to remove
4. **Add tag**: Click School/Family/Health
5. **Save**: Click 💾 Save button (downloads `diary_YYYY-MM-DD.txt`)

---

## 🌐 Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge | Opera |
|---------|--------|---------|--------|------|-------|
| Dashboard | ✅ 90+ | ✅ 88+ | ✅ 14+ | ✅ 90+ | ✅ 76+ |
| Glassmorphism | ✅ | ✅ | ✅ | ✅ | ✅ |
| Canvas Drawing | ✅ | ✅ | ✅ | ✅ | ✅ |
| contenteditable | ✅ | ✅ | ✅ | ✅ | ✅ |
| File Download | ✅ | ✅ | ✅ | ✅ | ✅ |

**Minimum Requirements:**
- JavaScript enabled
- CSS3 support (backdrop-filter)
- HTML5 Canvas API
- ES6 JavaScript

---

## 🎨 Customization

### Change Colors

**Edit the CSS variables in each HTML file:**

:root {
--bg-main: #f9a8d4; /* Main background /
--ink: #111827; / Dark text/borders /
--paper: #fdfbf6; / Paper background */
}
text

### Change Fonts

**Replace Google Fonts link:**

<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet"> ```
Add New Features
Create new-feature.html
Add bubble in index.html:
text
<div data-link="new-feature.html" class="parallax-wrap">
  <div class="glass-box">
    <i data-lucide="your-icon"></i>
    <span>New Feature</span>
  </div>
</div>


🐛 Troubleshooting
Issue: Dashboard bubbles don't animate
Solution:
Ensure JavaScript is enabled
Check browser console for errors (F12)
Try refreshing the page (Ctrl/Cmd + R)
Issue: Icons don't show
Solution:
Check internet connection (Lucide loads from CDN)
Clear browser cache
Verify lucide.createIcons() is called in script
Issue: Doodle canvas won't draw
Solution:
Check if browser supports HTML5 Canvas
Try using a different browser
Ensure mouse events are working
Issue: Diary formatting doesn't work
Solution:
Select text first
Then click formatting button
Check if contenteditable is supported
Try in Chrome/Firefox for best support
Issue: Files won't save
Solution:
Check browser download settings
Allow pop-ups from the site
Ensure browser has file download permissions

🤝 Contributing
Contributions welcome! Follow these steps:
Fork the repository
Create a feature branch:
text
git checkout -b feature/amazing-feature


Commit your changes:
text
git commit -m 'Add amazing feature'


Push to the branch:
text
git push origin feature/amazing-feature


Open a Pull Request
Development Guidelines
Keep code clean and commented
Test in multiple browsers
Maintain the calming aesthetic
No external npm dependencies
Mobile-friendly changes encouraged

📄 License
This project is licensed under the MIT License.
text
MIT License - Copyright (c) 2025 Vishruthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...

See 
LICENSE
 file for full details.

👤 Author
Vishruthi
Created with 💖 for mental wellness

🙏 Acknowledgments
Design Inspiration: Glassmorphism trend, mental wellness apps
Icons: 
Lucide Icons
 – MIT Licensed
Fonts: 
Google Fonts
 – Open Font License
CSS Framework: 
TailwindCSS
 – MIT Licensed

📧 Support & Contact
Issues: 
GitHub Issues
Discussions: 
GitHub Discussions
Email: Use the Contact page in the app
<div align="center">
🌟 Star this repo if it helped you! ⭐
Made with ❤️ for a calmer, grounded life

</div> ```
Additional files to include:
.gitignore:
text
# macOS
.DS_Store
.AppleDouble
.LSOverride

# Windows
Thumbs.db
Desktop.ini

# Editor
.vscode/
.idea/
*.swp
*.swo
*~

# Logs
*.log
npm-debug.log*

# Dependencies (if you add any)
node_modules/
package-lock.json

This README is production-ready and covers everything someone needs to understand, install, and run your project! 🚀
this is web link gg-murex.vercel.app and mit lience is also there
1 step completed
Perfect! Here's the updated README.md with your live Vercel link and MIT license already included:
text
# Grateful & Grounded (G&G) 🌿✨

A beautiful, calming mental wellness web application that provides a safe digital space for journaling, daily affirmations, creative doodling, AI conversations, relaxing games, and personal diary entries.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-brightgreen?style=for-the-badge)](https://gg-murex.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🌐 Live Demo

**Try it now:** [gg-murex.vercel.app](https://gg-murex.vercel.app/)

No installation needed – just click and explore!

---

## 📋 Table of Contents

- [Features](#-features)
- [Live Demo](#-live-demo)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Dependencies](#-dependencies)
- [Installation & Setup](#-installation--setup)
- [Running Locally](#-running-locally)
- [Usage Guide](#-usage-guide)
- [Deployment](#-deployment)
- [Browser Compatibility](#-browser-compatibility)
- [Customization](#-customization)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

### 🏠 Interactive Dashboard
- **Bubble Navigation System**: 6 interconnected features with smooth hover effects
- **Glassmorphism Design**: Frosted glass UI with soft shadows and blur effects
- **Animated Connections**: Color-coded lines light up on hover (red, yellow, pink, green, purple, blue)
- **Parallax Mouse Tracking**: Elements move dynamically based on cursor position
- **3D Tilt Effect**: Cards rotate in 3D space when you hover over them
- **Profile Panel**: Slide-out sidebar with demo profile information

### 📖 Journal
Daily reflection and gratitude tracking with a clean, distraction-free interface.

### 💛 Affirmations
Positive daily affirmations to boost mental wellness and self-confidence.

### 🎨 Doodle Canvas
**Full-featured drawing application:**
- Tools: Pencil ✏️, Eraser 🧼, Heart Stamp ❤️, Star Stamp ⭐
- Adjustable brush size (2-24px)
- 5 preset colors + custom color picker
- 3 template themes:
  - 🌿 Green chill
  - 🌌 Purple night
  - 🍓 Pink candy
- Save drawings as PNG files
- Dotted paper background effect

### 💬 AI Chatbox
Conversational AI companion for mental health support (ready for API integration).

### 🎮 Games
Relaxing mini-games designed to reduce stress and improve focus.

### 📝 Diary Entry
**Rich text editor with advanced features:**
- Formatting: **Bold**, *Italic*, <u>Underline</u>
- Text colors: Black, Pink, Blue, Green
- Highlight colors: Yellow, Pink, Blue (toggle on/off with double-click)
- Page background color picker
- Mood bubbles: 🌿 Calm, 🌈 Bright, 😴 Tired, 💭 Spinning, 🌧️ Heavy, 🏅 Proud
- Entry tags: School, Family, Health
- Character counter
- Save entries as `.txt` files with date stamp
- Dotted paper aesthetic

---

## 🚀 Quick Start

### Option 1: Use Live Version (Easiest)

Just visit: **[gg-murex.vercel.app](https://gg-murex.vercel.app/)**

### Option 2: Run Locally


1. Clone the repository
git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
2. Open in browser
Just double-click index.html OR use a local server:
python -m http.server 8000
3. Visit in browser
http://localhost:8000
text

**That's it! No build process, no npm install, no configuration needed.**

---

## 📁 Project Structure


grateful-grounded/
│
├── index.html # Main dashboard (landing page)
│ └── Features: Interactive bubble navigation, profile panel
│
├── journal.html # Daily journal interface
│ └── Features: Reflection tracking, gratitude logging
│
├── affirm.html # Affirmations page
│ └── Features: Daily positive messages
│
├── doodle.html # Drawing canvas
│ └── Features: Freehand drawing, stamps, themes, save PNG
│
├── diary.html # Diary text editor
│ └── Features: Rich text formatting, mood tracking, save TXT
│
├── ai-chat.html # AI chatbot interface
│ └── Features: Conversational UI (ready for API)
│
├── games.html # Mini-games collection
│ └── Features: Stress-relief games
│
├── contact.html # Contact/feedback page
│ └── Features: Get in touch form
│
├── README.md # This file
├── LICENSE # MIT License
└── .gitignore # Git ignore rules
text

### File Relationships


index.html (Dashboard)
├── journal.html
├── affirm.html
├── doodle.html
├── ai-chat.html
├── games.html
├── diary.html
└── contact.html
text

---

## 📦 Dependencies

### External CDN Resources

This project uses **zero npm dependencies** and loads everything via CDN:

| Resource | Version | Purpose | CDN Link |
|----------|---------|---------|----------|
| **TailwindCSS** | Latest | Utility-first CSS framework | `https://cdn.tailwindcss.com` |
| **Lucide Icons** | Latest | Icon library | `https://unpkg.com/lucide@latest` |
| **Google Fonts** | - | Typography (Plus Jakarta Sans, Playfair Display) | `https://fonts.googleapis.com` |

### Why CDN?

✅ **No build process** – Just open files in a browser  
✅ **Always up-to-date** – Automatically uses latest versions  
✅ **Fast loading** – Leverages global CDN caching  
✅ **Zero configuration** – Works immediately  

---

## 🛠️ Installation & Setup

### Prerequisites

- **Web Browser** (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Text Editor** (VS Code, Sublime Text, Atom, etc.) – optional, for customization
- **Python 3** or **Node.js** – optional, for running a local server

### Step 1: Download the Project

**Option A: Clone with Git**

git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
text

**Option B: Download ZIP**
1. Click the green "Code" button on GitHub
2. Select "Download ZIP"
3. Extract to a folder

### Step 2: Verify File Structure

Ensure you have all 8 HTML files:

ls -1 *.html
Expected output:
affirm.html
ai-chat.html
contact.html
diary.html
doodle.html
games.html
index.html
journal.html
text

---

## 💻 Running Locally

### Method 1: Direct File Open

1. Navigate to project folder
2. Double-click `index.html`
3. Opens in your default browser

---

### Method 2: Python HTTP Server (Recommended)

**Python 3.x:**

cd grateful-grounded
python -m http.server 8000
text

**Then visit:** `http://localhost:8000`

---

### Method 3: Node.js HTTP Server


npm install -g http-server
cd grateful-grounded
http-server -p 8000
text

**Visit:** `http://localhost:8000`

---

### Method 4: VS Code Live Server

1. Install **Live Server** extension
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## 📖 Usage Guide

### Dashboard Navigation

1. **Visit** [gg-murex.vercel.app](https://gg-murex.vercel.app/)
2. **Hover over bubbles** – Watch connecting lines light up
3. **Click any bubble** – Navigate to that feature
4. **Click the cat** – All lines glow + opens profile panel
5. **Profile chip** (top-right) – Opens profile sidebar

### Doodle Canvas

1. Select tool (Pencil/Eraser/Heart/Star)
2. Choose color (preset or custom)
3. Adjust brush size with slider
4. Draw on canvas
5. Change theme (green/purple/pink)
6. Save as PNG

### Diary Entry

1. Select mood bubble
2. Type in the paper area
3. Format text:
   - Select → Click **B**/**i**/**U**
   - Select → Click color dot
   - Select → Click highlight (click again to remove)
4. Add tag (School/Family/Health)
5. Save as TXT file

---

## 🚀 Deployment

### Deployed on Vercel

**Live URL:** [gg-murex.vercel.app](https://gg-murex.vercel.app/)

### Deploy Your Own

**1. Fork this repository**

**2. Connect to Vercel:**

Install Vercel CLI
npm i -g vercel
Deploy
vercel
text

**3. Or use GitHub integration:**
- Go to [vercel.com](https://vercel.com)
- Import your forked repo
- Deploy automatically on every push

### Deploy to Other Platforms

**Netlify:**

Drag & drop your folder to netlify.com
OR use CLI:
npm install -g netlify-cli
netlify deploy --prod
text

**GitHub Pages:**

Push to gh-pages branch
git checkout -b gh-pages
git push origin gh-pages
Enable in repo settings → Pages
text

---

## 🌐 Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge |
|---------|--------|---------|--------|------|
| Dashboard | ✅ 90+ | ✅ 88+ | ✅ 14+ | ✅ 90+ |
| Glassmorphism | ✅ | ✅ | ✅ | ✅ |
| Canvas Drawing | ✅ | ✅ | ✅ | ✅ |
| Rich Text Editor | ✅ | ✅ | ✅ | ✅ |
| File Download | ✅ | ✅ | ✅ | ✅ |

---

## 🎨 Customization

### Change Colors

Edit CSS variables in any HTML file:

:root {
--bg-main: #f9a8d4; /* Main background /
--ink: #111827; / Dark borders /
--paper: #fdfbf6; / Paper color */
}
text

### Change Fonts

Replace Google Fonts link:

<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet"> ```
🐛 Troubleshooting
Issue: Icons don't show
Check internet connection (CDN required)
Clear browser cache
Issue: Doodle won't draw
Ensure HTML5 Canvas is supported
Try Chrome/Firefox
Issue: Diary formatting fails
Select text first
Then click format button
Use Chrome for best support

🤝 Contributing
Contributions welcome! Follow these steps:
Fork the repository
Create a feature branch: git checkout -b feature/amazing-feature
Commit changes: git commit -m 'Add feature'
Push: git push origin feature/amazing-feature
Open a Pull Request

📄 License
This project is licensed under the MIT License – see 
LICENSE
 file for details.
text
MIT License

Copyright (c) 2025 Vishruthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


👤 Author
Vishruthi
Created with 💖 for mental wellness

🙏 Acknowledgments
Icons: 
Lucide Icons
Fonts: 
Google Fonts
Framework: 
TailwindCSS
Hosting: 
Vercel

📧 Support
Live Demo: 
gg-murex.vercel.app
Issues: 
GitHub Issues
Contact: Use the Contact page in the app
<div align="center">
🌟 
Try it Live
 | ⭐ Star this repo if it helped you!
Made with ❤️ for a calmer, grounded life

</div> ```
Perfect! Ab yeh README production-ready hai with your live link and MIT license! 🚀✨
# Grateful & Grounded (G&G) 🌿✨

A beautiful, calming mental wellness web application that provides a safe digital space for journaling, daily affirmations, creative doodling, AI conversations, relaxing games, and personal diary entries.

![G&G Banner](https://img.shields.io/badge/Mental_Wellness-App-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-success)

---

## 📋 Table of Contents

- [Features](#-features)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Dependencies](#-dependencies)
- [Installation & Setup](#-installation--setup)
- [Running Locally](#-running-locally)
- [Usage Guide](#-usage-guide)
- [Browser Compatibility](#-browser-compatibility)
- [Customization](#-customization)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

### 🏠 Interactive Dashboard
- **Bubble Navigation System**: 6 interconnected features with smooth hover effects
- **Glassmorphism Design**: Frosted glass UI with soft shadows and blur effects
- **Animated Connections**: Color-coded lines light up on hover (red, yellow, pink, green, purple, blue)
- **Parallax Mouse Tracking**: Elements move dynamically based on cursor position
- **3D Tilt Effect**: Cards rotate in 3D space when you hover over them
- **Profile Panel**: Slide-out sidebar with demo profile information

### 📖 Journal
Daily reflection and gratitude tracking with a clean, distraction-free interface.

### 💛 Affirmations
Positive daily affirmations to boost mental wellness and self-confidence.

### 🎨 Doodle Canvas
**Full-featured drawing application:**
- Tools: Pencil ✏️, Eraser 🧼, Heart Stamp ❤️, Star Stamp ⭐
- Adjustable brush size (2-24px)
- 5 preset colors + custom color picker
- 3 template themes:
  - 🌿 Green chill
  - 🌌 Purple night
  - 🍓 Pink candy
- Save drawings as PNG files
- Dotted paper background effect

### 💬 AI Chatbox
Conversational AI companion for mental health support (ready for API integration).

### 🎮 Games
Relaxing mini-games designed to reduce stress and improve focus.

### 📝 Diary Entry
**Rich text editor with advanced features:**
- Formatting: **Bold**, *Italic*, <u>Underline</u>
- Text colors: Black, Pink, Blue, Green
- Highlight colors: Yellow, Pink, Blue (toggle on/off with double-click)
- Page background color picker
- Mood bubbles: 🌿 Calm, 🌈 Bright, 😴 Tired, 💭 Spinning, 🌧️ Heavy, 🏅 Proud
- Entry tags: School, Family, Health
- Character counter
- Save entries as `.txt` files with date stamp
- Dotted paper aesthetic

---

## 🚀 Quick Start


1. Download the project
git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
2. Open in browser
Just double-click index.html OR use a local server:
python -m http.server 8000
3. Visit in browser
http://localhost:8000
text

**That's it! No build process, no npm install, no configuration needed.**

---

## 📁 Project Structure


grateful-grounded/
│
├── index.html # Main dashboard (landing page)
│ └── Features: Interactive bubble navigation, profile panel
│
├── journal.html # Daily journal interface
│ └── Features: Reflection tracking, gratitude logging
│
├── affirm.html # Affirmations page
│ └── Features: Daily positive messages
│
├── doodle.html # Drawing canvas
│ └── Features: Freehand drawing, stamps, themes, save PNG
│
├── diary.html # Diary text editor
│ └── Features: Rich text formatting, mood tracking, save TXT
│
├── ai-chat.html # AI chatbot interface
│ └── Features: Conversational UI (ready for API)
│
├── games.html # Mini-games collection
│ └── Features: Stress-relief games
│
├── contact.html # Contact/feedback page
│ └── Features: Get in touch form
│
├── README.md # This file
├── LICENSE # MIT License
└── .gitignore # Git ignore rules
text

### File Relationships


graph TD
A[index.html
Dashboard] --> B[journal.html]
A --> C[affirm.html]
A --> D[doodle.html]
A --> E[ai-chat.html]
A --> F[games.html]
A --> G[diary.html]
A --> H[contact.html]
text

---

## 📦 Dependencies

### External CDN Resources

This project uses **zero npm dependencies** and loads everything via CDN:

| Resource | Version | Purpose | CDN Link |
|----------|---------|---------|----------|
| **TailwindCSS** | Latest | Utility-first CSS framework | `https://cdn.tailwindcss.com` |
| **Lucide Icons** | Latest | Icon library | `https://unpkg.com/lucide@latest` |
| **Google Fonts** | - | Typography (Plus Jakarta Sans, Playfair Display) | `https://fonts.googleapis.com` |

### Why CDN?

✅ **No build process** – Just open files in a browser  
✅ **Always up-to-date** – Automatically uses latest versions  
✅ **Fast loading** – Leverages global CDN caching  
✅ **Zero configuration** – Works immediately  

**Offline Alternative:**  
If you need offline support, download these libraries and update the `<script>` and `<link>` tags to point to local files.

---

## 🛠️ Installation & Setup

### Prerequisites

- **Web Browser** (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Text Editor** (VS Code, Sublime Text, Atom, etc.) – optional, for customization
- **Python 3** or **Node.js** – optional, for running a local server

### Step 1: Download the Project

**Option A: Clone with Git**

git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
text

**Option B: Download ZIP**
1. Click the green "Code" button on GitHub
2. Select "Download ZIP"
3. Extract to a folder

### Step 2: Verify File Structure

Ensure you have all 8 HTML files:

ls -1 *.html
Expected output:
affirm.html
ai-chat.html
contact.html
diary.html
doodle.html
games.html
index.html
journal.html
text

### Step 3: Test in Browser

**Quick Test:**
1. Double-click `index.html`
2. Your default browser should open the dashboard

**If that doesn't work, see [Running Locally](#-running-locally) below.**

---

## 💻 Running Locally

### Method 1: Direct File Open (Simplest)

1. Navigate to project folder
2. Double-click `index.html`
3. The app opens in your default browser

**Limitations:**  
- May have CORS issues with some features
- File URLs (`file://`) are less secure

---

### Method 2: Python HTTP Server (Recommended)

**Python 3.x:**

cd grateful-grounded
python -m http.server 8000
text

**Python 2.x:**

python -m SimpleHTTPServer 8000
text

**Then visit:**

http://localhost:8000
text

**Why this is better:**  
✅ Proper HTTP server (not file://)  
✅ No CORS issues  
✅ Mimics production environment  

---

### Method 3: Node.js HTTP Server

**Install `http-server` globally:**

npm install -g http-server
text

**Run:**

cd grateful-grounded
http-server -p 8000
text

**Visit:**

http://localhost:8000
text

---

### Method 4: PHP Server

**If you have PHP installed:**

cd grateful-grounded
php -S localhost:8000
text

---

### Method 5: VS Code Live Server Extension

1. Install **Live Server** extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

**Auto-reloads on file changes!**

---

## 📖 Usage Guide

### Dashboard Navigation

1. **Open `index.html`** – You'll see the main dashboard
2. **Hover over bubbles** – Watch the connecting lines light up
3. **Click any bubble** – Navigate to that feature
4. **Click the cat** – All lines glow + opens profile panel
5. **Profile chip** (top-right) – Opens profile sidebar

### Doodle Canvas

1. **Select tool**: Pencil, Eraser, Heart, or Star
2. **Choose color**: Click a color dot or use custom picker
3. **Adjust size**: Drag the brush size slider
4. **Draw**: Click/drag on canvas
5. **Change theme**: Click theme buttons (green/purple/pink)
6. **Clear**: Click 🧻 Clear button
7. **Save**: Click 💾 Save doodle (downloads PNG)

### Diary Entry

1. **Select mood**: Click a mood bubble (changes background)
2. **Type text**: Click in the paper area and start writing
3. **Format text**:
   - Select text → Click **B** (bold), *i* (italic), or <u>U</u> (underline)
   - Select text → Click color dot to change text color
   - Select text → Click highlight color to highlight
   - Click same highlight again to remove
4. **Add tag**: Click School/Family/Health
5. **Save**: Click 💾 Save button (downloads `diary_YYYY-MM-DD.txt`)

---

## 🌐 Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge | Opera |
|---------|--------|---------|--------|------|-------|
| Dashboard | ✅ 90+ | ✅ 88+ | ✅ 14+ | ✅ 90+ | ✅ 76+ |
| Glassmorphism | ✅ | ✅ | ✅ | ✅ | ✅ |
| Canvas Drawing | ✅ | ✅ | ✅ | ✅ | ✅ |
| contenteditable | ✅ | ✅ | ✅ | ✅ | ✅ |
| File Download | ✅ | ✅ | ✅ | ✅ | ✅ |

**Minimum Requirements:**
- JavaScript enabled
- CSS3 support (backdrop-filter)
- HTML5 Canvas API
- ES6 JavaScript

---

## 🎨 Customization

### Change Colors

**Edit the CSS variables in each HTML file:**

:root {
--bg-main: #f9a8d4; /* Main background /
--ink: #111827; / Dark text/borders /
--paper: #fdfbf6; / Paper background */
}
text

### Change Fonts

**Replace Google Fonts link:**

<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet"> ```
Add New Features
Create new-feature.html
Add bubble in index.html:
text
<div data-link="new-feature.html" class="parallax-wrap">
  <div class="glass-box">
    <i data-lucide="your-icon"></i>
    <span>New Feature</span>
  </div>
</div>


🐛 Troubleshooting
Issue: Dashboard bubbles don't animate
Solution:
Ensure JavaScript is enabled
Check browser console for errors (F12)
Try refreshing the page (Ctrl/Cmd + R)
Issue: Icons don't show
Solution:
Check internet connection (Lucide loads from CDN)
Clear browser cache
Verify lucide.createIcons() is called in script
Issue: Doodle canvas won't draw
Solution:
Check if browser supports HTML5 Canvas
Try using a different browser
Ensure mouse events are working
Issue: Diary formatting doesn't work
Solution:
Select text first
Then click formatting button
Check if contenteditable is supported
Try in Chrome/Firefox for best support
Issue: Files won't save
Solution:
Check browser download settings
Allow pop-ups from the site
Ensure browser has file download permissions

🤝 Contributing
Contributions welcome! Follow these steps:
Fork the repository
Create a feature branch:
text
git checkout -b feature/amazing-feature


Commit your changes:
text
git commit -m 'Add amazing feature'


Push to the branch:
text
git push origin feature/amazing-feature


Open a Pull Request
Development Guidelines
Keep code clean and commented
Test in multiple browsers
Maintain the calming aesthetic
No external npm dependencies
Mobile-friendly changes encouraged

📄 License
This project is licensed under the MIT License.
text
MIT License - Copyright (c) 2025 Vishruthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...

See 
LICENSE
 file for full details.

👤 Author
Vishruthi
Created with 💖 for mental wellness

🙏 Acknowledgments
Design Inspiration: Glassmorphism trend, mental wellness apps
Icons: 
Lucide Icons
 – MIT Licensed
Fonts: 
Google Fonts
 – Open Font License
CSS Framework: 
TailwindCSS
 – MIT Licensed

📧 Support & Contact
Issues: 
GitHub Issues
Discussions: 
GitHub Discussions
Email: Use the Contact page in the app
<div align="center">
🌟 Star this repo if it helped you! ⭐
Made with ❤️ for a calmer, grounded life

</div> ```
Additional files to include:
.gitignore:
text
# macOS
.DS_Store
.AppleDouble
.LSOverride

# Windows
Thumbs.db
Desktop.ini

# Editor
.vscode/
.idea/
*.swp
*.swo
*~

# Logs
*.log
npm-debug.log*

# Dependencies (if you add any)
node_modules/
package-lock.json

This README is production-ready and covers everything someone needs to understand, install, and run your project! 🚀
this is web link gg-murex.vercel.app and mit lience is also there
1 step completed
Perfect! Here's the updated README.md with your live Vercel link and MIT license already included:
text
# Grateful & Grounded (G&G) 🌿✨

A beautiful, calming mental wellness web application that provides a safe digital space for journaling, daily affirmations, creative doodling, AI conversations, relaxing games, and personal diary entries.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-brightgreen?style=for-the-badge)](https://gg-murex.vercel.app)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🌐 Live Demo

**Try it now:** [gg-murex.vercel.app](https://gg-murex.vercel.app/)

No installation needed – just click and explore!

---

## 📋 Table of Contents

- [Features](#-features)
- [Live Demo](#-live-demo)
- [Quick Start](#-quick-start)
- [Project Structure](#-project-structure)
- [Dependencies](#-dependencies)
- [Installation & Setup](#-installation--setup)
- [Running Locally](#-running-locally)
- [Usage Guide](#-usage-guide)
- [Deployment](#-deployment)
- [Browser Compatibility](#-browser-compatibility)
- [Customization](#-customization)
- [Troubleshooting](#-troubleshooting)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

### 🏠 Interactive Dashboard
- **Bubble Navigation System**: 6 interconnected features with smooth hover effects
- **Glassmorphism Design**: Frosted glass UI with soft shadows and blur effects
- **Animated Connections**: Color-coded lines light up on hover (red, yellow, pink, green, purple, blue)
- **Parallax Mouse Tracking**: Elements move dynamically based on cursor position
- **3D Tilt Effect**: Cards rotate in 3D space when you hover over them
- **Profile Panel**: Slide-out sidebar with demo profile information

### 📖 Journal
Daily reflection and gratitude tracking with a clean, distraction-free interface.

### 💛 Affirmations
Positive daily affirmations to boost mental wellness and self-confidence.

### 🎨 Doodle Canvas
**Full-featured drawing application:**
- Tools: Pencil ✏️, Eraser 🧼, Heart Stamp ❤️, Star Stamp ⭐
- Adjustable brush size (2-24px)
- 5 preset colors + custom color picker
- 3 template themes:
  - 🌿 Green chill
  - 🌌 Purple night
  - 🍓 Pink candy
- Save drawings as PNG files
- Dotted paper background effect

### 💬 AI Chatbox
Conversational AI companion for mental health support (ready for API integration).

### 🎮 Games
Relaxing mini-games designed to reduce stress and improve focus.

### 📝 Diary Entry
**Rich text editor with advanced features:**
- Formatting: **Bold**, *Italic*, <u>Underline</u>
- Text colors: Black, Pink, Blue, Green
- Highlight colors: Yellow, Pink, Blue (toggle on/off with double-click)
- Page background color picker
- Mood bubbles: 🌿 Calm, 🌈 Bright, 😴 Tired, 💭 Spinning, 🌧️ Heavy, 🏅 Proud
- Entry tags: School, Family, Health
- Character counter
- Save entries as `.txt` files with date stamp
- Dotted paper aesthetic

---

## 🚀 Quick Start

### Option 1: Use Live Version (Easiest)

Just visit: **[gg-murex.vercel.app](https://gg-murex.vercel.app/)**

### Option 2: Run Locally


1. Clone the repository
git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
2. Open in browser
Just double-click index.html OR use a local server:
python -m http.server 8000
3. Visit in browser
http://localhost:8000
text

**That's it! No build process, no npm install, no configuration needed.**

---

## 📁 Project Structure


grateful-grounded/
│
├── index.html # Main dashboard (landing page)
│ └── Features: Interactive bubble navigation, profile panel
│
├── journal.html # Daily journal interface
│ └── Features: Reflection tracking, gratitude logging
│
├── affirm.html # Affirmations page
│ └── Features: Daily positive messages
│
├── doodle.html # Drawing canvas
│ └── Features: Freehand drawing, stamps, themes, save PNG
│
├── diary.html # Diary text editor
│ └── Features: Rich text formatting, mood tracking, save TXT
│
├── ai-chat.html # AI chatbot interface
│ └── Features: Conversational UI (ready for API)
│
├── games.html # Mini-games collection
│ └── Features: Stress-relief games
│
├── contact.html # Contact/feedback page
│ └── Features: Get in touch form
│
├── README.md # This file
├── LICENSE # MIT License
└── .gitignore # Git ignore rules
text

### File Relationships


index.html (Dashboard)
├── journal.html
├── affirm.html
├── doodle.html
├── ai-chat.html
├── games.html
├── diary.html
└── contact.html
text

---

## 📦 Dependencies

### External CDN Resources

This project uses **zero npm dependencies** and loads everything via CDN:

| Resource | Version | Purpose | CDN Link |
|----------|---------|---------|----------|
| **TailwindCSS** | Latest | Utility-first CSS framework | `https://cdn.tailwindcss.com` |
| **Lucide Icons** | Latest | Icon library | `https://unpkg.com/lucide@latest` |
| **Google Fonts** | - | Typography (Plus Jakarta Sans, Playfair Display) | `https://fonts.googleapis.com` |

### Why CDN?

✅ **No build process** – Just open files in a browser  
✅ **Always up-to-date** – Automatically uses latest versions  
✅ **Fast loading** – Leverages global CDN caching  
✅ **Zero configuration** – Works immediately  

---

## 🛠️ Installation & Setup

### Prerequisites

- **Web Browser** (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- **Text Editor** (VS Code, Sublime Text, Atom, etc.) – optional, for customization
- **Python 3** or **Node.js** – optional, for running a local server

### Step 1: Download the Project

**Option A: Clone with Git**

git clone 
https://github.com/yourusername/grateful-grounded.git

cd grateful-grounded
text

**Option B: Download ZIP**
1. Click the green "Code" button on GitHub
2. Select "Download ZIP"
3. Extract to a folder

### Step 2: Verify File Structure

Ensure you have all 8 HTML files:

ls -1 *.html
Expected output:
affirm.html
ai-chat.html
contact.html
diary.html
doodle.html
games.html
index.html
journal.html
text

---

## 💻 Running Locally

### Method 1: Direct File Open

1. Navigate to project folder
2. Double-click `index.html`
3. Opens in your default browser

---

### Method 2: Python HTTP Server (Recommended)

**Python 3.x:**

cd grateful-grounded
python -m http.server 8000
text

**Then visit:** `http://localhost:8000`

---

### Method 3: Node.js HTTP Server


npm install -g http-server
cd grateful-grounded
http-server -p 8000
text

**Visit:** `http://localhost:8000`

---

### Method 4: VS Code Live Server

1. Install **Live Server** extension
2. Right-click `index.html`
3. Select "Open with Live Server"

---

## 📖 Usage Guide

### Dashboard Navigation

1. **Visit** [gg-murex.vercel.app](https://gg-murex.vercel.app/)
2. **Hover over bubbles** – Watch connecting lines light up
3. **Click any bubble** – Navigate to that feature
4. **Click the cat** – All lines glow + opens profile panel
5. **Profile chip** (top-right) – Opens profile sidebar

### Doodle Canvas

1. Select tool (Pencil/Eraser/Heart/Star)
2. Choose color (preset or custom)
3. Adjust brush size with slider
4. Draw on canvas
5. Change theme (green/purple/pink)
6. Save as PNG

### Diary Entry

1. Select mood bubble
2. Type in the paper area
3. Format text:
   - Select → Click **B**/**i**/**U**
   - Select → Click color dot
   - Select → Click highlight (click again to remove)
4. Add tag (School/Family/Health)
5. Save as TXT file

---

## 🚀 Deployment

### Deployed on Vercel

**Live URL:** [gg-murex.vercel.app](https://gg-murex.vercel.app/)

### Deploy Your Own

**1. Fork this repository**

**2. Connect to Vercel:**

Install Vercel CLI
npm i -g vercel
Deploy
vercel
text

**3. Or use GitHub integration:**
- Go to [vercel.com](https://vercel.com)
- Import your forked repo
- Deploy automatically on every push

### Deploy to Other Platforms

**Netlify:**

Drag & drop your folder to netlify.com
OR use CLI:
npm install -g netlify-cli
netlify deploy --prod
text

**GitHub Pages:**

Push to gh-pages branch
git checkout -b gh-pages
git push origin gh-pages
Enable in repo settings → Pages
text

---

## 🌐 Browser Compatibility

| Feature | Chrome | Firefox | Safari | Edge |
|---------|--------|---------|--------|------|
| Dashboard | ✅ 90+ | ✅ 88+ | ✅ 14+ | ✅ 90+ |
| Glassmorphism | ✅ | ✅ | ✅ | ✅ |
| Canvas Drawing | ✅ | ✅ | ✅ | ✅ |
| Rich Text Editor | ✅ | ✅ | ✅ | ✅ |
| File Download | ✅ | ✅ | ✅ | ✅ |

---

## 🎨 Customization

### Change Colors

Edit CSS variables in any HTML file:

:root {
--bg-main: #f9a8d4; /* Main background /
--ink: #111827; / Dark borders /
--paper: #fdfbf6; / Paper color */
}
text

### Change Fonts

Replace Google Fonts link:

<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet"> ```
🐛 Troubleshooting
Issue: Icons don't show
Check internet connection (CDN required)
Clear browser cache
Issue: Doodle won't draw
Ensure HTML5 Canvas is supported
Try Chrome/Firefox
Issue: Diary formatting fails
Select text first
Then click format button
Use Chrome for best support

🤝 Contributing
Contributions welcome! Follow these steps:
Fork the repository
Create a feature branch: git checkout -b feature/amazing-feature
Commit changes: git commit -m 'Add feature'
Push: git push origin feature/amazing-feature
Open a Pull Request

📄 License
This project is licensed under the MIT License – see 
LICENSE
 file for details.
text
MIT License

Copyright (c) 2025 Vishruthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


👤 Author
Vishruthi
Created with 💖 for mental wellness

🙏 Acknowledgments
Icons: 
Lucide Icons
Fonts: 
Google Fonts
Framework: 
TailwindCSS
Hosting: 
Vercel

📧 Support
Live Demo: 
gg-murex.vercel.app
Issues: 
GitHub Issues
Contact: Use the Contact page in the app
<div align="center">
🌟 
Try it Live
 | ⭐ Star this repo if it helped you!
Made with ❤️ for a calmer, grounded life

</div> ```
Perfect! Ab yeh README production-ready hai with your live link and MIT license! 🚀✨

