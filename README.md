# Umair Gujjar's Portfolio Website

![GitHub Pages Deployment](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Professional portfolio website hosted on GitHub Pages, featuring responsive design, GitHub API integration, and contact form functionality.

👉 **Live Demo:** [https://umairgujjar.github.io](https://umairgujjar.github.io)

![Portfolio Screenshot](https://via.placeholder.com/800x450/0d1117/ffffff?text=Umair+Gujjar+Portfolio+Screenshot)

## Features

- 🌓 Modern GitHub-inspired dark theme
- 📱 Fully responsive design
- ⚡ Dynamic project loading from GitHub API
- 📬 Functional contact form with Web3Forms integration
- 🌐 Social media integration
- 💻 Programming language detection with icons
- 🚀 Optimized for GitHub Pages deployment

## Customization Guide

To use this template for your own portfolio:

1. **Replace Personal Information**
   - Update the name in the `<h1>` tag
   - Modify the bio text in the "About Me" section
   - Update social media links with your profiles

2. **Update Avatar**
   - Change the background URL in the `.avatar` CSS class to your GitHub profile image:
     ```css
     background: url('https://github.com/your-username.png') center/cover;
     ```

3. **Customize Contact Information**
   - Update email address and LinkedIn URL in the contact section
   - Replace the Web3Forms API key with your own:
     ```html
     <input type="hidden" name="access_key" value="your-api-key">
     ```

4. **Modify Colors (Optional)**
   - Update CSS variables in the `:root` selector to change the color scheme:
     ```css
     :root {
       --primary: #0d1117;
       --secondary: #161b22;
       --accent: #58a6ff;
       /* ... */
     }
     ```

## Deployment

1. Create a new repository named `yourusername.github.io`
2. Add the `index.html` file to the repository
3. Enable GitHub Pages in repository settings:
   - Go to Settings > Pages
   - Set source to "Deploy from a branch"
   - Select branch: main (or master)
   - Select folder: / (root)
4. Your site will be live at: `https://yourusername.github.io`

## Contact Form Setup

The contact form uses [Web3Forms](https://web3forms.com/) for form submission:

1. Sign up for a free account at [web3forms.com](https://web3forms.com/)
2. Create a new form to get your API key
3. Replace the API key in the form code:
   ```html
   <input type="hidden" name="access_key" value="your-api-key">
