# 🖼️ Image Gallery

A modern, responsive image gallery with filtering capabilities and smooth lightbox navigation. Built with HTML, CSS, and JavaScript.
![Image Gallery](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

### 🎯 Core Features
- **📱 Responsive Design** - Works perfectly on all devices
- **🎨 Category Filtering** - Filter images by Nature, City, and Abstract
- **🔍 Lightbox View** - Full-screen image viewing experience
- **🔄 Smooth Navigation** - Next/previous buttons with keyboard support
- **✨ Hover Effects** - Beautiful animations and transitions

### 🚀 Advanced Features
- **⌨️ Keyboard Navigation** - Use arrow keys and Escape for navigation
- **📐 CSS Grid Layout** - Modern, flexible gallery arrangement
- **🎭 Smooth Transitions** - CSS animations for all interactions
- **📲 Mobile Optimized** - Touch-friendly interface for mobile devices

## 🛠 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Grid, Flexbox, transitions, and animations
- **JavaScript** - DOM manipulation and event handling
- **Responsive Design** - Mobile-first approach


## 🎮 How to Use

### Basic Navigation
1. **Browse Images**: Scroll through the gallery grid
2. **Filter Categories**: Click category buttons (All, Nature, City, Abstract)
3. **View Full Image**: Click any thumbnail to open lightbox
4. **Navigate Lightbox**: Use arrow buttons or keyboard arrows
5. **Close Lightbox**: Click × or press Escape

### Keyboard Shortcuts
- **← → Arrow Keys**: Navigate between images in lightbox
- **Escape**: Close lightbox
- **Click**: Open/close images and select filters

## 🎨 Customization

### Adding New Images
1. Add images to the `images/` folder
2. Update HTML with new image elements:
```html
<img src="images/your-image.jpg" data-category="category" onclick="openfullImg(this.src, this.dataset.index)" alt="Description">
