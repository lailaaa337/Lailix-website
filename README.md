# 🎬 Lailix Website

A Netflix-inspired streaming website project built with HTML and CSS. This is a comprehensive college project showcasing modern web design principles with responsive layouts, interactive navigation, and professional styling. The project demonstrates front-end development fundamentals and UI/UX design inspired by leading streaming platforms.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Assets Required](#assets-required)
- [Technologies Used](#technologies-used)
- [File Descriptions](#file-descriptions)
- [Customization Guide](#customization-guide)
- [Browser Compatibility](#browser-compatibility)
- [Project Details](#project-details)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 📺 Overview

Lailix is a modern streaming platform web interface that replicates the core design patterns of Netflix. This project serves as an educational demonstration of HTML5 semantic structure combined with CSS3 styling techniques. It includes a professional header navigation system, a featured video hero section with auto-playing background media, and multiple content gallery sections for displaying shows and movies.

The website features:
- Professional grade navigation bar with multiple menu items
- Interactive user account icons (Search, Notifications, Profile)
- Auto-playing video hero section with overlay text
- Multiple grid-based image galleries for content display
- Clean, modern aesthetic inspired by contemporary streaming services

## ✨ Features

### 📺 Navigation Menu
- **Dynamic Header Navigation** - Professional top navigation bar with LAILIX branding
- **Menu Categories** - Browse TV Shows, Movies, New & Popular content, My List, and Browse by Language options
- **User Controls** - Quick access icons for Search, Notifications, and Profile management
- **Responsive Design** - Navigation adapts to different screen sizes

### 🎬 Featured Video Section
- **Auto-Playing Background Video** - Engaging hero section with continuous video background
- **Muted Video Loop** - Professional video experience without audio distraction
- **Overlay Text & CTA** - Feature title, subtitle, and "Watch Now" call-to-action button
- **Interstellar Featured Content** - Movie showcase with genre information

### 🖼️ Image Gallery Sections
- **Crowd Pleasers Gallery** - First collection of popular content cards
- **Additional Galleries** - Multiple sections for organizing content by category
- **Professional Image Grid** - Properly organized content displays with consistent spacing
- **Hover Effects Ready** - Structure supports interactive hover states

### 🔍 User Interface Elements
- **Search Functionality** - Dedicated search icon for content discovery
- **Notification Center** - Profile alerts and updates icon
- **User Profile** - Account management and customization access
- **Visual Hierarchy** - Clear organization of information and calls-to-action

### 📱 Responsive & Modern Design
- **HTML5 Semantic Structure** - Proper semantic markup for accessibility
- **CSS3 Styling** - Modern CSS techniques for professional appearance
- **Professional Color Scheme** - Dark theme with accent colors
- **Typography** - Clear, readable font hierarchy

## 📁 Project Structure

```
HTML/
│
├── project.html              # Main HTML file (119 lines)
│                             # Contains header, video section, galleries
│
├── style.css                 # Complete CSS styling
│                             # Layout, colors, typography, effects
│
├── pics/                     # Media assets directory
│   ├── background-video.mp4  # Hero section video content
│   ├── tall.jpeg             # Gallery image 1
│   ├── love.jpeg             # Gallery image 2
│   ├── noel.jpeg             # Gallery image 3
│   ├── dog.jpeg              # Gallery image 4
│   ├── adamjpeg.jpeg         # Gallery image 5
│   ├── beautiful.jpeg        # Gallery image 6
│   ├── search-icon.png       # Search functionality icon
│   ├── notifications-icon.png # Notifications indicator
│   └── profile-icon.png      # User profile icon
│
└── README.md                 # Project documentation (this file)
```

## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Git (optional, for cloning)
- Text editor for modifications (VS Code recommended)

### Steps

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/lailaaa337/Lailix-website.git
   cd HTML
   ```

2. **Organize Media Assets**
   - Create a `pics/` folder in the project directory
   - Place all video and image files as per the asset list

3. **Open in Browser**
   - Double-click `project.html` or
   - Right-click → Open with → Your preferred browser

4. **Verify All Assets**
   - Check that images and video load correctly
   - Ensure no broken links in console

## 💻 Usage

1. **Launch the Website**
   - Open `project.html` in a web browser
   - The page will load with the header navigation visible

2. **Explore Navigation**
   - Hover over menu items in the navigation bar
   - Click icons to test interactivity (ready for JavaScript additions)

3. **View Featured Content**
   - The video will auto-play in the hero section
   - Read the featured movie information and CTA

4. **Browse Content Galleries**
   - Scroll through different image gallery sections
   - View organized content collections

5. **Interactive Enhancements (Future)**
   - Hover states for improved UX
   - Click handlers for search and navigation
   - Dynamic content loading capability

## 📦 Assets Required

Place all files in the `pics/` folder for proper loading:

### Video Files
- **`background-video.mp4`** - Hero section background video (recommended: 1-2 minutes, HD quality, 16:9 aspect ratio)

### Gallery Images
- **`tall.jpeg`** - Portrait-oriented gallery image
- **`love.jpeg`** - Valentine/romance themed image
- **`noel.jpeg`** - Holiday themed image
- **`dog.jpeg`** - Pet/animal content image
- **`adamjpeg.jpeg`** - Person/character image
- **`beautiful.jpeg`** - Scenic/beautiful content image

### Navigation Icons
- **`search-icon.png`** - Search functionality icon (recommended: 30x30px minimum)
- **`notifications-icon.png`** - Notifications bell icon (recommended: 30x30px minimum)
- **`profile-icon.png`** - User profile/avatar icon (recommended: 30x30px minimum)

**Asset Format Guidelines:**
- Images: JPG/PNG format, optimized for web
- Video: MP4 format, H.264 codec for maximum compatibility
- Icons: PNG with transparency for flexibility

## 🛠️ Technologies Used

### HTML5
- **Semantic Elements** - `<header>`, `<nav>`, `<video>`, `<div>` for proper structure
- **Video Element** - Native HTML5 video player with autoplay, muted, and loop attributes
- **Accessibility** - Alt text for images and proper element hierarchy
- **Form Elements** - Button elements with semantic meaning

### CSS3
- **Flexbox** - Modern layout system for navigation and icons
- **Grid Systems** - Organized image gallery layouts
- **Media Queries** - Responsive design for multiple screen sizes
- **Transitions & Transforms** - Smooth animations and visual effects
- **Background Properties** - Video and image backgrounds with positioning
- **Typography** - Font families, sizing, and text styling
- **Color Schemes** - Dark theme styling with accent colors

### Design Patterns
- **Streaming Platform UI** - Netflix-inspired interface design
- **Hero Section Pattern** - Featured content with overlay
- **Gallery Grid** - Organized content display
- **Navigation Bar** - Fixed or sticky positioning

## 📄 File Descriptions

### project.html (119 lines)
The main HTML file containing:
- **Header Section** - Navigation bar with LAILIX branding and menu items
- **Video Hero Section** - Featured content with background video and overlay
- **Gallery Sections** - Multiple image collections organized by category
- **Icons** - User interaction elements (Search, Notifications, Profile)

### style.css
Complete styling file containing:
- **Global Styles** - Base styling for all elements
- **Header Styles** - Navigation bar appearance and layout
- **Video Section Styles** - Hero section and overlay styling
- **Gallery Styles** - Image grid and responsive layouts
- **Icon Styles** - User control element styling
- **Color Palette** - Consistent color scheme throughout
- **Typography** - Font styling and hierarchy
- **Effects** - Hover states and transitions

## 🎨 Customization Guide

### Change Colors
Open `style.css` and modify color values:
```css
/* Change header background */
header {
  background-color: #your-color-here;
}

/* Change text colors */
h1, h2 {
  color: #your-color-here;
}

/* Change button styles */
button {
  background-color: #your-color-here;
}
```

### Modify Typography
Adjust fonts and sizing:
```css
/* Change main heading */
h1 {
  font-family: 'Your Font';
  font-size: 48px;
}

/* Change body text */
body {
  font-family: 'Your Font';
  font-size: 16px;
}
```

### Update Content
Edit `project.html`:
- Change menu item text
- Update featured movie information
- Modify gallery titles and descriptions
- Adjust CTA button text

### Replace Images
- Add your own images to the `pics/` folder
- Update image paths in `project.html`
- Maintain consistent image dimensions for galleries

### Resize Elements
- Adjust `width` and `height` values in CSS
- Modify `padding` and `margin` for spacing
- Change grid layouts for different gallery arrangements

## 🌐 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | Latest | ✅ Full Support |
| Firefox | Latest | ✅ Full Support |
| Safari | Latest | ✅ Full Support |
| Edge | Latest | ✅ Full Support |
| Opera | Latest | ✅ Full Support |
| IE 11 | 11.x | ⚠️ Limited (Video support issues) |

## 📝 Project Details

### Educational Purpose
- Demonstrates HTML5 semantic structure
- Showcases CSS3 styling techniques
- Implements modern web design principles
- Suitable for web development courses

### Learning Outcomes
- Understanding of HTML5 elements
- CSS3 layout techniques (Flexbox, Grid)
- Video integration in web pages
- Responsive design fundamentals
- UI/UX design inspiration

### Development Status
- ✅ HTML Structure Complete
- ✅ CSS Styling Complete
- 🔄 Ready for JavaScript Enhancement
- 🔄 Mobile Responsiveness Improvements Possible
- 🔄 Accessibility Enhancements Coming

## 🤝 Contributing

Contributions are welcome! For college project purposes:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/your-feature`)
3. **Make** your improvements
4. **Commit** with clear messages
5. **Push** to your fork
6. **Submit** a Pull Request with description

### Contribution Ideas
- Add JavaScript interactivity
- Improve mobile responsiveness
- Add accessibility features
- Enhance animations and transitions
- Create additional content sections

## 📄 License

This project is created for educational purposes as part of a college project. Feel free to use it as a learning resource or starting point for your own projects.

## 👤 Author

**Layla**
- GitHub: [@lailaaa337](https://github.com/lailaaa337)
- Project: [Lailix-website](https://github.com/lailaaa337/Lailix-website)

---

### 🔗 Quick Links
- [GitHub Repository](https://github.com/lailaaa337/Lailix-website)
- [View Live](https://lailaaa337.github.io/Lailix-website/) (if deployed)
- [Report Issues](https://github.com/lailaaa337/Lailix-website/issues)

### 📌 Last Updated
February 2026

### 💡 Tips
- Use developer tools (F12) to inspect and modify elements
- Test the project on different devices for responsive behavior
- Experiment with CSS animations for enhanced interactivity
- Consider adding JavaScript for dynamic functionality

---

**Enjoy exploring the Lailix Website Project! 🎉**