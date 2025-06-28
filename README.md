# Roll Dice Game 🎲

A fully responsive, modern dice rolling game for two players built with HTML, CSS, and JavaScript.

## Features

### 🎮 Game Features

- **Two-player gameplay** with turn-based mechanics
- **Dice rolling** with visual dice display
- **Score tracking** with current and total scores
- **Hold functionality** to save current score
- **Win condition** at 50 points
- **New game** button to reset

### 📱 Responsive Design

- **Mobile-first approach** with progressive enhancement
- **Flexible layouts** that adapt to all screen sizes
- **Touch-friendly controls** with proper button sizing
- **Landscape orientation support** for mobile devices
- **High DPI display optimization**

### 🎯 Device Support

- **Mobile phones** (320px and up)
- **Tablets** (768px and up)
- **Desktop computers** (1024px and up)
- **Large displays** (1200px and up)

### ♿ Accessibility Features

- **Keyboard navigation** support
- **Reduced motion** preferences respected
- **High contrast** and readable typography
- **Screen reader** friendly markup
- **Focus indicators** for navigation

### 🌙 Modern Features

- **Dark mode** support (system preference)
- **Smooth animations** and transitions
- **Backdrop blur** effects
- **Modern CSS** with flexbox and grid
- **Progressive Web App** ready

## How to Play

### Controls

- **🎲 ROLL DICE**: Roll the dice and add to current score
- **📥 HOLD**: Save current score and switch players
- **🔄 NEW GAME**: Reset the game

### Keyboard Shortcuts

- **Space/Enter**: Roll dice
- **H**: Hold current score
- **N**: New game

### Touch Controls (Mobile)

- **Swipe down**: Roll dice
- **Swipe up**: Hold current score
- **Tap buttons**: Standard button interaction

### Game Rules

1. Players take turns rolling the dice
2. Rolling a 1 loses current score and switches turns
3. Rolling 2-6 adds to current score
4. Use HOLD to save current score to total
5. First player to reach 50 points wins!

## Technical Details

### Responsive Breakpoints

- **Mobile**: 320px - 767px (stacked layout)
- **Tablet**: 768px - 1023px (side-by-side layout)
- **Desktop**: 1024px+ (full layout with absolute positioning)

### CSS Features

- **CSS Grid & Flexbox** for layouts
- **CSS Custom Properties** for theming
- **Media queries** for responsive design
- **Clamp()** for fluid typography
- **Backdrop-filter** for modern effects

### JavaScript Features

- **ES6+** syntax
- **Event delegation** for performance
- **Touch event handling** for mobile
- **Keyboard event handling** for accessibility
- **Responsive resize handling**

## Browser Support

- **Chrome** 88+
- **Firefox** 85+
- **Safari** 14+
- **Edge** 88+
- **Mobile browsers** (iOS Safari, Chrome Mobile)

## Installation

1. Clone or download the project
2. Open `index.html` in a web browser
3. No build process required - pure HTML/CSS/JS

## File Structure

```
Roll Dice Game/
├── index.html          # Main HTML file
├── style.css           # Responsive CSS styles
├── script.js           # Game logic and interactions
├── dice-1.png          # Dice face images
├── dice-2.png
├── dice-3.png
├── dice-4.png
├── dice-5.png
├── dice-6.png
├── logo.jpg            # Favicon
└── README.md           # This file
```

## Performance

- **Lightweight**: No external dependencies
- **Fast loading**: Optimized images and minimal code
- **Smooth animations**: Hardware-accelerated CSS transitions
- **Efficient**: Minimal DOM manipulation

## Future Enhancements

- [ ] Sound effects
- [ ] Animations for dice rolling
- [ ] Local storage for high scores
- [ ] Multiplayer over network
- [ ] Custom dice themes
- [ ] Tournament mode

## License

This project is open source and available under the MIT License.

---

**Enjoy playing! 🎲**
