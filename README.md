# 💌 LoveNote

> Because some questions deserve a special delivery

A beautifully interactive, romantic web application for asking someone out in a memorable way. With playful questions, smooth animations, and a dash of humor, LoveNote makes your big ask unforgettable.

## ✨ Features

- **Multiple Charming Lines**: 25+ different funny and heartfelt ways to ask someone out
- **Interactive Animations**: Smooth fade transitions and confetti celebrations
- **The "Elusive No Button"**: A playful "No" button that dodges away from clicks (because there's only one right answer 😉)
- **Responsive Design**: Looks beautiful on mobile, tablet, and desktop
- **Gradient Aesthetic**: Soft, romantic color palette with custom fonts
- **Canvas Hearts Animation**: Subtle animated hearts floating in the background
- **Confetti Celebration**: Festive confetti animation when they say yes!

## 🎨 Design Highlights

- Custom styling with a romantic pink and purple gradient theme
- Smooth transitions and interactive hover effects
- Mobile-optimized layout with proper touch handling
- Glassmorphism effects for a modern, elegant look
- Pacifico font for that handwritten, personal touch

## 🚀 Getting Started

### Option 1: Direct Access
Simply visit the live site and open `index.html` in your browser.

### Option 2: Local Setup
1. Clone the repository:
```bash
git clone https://github.com/mathisbraud2006-jpg/LoveNote.git
cd LoveNote
```

2. Open `index.html` in your web browser

That's it! No build process or dependencies needed. It's pure HTML, CSS, and vanilla JavaScript.

## 📋 How It Works

1. **Start**: The app displays a cute question with emoji flair
2. **Read**: Each question has a funny, heartfelt, or punny angle to it
3. **Choose**:
   - Click **"Yes! 💕"** to celebrate your victory with confetti
   - Click **"No 😐"** to watch it escape (we know you won't!)
4. **Reroll**: Use the "✨ try another line" button to cycle through different messages
5. **Celebrate**: When they say yes, confetti rains down and a special victory message appears

## 📱 Questions Included

The app comes pre-loaded with 25 creative pickup lines, including:
- Data-driven arguments ("Statistically, this will be a great date")
- Pet endorsements ("My dog already thinks you're amazing")
- Honest admissions ("I've been practicing this ask for 3 days")
- Cosmic connections ("The stars literally aligned for this moment")
- Bribery tactics ("I'll buy the boba. Both of them. No hesitation")
- And many more!

## 🎯 Perfect For

- 💑 Asking someone out
- 💍 Proposal prep (customize the questions!)
- 😄 Impressing with humor and creativity
- 📱 Sharing with that special someone
- 🎭 Creative confession of feelings

## 🛠️ Customization

Want to personalize it? Edit the `lines` array in the JavaScript section of `index.html`:

```javascript
const lines = [
  { 
    emoji:"🌹💌🥂", 
    q:"Will you go on a date with me?", 
    sub:"Think carefully… there's only one right answer 💖",
    winEmoji:"🥳🎉💖", 
    winText:"Yay!! It's a date!!", 
    winSub:"I knew you'd say yes~ See you soon! 🌹"
  },
  // Add more questions here!
];
```

Each question object includes:
- `emoji`: Decorative emoji row
- `q`: The main question
- `sub`: Subtitle/subtext
- `winEmoji`: Emoji shown on victory screen
- `winText`: Victory message text
- `winSub`: Additional victory message

### Changing the Signature
Update line 197 to personalize who's asking:
```html
<p class="signature">— Your Name 🖊️</p>
```

## 🎨 Color Customization

The gradient background uses a soft pink-to-purple palette. To change colors, edit the CSS gradient:
```css
background: linear-gradient(160deg, #ffe0f0 0%, #ffd6e8 40%, #e8d0ff 100%);
```

## 📊 Technical Details

- **Language**: HTML, CSS, JavaScript (Vanilla - no frameworks!)
- **Size**: Lightweight and fast
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **External Dependencies**: Only Google Fonts (Pacifico)
- **Accessibility**: Keyboard and touch-friendly

## 🎬 Features in Action

### Say Yes Animation
- Victory emoji display
- Celebratory message
- Confetti particle effects
- Card fade-out transition

### Dodge "No" Button
- Button position randomizes on hover/touch
- Stays within the scene boundaries
- Humorous, interactive experience

### Background Animation
- 18 floating hearts
- Subtle wobble and drift effects
- Rotating heart shapes
- Opacity variations for depth

## 🔧 No Build Required!

This is a pure HTML/CSS/JavaScript project with no build step. Just download, customize, and share!

## 📄 License

Feel free to use, modify, and share for personal projects. This is a labor of love! 💕

## 💌 About

Created by **Mathis B.** as a creative way to ask someone special out. Feel free to personalize it and use it for your own important moments!

---

**Remember**: The best questions are the ones that lead to yes! 🌹✨

Made with 💖 and JavaScript
