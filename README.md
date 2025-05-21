# 🪐 Cosmic 404 - Space Themed Error Page

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<div align="center">
  <img src="preview.gif" alt="Cosmic 404 Preview" width="700px">
  <p><i>✨ An immersive 404 error page featuring a mesmerizing 3D planet with orbiting moon, cosmic dust particles, and twinkling stars - all created with pure CSS and minimal JavaScript! 🌌 Transform error messages into an interstellar experience that captivates visitors while guiding them back to safety. 🚀</i></p>
</div>

## ✨ Features

- **Mesmerizing 3D Planet** - Rotating planet with realistic surface details
- **Dynamic Ring System** - Orbital rings that rotate independently 
- **Animated Moon** - Moon that orbits around the planet
- **Interactive Parallax** - Mouse-controlled parallax effect for immersive depth
- **Shooting Stars** - Animated shooting stars across the cosmic background
- **Cosmic Dust** - Floating dust particles that enhance the space atmosphere
- **Responsive Design** - Adapts beautifully to all screen sizes and devices
- **Pure CSS Animation** - Almost all animations created with CSS keyframes
- **Minimal JavaScript** - Only used for dust particle generation and parallax effect

## 📋 Project Structure

```
Cosmic-404/
├── index.html     # HTML structure with embedded CSS and JS
├── preview.gif    # Preview animation of the 404 page
└── README.md      # Project documentation
```

## 🔍 How it Works

This project leverages advanced CSS and minimal JavaScript techniques including:

- **3D Transforms** - Using perspective, preserve-3d, and rotate3d properties
- **CSS Keyframe Animations** - Multiple animation sequences for planet rotation, moon orbit, etc.
- **Custom Properties** - CSS variables for dynamic dust particle movements
- **Parallax Effects** - JavaScript-powered mouse movement tracking
- **Responsive Design** - Media queries for different screen sizes
- **Dynamic Element Creation** - JavaScript for generating dust particles

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sadat-Rakib/Cosmic-404.git
   cd Cosmic-404
   ```

2. Open `index.html` in your browser:
   ```bash
   # Using Python's built-in server
   python -m http.server
   # Or simply open the file in your browser
   ```

## 🎮 Customization

Easily customize the 404 page to match your website's design:

### Colors
To change the planet colors, modify these CSS variables:
```css
.planet .inner {
    background: linear-gradient(90deg, #9a5528 50%, #d88556 50%);
    /* Change to your desired colors */
}

.ring {
    background: radial-gradient(transparent 50%, #d4df65 50.1%, #d4df65 58%, #e2ed77 58.1%, transparent 70%);
    /* Change to your desired ring colors */
}
```

### Text
Customize the error message by modifying:
```html
<p class="info">PLANET NOT FOUND</p>
<button class="back-button">RETURN TO ORBIT</button>
```

### Animation Speeds
Adjust animation durations for a different feel:
```css
@keyframes sceneRotate {
    /* Change 100s to speed up or slow down the rotation */
    animation: sceneRotate 100s infinite linear;
}
```

## 📱 Responsive Behavior

The page automatically adapts to different screen sizes:

- **Desktop:** Full interactive experience with parallax effects
- **Tablet:** Optimized planet size and animations
- **Mobile:** Simplified layout with preserved animations

## 📊 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Safari  | ✅ Full |
| Edge    | ✅ Full |
| Opera   | ✅ Full |
| IE      | ❌ Not supported |

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by modern space exploration visuals
- CSS 3D transform techniques
- The growing community of creative web developers
---

<div align="center">
  <p>⭐ Star this repository if you found it interesting! ⭐</p>
  <p>Made with ❤️ and CSS magic</p>
</div>
