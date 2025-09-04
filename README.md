# 🕉️ Radha-Krishna Virtual Greeting Card Generator

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://basantkr762.github.io/radha-greeting/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

A beautiful, interactive web application that allows users to create and share personalized Radha-Krishna themed greeting cards. This project celebrates the divine love between Radha and Krishna through an intuitive card generator with stunning visuals and modern web technologies.

![Application Screenshot](https://github.com/user-attachments/assets/4ad3be74-195c-4a8b-8705-04b97543dcb8)

## ✨ Features

### 🎨 Card Customization
- **Multiple Background Designs**: Choose from 3 beautiful Radha-Krishna themed backgrounds
- **Custom Text Messages**: Add personalized messages with real-time preview
- **Font Selection**: Multiple font options including decorative and modern styles
- **Text Styling**: 
  - Color picker for custom text colors
  - Text effects: Shadow, Glow, Outline, or None
  - Automatic text wrapping for optimal layout

### 🎯 Interactive Elements
- **Drag & Drop Stickers**: Add emojis and symbols (❤️, 🪷, 🪔, 🕉️, 🎵, 🦚, ⭐, 🌸)
- **Live Preview**: Real-time canvas rendering with 3D tilt effects
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

### 💾 Export & Share
- **High-Quality Downloads**: Export cards as PNG images
- **Native Sharing**: Share directly using Web Share API (on supported devices)
- **Cross-Platform Compatibility**: Works on all modern browsers

### 🌟 Visual Experience
- **Animated Backgrounds**: Beautiful gradient animations and floating elements
- **3D Parallax Effects**: Interactive tilt animations using VanillaTilt.js
- **Smooth Transitions**: CSS animations and hover effects throughout
- **Spiritual Aesthetics**: Carefully designed color schemes and imagery

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/basantkr762/radha-greeting.git
   cd radha-greeting
   ```

2. **Start a local server**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000` in your web browser

### Alternative: Direct File Access
You can also open `index.html` directly in your browser, though some features may require a web server for optimal functionality.

## 🛠️ Technology Stack

### Frontend Technologies
- **HTML5**: Semantic markup with modern web standards
- **CSS3**: Advanced styling with animations and responsive design
- **JavaScript (ES6+)**: Modern JavaScript features and APIs
- **Canvas API**: High-quality card rendering and image generation

### Frameworks & Libraries
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework (via CDN)
- **[VanillaTilt.js](https://micku7zu.github.io/vanilla-tilt.js/)**: Lightweight 3D tilt effect library
- **[Google Fonts](https://fonts.google.com/)**: Great Vibes and Poppins font families

### Web APIs Used
- **Canvas API**: For card composition and image generation
- **File API**: For image download functionality
- **Web Share API**: For native sharing capabilities
- **Drag and Drop API**: For interactive sticker placement
- **Fetch API**: For resource loading and management

## 📁 Project Structure

```
radha-greeting/
├── index.html              # Main application file (SPA)
├── vanilla-tilt.js          # 3D tilt effect library
├── design-one.png          # Background option 1
├── design-two.png          # Background option 2  
├── design-three.png        # Background option 3
├── vrindavan.jpg           # Hero section background
└── README.md               # Project documentation
```

## 🎯 Usage Guide

### Creating Your First Greeting Card

1. **Choose a Background**
   - Click on one of the three available Radha-Krishna themed backgrounds
   - The selected background will appear in the live preview

2. **Add Your Message**
   - Enter your custom message in the text input field
   - Select from available fonts: Poppins, Great Vibes, Georgia, or Verdana
   - Choose your preferred text color using the color picker
   - Apply effects like shadow, glow, or outline for enhanced styling

3. **Add Decorative Elements**
   - Drag and drop stickers from the available options
   - Position them anywhere on the card canvas
   - Mix and match different symbols for creative designs

4. **Preview and Export**
   - View your creation in real-time with 3D tilt effects
   - Click "Download as PNG" to save your card
   - Use "Share Card" to share directly on supported platforms

### Tips for Best Results
- Keep messages concise for better readability
- Use contrasting colors for text visibility
- Experiment with different font combinations
- Place stickers strategically to complement the background

## 🌐 Browser Compatibility

| Browser | Version | Supported Features |
|---------|---------|-------------------|
| Chrome | 80+ | ✅ All features including Web Share API |
| Firefox | 75+ | ✅ All features (limited sharing) |
| Safari | 13+ | ✅ All features including Web Share API |
| Edge | 80+ | ✅ All features including Web Share API |

### Required Features
- Canvas API support
- ES6+ JavaScript features
- CSS Grid and Flexbox
- Modern event handling

## 🎨 Customization

### Adding New Backgrounds
1. Add your image file to the project directory
2. Update the `backgrounds` array in the JavaScript section:
```javascript
const backgrounds = [
    { id: 'bg1', src: 'design-one.png', name: 'Radha Krishna' },
    { id: 'bg2', src: 'design-two.png', name: 'Radha Krishna' },
    { id: 'bg3', src: 'design-three.png', name: 'Radha Krishna' },
    { id: 'bg4', src: 'your-new-background.png', name: 'Custom Design' }
];
```

### Adding New Stickers
Update the `stickers` array with new emoji options:
```javascript
const stickers = [
    { id: 'heart', emoji: '❤️', name: 'Heart' },
    { id: 'newSticker', emoji: '🌟', name: 'New Sticker' }
];
```

### Styling Modifications
- Modify CSS custom properties for color schemes
- Adjust animation timings and effects
- Customize responsive breakpoints
- Update font selections

## 🤝 Contributing

We welcome contributions to improve the Radha-Krishna Greeting Card Generator! Here's how you can help:

### Ways to Contribute
- 🐛 **Bug Reports**: Report issues or unexpected behavior
- 💡 **Feature Requests**: Suggest new features or improvements
- 🎨 **Design Improvements**: Enhance UI/UX or add new visual elements
- 📝 **Documentation**: Improve README or add code comments
- 🌍 **Localization**: Add support for multiple languages

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes and test thoroughly
4. Commit your changes: `git commit -m 'Add amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Code Style Guidelines
- Use modern JavaScript (ES6+) features
- Follow semantic HTML5 markup
- Maintain responsive design principles
- Add comments for complex functionality
- Test across multiple browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE). Feel free to use, modify, and distribute this code for personal and commercial projects.

## 🙏 Acknowledgments

- **Spiritual Inspiration**: The eternal love story of Radha and Krishna
- **Visual Design**: Traditional Indian art and modern web aesthetics
- **Community**: All contributors and users who help improve this project
- **Libraries**: VanillaTilt.js for 3D effects, Tailwind CSS for styling

## 📞 Contact & Support

- **Developer**: Basant Kumar
- **GitHub**: [@basantkr762](https://github.com/basantkr762)
- **Issues**: [Report bugs or request features](https://github.com/basantkr762/radha-greeting/issues)

## 🌟 Show Your Support

If you found this project helpful or inspiring, please consider:
- ⭐ Starring this repository
- 🍴 Forking for your own modifications
- 📢 Sharing with friends and family
- 💝 Creating beautiful greeting cards to spread joy

---

<div align="center">

**Made with ❤️ and devotion to Radha-Krishna** 

*"In every little greeting shared, may divine love be declared"* 🙏

</div>