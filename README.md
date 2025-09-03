# 🌟 Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a **Rich Black & Vivid Yellow** color scheme with stunning neon effects.

## 🚀 Live Demo

[View Live Portfolio](https://akbar330.github.io/portofolio/)

## ✨ Features

- **Modern Neon Design** - Rich black background with vivid yellow accents and glowing effects
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile devices  
- **Smooth Animations** - CSS transitions and scroll-triggered animations
- **GitHub Integration** - Dynamically fetches and displays repositories using GitHub API
- **Interactive Elements** - Hover effects, animated skill bars, and smooth scrolling
- **Clean Code** - Well-structured HTML, CSS, and vanilla JavaScript

## 🎨 Design Highlights

- **Color Palette**: Rich Black (#0f0f0f) & Vivid Yellow (#fbbf24)
- **Typography**: Modern, clean fonts with neon text effects
- **Icons**: Feather Icons for consistent, lightweight iconography
- **Effects**: Glowing borders, pulsing dots, and shadow effects
- **Layout**: CSS Grid and Flexbox for responsive design

## 📱 Sections

- **Hero** - Eye-catching introduction with animated elements
- **About** - Personal introduction and professional background  
- **Skills** - Interactive skill bars with proficiency levels
- **Projects** - Dynamically loaded from GitHub repositories
- **Contact** - Easy ways to get in touch

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with animations and effects
- **JavaScript (ES6+)** - Interactive functionality and API integration
- **GitHub API** - Dynamic project loading
- **Feather Icons** - Lightweight icon library

## 📦 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Akbar330/portofolio.git
   cd portofolio
   ```

2. **Configure GitHub Integration**
   
   Open the HTML file and update the GitHub configuration:
   ```javascript
   const GITHUB_USERNAME = 'YOUR_USERNAME'; 
   const FEATURED_REPOS = [
       'repo-name-1',
       'repo-name-2', 
       'repo-name-3'
   ];
   ```

3. **Open in Browser**
   ```bash
   # Simply open the HTML file in your browser
   open index.html
   # or double-click the file
   ```

4. **Deploy to GitHub Pages** (Optional)
   - Go to repository Settings
   - Navigate to Pages section
   - Select source branch (usually `main` or `master`)
   - Your site will be available at `https://yourusername.github.io/portofolio/`

## ⚙️ Customization

### Personal Information
Update the following sections in the HTML file:
- Name and title in hero section
- About me description
- Contact information
- Social media links

### Skills & Expertise
Modify skill levels in the JavaScript section:
```javascript
// Update skill percentages and names
<div class="skill-fill" data-width="75"></div> // Change percentage
```

### Colors & Styling
Customize the color scheme in CSS:
```css
/* Main colors */
:root {
  --primary-yellow: #fbbf24;
  --primary-black: #0f0f0f;
  --secondary-gray: #1f2937;
}
```

## 📊 GitHub Integration

The portfolio automatically fetches your latest repositories from GitHub API:

- **Featured Repos** - Displays specific repositories you want to highlight
- **Fallback** - Shows latest public repositories if featured ones aren't found
- **Repository Info** - Stars, forks, language, and last updated date
- **Live Links** - Direct links to repository and live demos

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Akbar330/portofolio/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Akbar**
- GitHub: [@Akbar330](https://github.com/Akbar330)
- Portfolio: [Live Demo](https://akbar330.github.io/portofolio/)

## 🙏 Acknowledgments

- [Feather Icons](https://feathericons.com/) for the beautiful icon set
- [GitHub API](https://docs.github.com/en/rest) for repository integration
- Inspiration from modern web design trends and neon aesthetics

---

⭐ **If you found this project helpful, please give it a star!** ⭐
