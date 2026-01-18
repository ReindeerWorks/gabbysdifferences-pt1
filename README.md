# 🐱 Gabby Cat - Find the Differences!

An interactive "Spot the Difference" game featuring Gabby and her adorable cat friends!

## 🎮 Play the Game

[Live Demo](#) *(Add your GitHub Pages link here)*

## ✨ Features

- **3 Hidden Differences** - Can you find them all with Gabby?
- **Kid-Friendly Design** - Bright colors and fun animations
- **Interactive Gameplay** - Click on either image to mark differences
- **Visual Feedback** - Green circles for correct finds, red X for misses
- **Performance Tracking** - Timer, click counter, and accuracy stats
- **Hint System** - Get up to 3 hints when you need help
- **Responsive Design** - Perfect on phones, tablets, and computers
- **Victory Celebration** - Fun "Purrfect!" message when you win

## 🎯 The 3 Differences

1. **Yellow Fish/Butterfly** - A bright yellow creature appears in the upper left corner
2. **Cat Headband Ear** - The left ear on Gabby's headband changes from pink to white
3. **White Cat's Nose** - The white cat's nose gets more detailed with nostrils

## 🚀 Getting Started

### Quick Start

1. Clone this repository:
```bash
git clone https://github.com/yourusername/gabby-cat-differences.git
```

2. Open `index.html` in your web browser

That's it! No installation or setup needed!

### GitHub Pages Deployment

1. Go to your repository Settings
2. Navigate to "Pages" section
3. Select your main branch as the source
4. Your game will be live at `https://yourusername.github.io/gabby-cat-differences`

## 📁 Project Structure

```
gabby-cat-differences/
├── index.html          # Complete game (HTML, CSS, JS in one file)
├── image1.png          # Original Gabby Cat scene
├── image2.png          # Scene with 3 differences
└── README.md           # This file
```

## 🎨 Customization

### Adjusting Difference Locations

The difference locations are defined in the JavaScript section:

```javascript
const differences = [
    { x: 8, y: 18, radius: 6, name: "Yellow Fish" },
    { x: 35, y: 8, radius: 5, name: "Headband Ear" },
    { x: 38, y: 68, radius: 4, name: "Cat Nose" }
];
```

- `x` and `y` are percentages (0-100) of the image dimensions
- `radius` defines the clickable area size (in percentage)
- `name` is for your reference only

### Changing the Color Theme

Main colors are defined in the CSS:
- Primary blue gradient: `#4facfe` to `#00f2fe`
- Success green: `#00d9a5`
- Error red: `#ff4757`
- Hint yellow: `#feca57`

### Difficulty Adjustment

To make the game easier or harder:
- **Easier**: Increase the `radius` values (bigger clickable areas)
- **Harder**: Decrease the `radius` values (smaller clickable areas)
- Add more differences by adding objects to the `differences` array

## 🎓 How to Play

1. Look at both pictures of Gabby and her cat friends
2. Click on any differences you spot (click on either picture!)
3. Green circles appear when you find a difference ✅
4. Red X marks show incorrect clicks ❌
5. Use the 💡 Hint button if you get stuck (3 available)
6. Find all 3 differences to win!

## 🛠️ Technical Details

- **Pure Vanilla JavaScript** - No frameworks or libraries needed
- **Single HTML File** - Everything bundled for easy deployment
- **Responsive CSS Grid** - Side-by-side on desktop, stacked on mobile
- **Percentage-Based Positioning** - Works at any screen size
- **CSS Animations** - Smooth, playful visual effects
- **Mobile-Optimized** - Touch-friendly interface

## 📱 Browser Support

Works great on:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS & Android)

## 🎨 Design Features

- Bright, cheerful color scheme perfect for kids
- Cat-themed emojis and animations
- "Purrfect!" victory message
- Bouncing title animation
- Smooth hover effects on buttons
- Responsive layout that works on any device

## 🔧 Adding More Levels

Want to create multiple levels? Here's how:

1. Create `scene2.html`, `scene3.html`, etc.
2. Use different images for each level
3. Update the `differences` array for each scene
4. Add navigation buttons to move between levels

## 📝 License

Perfect for educational use, birthday parties, or just for fun!

## 🙏 Credits

Featuring Gabby and her adorable cat friends!

---

**Made with 🐱 and ❤️ for all Gabby Cat fans!**
