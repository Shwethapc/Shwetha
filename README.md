# Shwetha Chikkalingaiah - Personal Portfolio

A modern, responsive personal portfolio website showcasing skills, education, projects, and professional experience.

## ✨ Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, animated sections, and hover effects
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized assets
- **Accessibility**: Semantic HTML and keyboard navigation support

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Google Fonts**: Inter font family for typography
- **Font Awesome**: Icons and visual elements

## 📋 Sections Included

1. **Hero Section**: Introduction with photo placeholder and call-to-action buttons
2. **About Me**: Personal information and brief description
3. **Education**: Timeline of academic achievements
4. **Skills & Expertise**: Programming languages, tools, and soft skills
5. **Certifications**: Professional certifications and courses
6. **Projects**: Featured project with detailed description
7. **Extra-curricular Activities**: Hobbies and interests
8. **Contact**: Contact information and message form

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for loading external fonts and icons)

### Installation

1. **Clone or Download**: Get the project files to your local machine
2. **Open**: Simply open `index.html` in your web browser
3. **Customize**: Edit the content to match your personal information

### Adding Your Photo

To add your personal photo:

1. **Save your photo** in the project directory (recommended: `photo.jpg` or `photo.png`)
2. **Update the HTML**: Replace the image placeholder in `index.html`:

```html
<!-- Replace this placeholder -->
<div class="image-placeholder">
    <i class="fas fa-user"></i>
    <p>Your Photo Here</p>
</div>

<!-- With your actual photo -->
<div class="hero-image">
    <img src="photo.jpg" alt="Shwetha Chikkalingaiah" class="profile-photo">
</div>
```

3. **Add CSS styling** for the photo in `styles.css`:

```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid rgba(255, 255, 255, 0.3);
    transition: all 0.3s ease;
}

.profile-photo:hover {
    transform: scale(1.05);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
}
```

## 🎨 Customization

### Personal Information
Edit the following sections in `index.html`:

- **Contact Details**: Update email, phone, and address
- **Education**: Modify schools, degrees, and grades
- **Skills**: Add/remove programming languages and tools
- **Projects**: Update project descriptions and technologies
- **About Me**: Personalize the description

### Colors and Styling
Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #667eea;
    --accent-color: #ff6b6b;
    --text-color: #333;
    --background-color: #f8fafc;
}
```

### Adding More Projects
To add additional projects, duplicate the project card structure:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <div class="project-meta">
            <span class="project-duration">Duration</span>
            <span class="project-team">Team Size</span>
        </div>
    </div>
    <div class="project-content">
        <!-- Project details -->
    </div>
</div>
```

## 📱 Mobile Responsiveness

The portfolio is fully responsive and includes:
- Mobile-first design approach
- Collapsible navigation menu
- Optimized layouts for all screen sizes
- Touch-friendly interactive elements

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── [your-photo]        # Your profile photo (add this)
```

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be live instantly with a custom URL

### Other Hosting
Upload all files to any web hosting service that supports static websites.

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Email format verification
- Success/error notifications
- Form reset after submission

**Note**: This is a frontend-only form. To make it fully functional, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Use a form service like Formspree or Netlify Forms
3. Configure email sending functionality

## 🎯 Performance Tips

- Images are optimized for web
- External resources are loaded efficiently
- CSS and JavaScript are minified for production
- Smooth animations without affecting performance

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them!

## 💡 Credits

- **Design**: Modern portfolio design principles
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Inspiration**: Contemporary web design trends

---

**Built with ❤️ for showcasing professional achievements and skills.**