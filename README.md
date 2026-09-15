# Personal Portfolio Website

A modern, responsive portfolio website to showcase your projects, skills, and experience.

## Features

✨ **Modern Design**
- Clean and professional layout
- Smooth animations and transitions
- Responsive design that works on all devices

🎨 **Customizable**
- Easy to update with your own information
- Gradient color scheme (easily adjustable)
- Simple HTML/CSS structure

📱 **Responsive**
- Mobile-friendly design
- Works perfectly on phones, tablets, and desktops

🚀 **Performance**
- No dependencies or frameworks required
- Lightweight HTML and CSS
- Fast loading times

## Sections

1. **Navigation Bar** - Sticky navigation for easy access
2. **Hero Section** - Eye-catching introduction
3. **About** - Brief bio and introduction
4. **Projects** - Showcase your best work
5. **Skills** - Display technical expertise
6. **Contact** - Links to get in touch
7. **Footer** - Copyright and additional info

## Getting Started

### Setup

1. Clone this repository
2. Open `index.html` in your web browser
3. Customize the content with your information

### Customization

#### Update Your Information

Edit `index.html` and replace:
- "Your Name" with your actual name
- "your.email@example.com" with your email
- Project descriptions and links
- Skills and categories
- Social media links (GitHub, LinkedIn, Twitter)

#### Customize Colors

Edit the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #667eea;      /* Main brand color */
    --secondary-color: #764ba2;    /* Accent color */
    --text-color: #333;            /* Text color */
    --light-bg: #f7f7f7;           /* Light background */
}
```

#### Add Projects

To add more projects, duplicate a `.project-card` div in the Projects section:

```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #color1 0%, #color2 100%);"></div>
    <h3>Project Name</h3>
    <p>Project description here</p>
    <div class="project-tags">
        <span class="tag">Tech</span>
        <span class="tag">Stack</span>
    </div>
    <a href="#" class="btn btn-outline">View Project</a>
</div>
```

#### Add Skills

To add more skill categories, duplicate a `.skill-category` div:

```html
<div class="skill-category">
    <h3>Category Name</h3>
    <ul>
        <li>Skill 1</li>
        <li>Skill 2</li>
        <li>Skill 3</li>
    </ul>
</div>
```

## Deployment

### GitHub Pages (Recommended)

1. Push this repository to GitHub
2. Go to **Settings** → **Pages**
3. Set the source to **main** branch
4. Your site will be available at `https://yourusername.github.io/portfolio`

### Other Hosting Options

- **Netlify** - Free hosting with automatic deployments
- **Vercel** - Simple deployment from Git
- **Traditional Hosting** - Upload files via FTP

## Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Styling
└── README.md          # This file
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Future Enhancements

Consider adding:
- Smooth scroll behavior (already included!)
- Dark mode toggle
- Blog section
- Resume/CV download
- Form validation for contact
- Image optimization

## Tips

- Use high-quality images or gradient backgrounds
- Keep project descriptions concise
- Update your portfolio regularly
- Test on mobile devices before deploying
- Use meaningful link descriptions

## License

Feel free to use this template for your personal portfolio!

---

**Happy building! 🚀**
