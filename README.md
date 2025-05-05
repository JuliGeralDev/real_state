# 🏡 Real State Project – Responsive Real Estate Website

Real State Project is a *study project* developed as part of a Udemy course by Juan Pablo De la Torre Valdez. It is a modern and responsive website designed to showcase real estate properties, blog entries, and testimonials. Built with modern tools such as HTML5, SCSS, and Gulp, this project focuses on modular styling, layout structure, and automated workflows.

> ⚠️ Note: This is not a functional application, but a front-end prototype created to demonstrate design, layout, and asset management skills.

## 🔗 Live Preview

[👉 View the Demo on Netlify](https://realstate-juligeraldev.netlify.app/)
## ✨ Features

- Responsive Design for all screen sizes using media queries and flexible layouts  
- Modular SCSS Architecture with reusable styles and variables  
- Image Optimization using Gulp plugins with WebP and AVIF support  
- Featured Property Listings with images, descriptions, and pricing  
- Blog Section with recent posts  
- Testimonials from clients  
- Custom UI components including header, footer, and navigation  

## 📁 Project Structure

real_state_project/  
├── build/              # Compiled CSS and optimized images  
├── src/                # Source files  
│   ├── scss/  
│   │   ├── base/       # Variables, mixins, global styles  
│   │   ├── ui/         # Component-specific styles  
│   ├── img/            # Source images  
├── index.html          # Home page  


## 🛠️ Technologies Used

- HTML5 – Semantic structure for web content  
- SCSS – Preprocessor for modular and maintainable styles  
- Gulp – Automates development tasks and optimizations  
- Google Fonts – Custom typography  
- Browserslist – Cross-browser compatibility configuration  

## ⚙️ Installation

To set up the project locally:

1. Clone the repository  
   `git clone <repository-url>`

2. Navigate to the project directory  
   `cd real_state_project`

3. Install dependencies  
   `npm install`

4. Start the development environment  
   `npm run dev`

This will:  
- ✅ Compile SCSS files into minified CSS  
- ✅ Optimize images and generate WebP/AVIF formats  
- ✅ Watch for changes in SCSS and image files and recompile automatically

## 🎨 SCSS Structure

### base/
- _variables.scss – Color palette, font families, spacing  
- _mixins.scss – Media queries and reusable logic  
- _globales.scss – Resets and basic element styles

### ui/
- Component styles for layout sections, header, footer, etc.

## 🔁 Gulp Tasks

- CSS Compilation – Compiles SCSS and applies autoprefixing  
- Image Optimization – Converts and compresses images  
- File Watcher – Detects changes and rebuilds assets in real time

## 👩‍💻 Author

Juliana García Corredor  
GitHub: [@JuliGeralDev](https://github.com/JuliGeralDev)

## 📝 Notes

- Make sure you have Node.js and npm installed.  
- The `/build` folder is generated automatically and is ignored by Git.
