# Kusal Pabasara - Personal Portfolio Website



A modern, responsive personal portfolio website for Kusal Pabasara, Computer Science & Engineering undergraduate at the University of Moratuwa, Sri Lanka.

## 🌟 Features

- **Responsive Design**: Fully responsive layout optimized for all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Animated section transitions, hover effects, and smooth scrolling
- **Contact Forms**: Integrated with Formspree for hassle-free form submissions
- **Floating Contact Widget**: Quick-access contact form that follows users as they scroll
- **Social Media Integration**: Direct links to all professional social profiles
- **SEO Friendly**: Properly structured HTML with appropriate meta tags

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Me**: Personal introduction and background information
3. **Skills**: Technical skills organized by category
4. **Experience**: Professional experience displayed in an interactive timeline
5. **Projects**: Showcase of notable projects with descriptions and technologies used
6. **Education**: Academic background and qualifications
7. **Contact**: Contact information and form for inquiries
8. **Footer**: Quick links and additional contact information

## 🛠️ Technologies Used

- **HTML5**: Modern semantic markup
- **CSS3**: Advanced styling with flexbox and grid layouts
- **JavaScript**: Interactive elements and animations
- **Font Awesome**: Scalable vector icons
- **Formspree**: Form backend, API & email service
- **Google Fonts**: Typography enhancement

## 🚀 Getting Started

### Prerequisites

- A web browser
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (for modifications)

### Installation

1. Clone the repository or download the ZIP file
   ```bash
   git clone https://github.com/YourUsername/personal-portfolio.git
   ```

2. Open the project folder in your code editor

3. Launch the website by opening `index.html` in your browser

### Configuration

#### Formspree Setup

The contact forms are already configured with Formspree. If you're forking this project, you'll need to:

1. Create your own Formspree account at [formspree.io](https://formspree.io/)
2. Create a new form and get your form ID
3. Replace the existing form ID in both forms:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

#### Social Media Links

Update the social media links in the contact section and footer:

```html
<div class="social-links">
    <a href="YOUR_FACEBOOK_URL" target="_blank"><i class="fab fa-facebook-f"></i></a>
    <a href="YOUR_INSTAGRAM_URL" target="_blank"><i class="fab fa-instagram"></i></a>
    <a href="YOUR_LINKEDIN_URL" target="_blank"><i class="fab fa-linkedin-in"></i></a>
    <a href="YOUR_GITHUB_URL" target="_blank"><i class="fab fa-github"></i></a>
</div>
```

## 📱 Mobile Responsiveness

The website is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones

The responsive design uses:
- Fluid layouts
- Flexible images
- Media queries for different screen sizes
- Appropriate touch targets for mobile users

## 🔄 Customization

### Changing Colors

The website uses CSS variables for easy color customization. Edit the following in the CSS section:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --dark-color: #1e293b;
    --light-color: #f8fafc;
    --text-color: #334155;
    --accent-color: #3b82f6;
}
```

### Adding New Projects

To add a new project, copy the project card structure and update the content:

```html
<div class="project-card">
    <div class="project-img">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span class="project-tag">Technology 1</span>
            <span class="project-tag">Technology 2</span>
            <span class="project-tag">Technology 3</span>
        </div>
    </div>
</div>
```

## 🔍 SEO Tips

- Add a proper meta description to improve search engine visibility
- Include relevant keywords in your content
- Ensure all images have descriptive alt text
- Create a sitemap.xml file
- Register your site with Google Search Console

## 📄 License

This project is available for personal and commercial use with appropriate attribution.

## 🙏 Acknowledgements

- Font Awesome for the icons
- Formspree for the form backend
- Google Fonts for typography options

---

Made with ❤️ by Kusal Pabasara | [LinkedIn](https://www.linkedin.com/in/kusal-pabasara-3a17b5363/) | [GitHub](https://github.com/KusalPabasara)
