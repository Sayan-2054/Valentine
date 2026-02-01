# 💕 Valentine's Day Website for Puchu

A beautiful, interactive Valentine's Day website created with love for Sushmita Sarkar (Puchu).

## 🎨 Features

### Visual Design
- **Animated Gradient Background** - Flowing colors in pink, red, blue, purple, violet, and orange
- **Floating Hearts Animation** - Romantic hearts floating across the screen
- **Glassmorphism Effects** - Modern frosted glass design with backdrop blur
- **Smooth Animations** - Elegant transitions and micro-interactions throughout

### Interactive Elements
- **Playful "No" Button** - The No button moves away when the cursor gets close (within 150px)
- **Impossible to Decline** - The No button escapes to random positions, making it impossible to click
- **Growing "Yes" Button** - After multiple attempts to click No, the Yes button grows larger
- **Smart Positioning** - Buttons never overlap, ensuring a smooth experience

### Two Beautiful Pages
1. **Question Page** - "Will You Be My Valentine, Puchu?" with interactive buttons
2. **Celebration Page** - Beautiful love letter with confetti and sparkles when she says Yes

## 🚀 How to Use

1. **Open the Website**
   - Simply open `valentine.html` in any modern web browser
   - Works on desktop, tablet, and mobile devices

2. **Share with Puchu**
   - Send the HTML file directly
   - Host it on a web server for a shareable link
   - Or upload to GitHub Pages, Netlify, or Vercel for free hosting

## 💻 Technical Details

### Technologies Used
- Pure HTML, CSS, and JavaScript (no dependencies required)
- Google Fonts: Playfair Display & Quicksand
- Responsive design for all screen sizes

### Browser Compatibility
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
```
valentine.html          # Single-file website (contains all HTML, CSS, JS)
README.md              # This file
```

## 🎯 How It Works

### The "No" Button Logic
- Tracks mouse/touch position in real-time
- Calculates distance from cursor to button
- When cursor gets within 150px, button moves to a random position
- Checks for overlap with Yes button and repositions if needed
- Movement range: 800px width × 400px height container

### The Celebration
- Confetti animation with multiple colors
- Sparkle effects appearing randomly
- Animated love letter with staggered text reveals
- Glowing title effect

## 📱 Responsive Design

The website adapts beautifully to different screen sizes:
- **Desktop**: Full-sized buttons with large movement area
- **Tablet**: Optimized spacing and button sizes
- **Mobile**: Touch-friendly with adjusted button positions

## 💝 Customization

Want to personalize further? Here's what you can modify:

### Colors
Look for these CSS variables and color values:
- Background gradient: Lines with `#ff6b9d`, `#c06c84`, `#6c5b7b`, etc.
- Button colors: `#ff6b9d`, `#ff8fab`

### Text Content
- Main question: Line with "Will You Be My Valentine?"
- Nickname: "Puchu, my dearest"
- Love letter: All paragraphs in the `.love-letter` section

### Animation Speed
- Gradient animation: `animation: gradientShift 15s`
- Heart floating: `animation: floatUp 8s`
- Confetti fall: `animation: confettiFall 3s`

## 🎁 Hosting Options

### Free Hosting Services
1. **GitHub Pages** - Push to GitHub and enable Pages
2. **Netlify** - Drag and drop the HTML file
3. **Vercel** - Quick deployment with custom domain
4. **Surge.sh** - Simple command-line deployment

### Quick Deploy to GitHub Pages
```bash
# Create a new repository
git init
git add valentine.html README.md
git commit -m "Valentine's website for Puchu"
git branch -M main
git remote add origin [your-repo-url]
git push -u origin main

# Enable GitHub Pages in repository settings
# Your site will be live at: https://[username].github.io/[repo-name]/valentine.html
```

## ❤️ Tips for Maximum Impact

1. **Timing** - Send it on Valentine's Day morning for maximum surprise
2. **Personal Touch** - Consider recording a voice message to send along with it
3. **Screenshot** - Take screenshots of her reaction when she tries clicking No!
4. **Follow Up** - Plan something special for after she says Yes

## 📝 License

Made with love ❤️ - Feel free to use and modify for your own romantic gestures!

---

**Created with:** HTML5, CSS3, JavaScript  
**Made for:** Sushmita Sarkar (Puchu) 💕  
**Purpose:** To make her smile and say Yes! ✨
**Designed and created by:** Sayantan Chowdhury