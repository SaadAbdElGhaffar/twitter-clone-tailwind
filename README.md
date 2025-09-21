# Twitter Clone - Tailwind CSS

A responsive Twitter clone built with HTML and Tailwind CSS, featuring a modern dark/light theme toggle and authentic Twitter-like interface design.

## 🚀 Live Demo

[**View Live Demo**](https://saadabdelghaffar.github.io/twitter-clone-tailwind/)

## 📸 Preview

The application features a clean, responsive design that closely mimics Twitter's interface with:
- **Dark/Light Mode Toggle** - Seamless theme switching
- **Responsive Design** - Mobile-first approach with desktop enhancements
- **Interactive Elements** - Hover effects and smooth transitions
- **Authentic UI** - Twitter-like sidebar, main feed, and right panel

## ✨ Features

### 🎨 Design Features
- **Responsive Layout** - Optimized for mobile, tablet, and desktop
- **Dark/Light Theme** - Toggle between themes with smooth transitions
- **Custom Color Palette** - Custom "dim" color scheme matching Twitter's aesthetic
- **Font Awesome Icons** - Complete icon set for navigation and interactions

### 🧩 UI Components
- **Sidebar Navigation** - Home, Explore, Notifications, Messages, Bookmarks, Lists, Profile, More
- **Tweet Composer** - Text area with media attachment options
- **Main Feed** - Tweet display with engagement metrics
- **Right Panel** - Search bar, trending topics, and suggested follows
- **User Profile** - Profile display with avatar and user information

### 📱 Interactive Elements
- **Hover Effects** - Color changes on navigation items and buttons
- **Smooth Animations** - CSS transitions and loading spinners
- **Responsive Icons** - Hide/show elements based on screen size
- **Custom Scrollbars** - Styled scrollbars for both light and dark themes

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **JavaScript** - Dark mode toggle functionality

## 📁 Project Structure

```
twitter-clone-tailwind/
├── index.html              # Main HTML file
├── style.css              # Custom CSS with Tailwind directives
├── dist.css               # Compiled Tailwind CSS
├── tailwind.config.js     # Tailwind configuration
├── package.json           # Node.js dependencies and scripts
├── images/                # Image assets
│   ├── hCCopfyz_400x400.jpg    # Profile avatar
│   └── d41586-019-00653-5_16459150.jpg  # Tweet image
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js installed on your machine
- Basic knowledge of HTML, CSS, and Tailwind CSS

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SaadAbdElGhaffar/twitter-clone-tailwind.git
   cd twitter-clone-tailwind
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run watch
   ```
   This command watches for changes in `style.css` and automatically compiles to `dist.css`

4. **Open in browser**
   Open `index.html` in your preferred browser or use a live server extension

## ⚙️ Configuration

### Tailwind CSS Configuration
The project uses a custom Tailwind configuration with:

```javascript
// tailwind.config.js
module.exports = {
  content: ['./*.html'],
  darkMode: 'class',
  theme: {
    extend: {
      colors: {
        dim: {
          50: "#5F99F7",   // Twitter blue variants
          100: "#5F99F7",
          200: "#38444d",
          300: "#202e3a",
          400: "#253341",
          500: "#5F99F7",
          600: "#5F99F7",
          700: "#192734",
          800: "#162d40",
          900: "#15202b",  // Dark background
        },
      },
    },
  },
}
```

### Custom CSS Components
- `.active` - Active navigation state styling
- `.icon` - Navigation icon styling with hover effects
- `.word` - Responsive text visibility
- Custom scrollbar styling for both themes

## 🎨 Theme System

The application supports both light and dark themes:

- **Light Theme** - Clean white background with subtle gray accents
- **Dark Theme** - Twitter's characteristic dark blue color scheme
- **Toggle Button** - JavaScript-powered theme switcher
- **Persistent State** - Theme preference maintained during session

## 📱 Responsive Design

The layout adapts across different screen sizes:

- **Mobile (< 1280px)** - Condensed sidebar with icons only
- **Desktop (≥ 1280px)** - Full sidebar with text labels and right panel
- **Flexible Grid** - CSS Grid and Flexbox for optimal layouts

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Saad Abd El Ghaffar**
- GitHub: [@SaadAbdElGhaffar](https://github.com/SaadAbdElGhaffar)
- Email: saadabdelghaffar639@gmail.com

## 🙏 Acknowledgments

- Design inspired by Twitter's official interface
- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons provided by [Font Awesome](https://fontawesome.com/)

---

⭐ Star this repository if you found it helpful!
