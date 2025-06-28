# Kenzy Walid - Professional Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a beautiful green theme and excellent UI/UX design.

## 🌟 Features

- **Modern Design**: Clean, professional layout with a green color scheme
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth animations, hover effects, and interactive elements
- **Professional Sections**: Hero, About, Skills, Projects, Certificates, and Contact
- **Mobile-Friendly**: Hamburger menu for mobile navigation
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation
- **Image Gallery**: Clickable certificate images with modal view
- **Loading Animations**: Smooth loading effects and transitions

## 🎨 Design Features

- **Green Theme**: Professional green color palette
- **Typography**: Modern Inter font family
- **Shadows & Effects**: Subtle shadows and hover effects
- **Gradients**: Beautiful gradient backgrounds
- **Icons**: Font Awesome icons for enhanced visual appeal
- **Animations**: CSS animations and JavaScript interactions

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
├── kenzyyyyyyyyy.jpg   # Profile image
├── data analysis.jpeg  # Project image
├── EYouth data camp.png # Project image
├── hippo competiotion.jpg # Project image
├── IEEE.jpg           # Certificate image
├── python basics.png  # Certificate image
├── data base fundmentals.png # Certificate image
├── voulnteer certificate.png # Certificate image
├── agya training.jpg  # Certificate image
└── [other certificate files]
```

## 🚀 Getting Started

1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting platform

## ✏️ Customization Guide

### Personal Information
Edit the following sections in `index.html`:

- **Name**: Update "Kenzy Walid" throughout the file
- **Title**: Change "Data Analyst & AI Enthusiast" to your profession
- **Description**: Update the hero description and about section
- **Contact Info**: Update email, phone, and location in the contact section
- **Social Links**: Add your actual social media URLs

### Images
- **Profile Image**: Replace `kenzyyyyyyyyy.jpg` with your photo
- **Project Images**: Update project images with your actual work
- **Certificate Images**: Replace with your actual certificates

### Skills
Update the skills section in `index.html`:
```html
<div class="skill-item">
    <span class="skill-name">Your Skill</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### Projects
Add your projects in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
        </div>
    </div>
</div>
```

### Certificates
Add your certificates in the certificates section:
```html
<div class="certificate-card">
    <div class="certificate-image">
        <img src="your-certificate.jpg" alt="Certificate Name">
    </div>
    <div class="certificate-content">
        <h3>Certificate Name</h3>
        <p>Certificate description.</p>
    </div>
</div>
```

## 🎨 Color Customization

The green theme can be customized by modifying CSS variables in `styles.css`:

```css
:root {
    --primary-green: #10b981;      /* Main green color */
    --primary-green-dark: #059669; /* Darker green for hover */
    --primary-green-light: #34d399; /* Lighter green */
    --secondary-green: #6ee7b7;    /* Secondary green */
    --accent-green: #a7f3d0;       /* Accent green */
    --dark-green: #064e3b;         /* Dark green */
    --light-green: #ecfdf5;        /* Light green background */
}
```

## 📱 Responsive Design

The portfolio is fully responsive and includes:
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Flexible grid layouts
- Optimized typography for all screen sizes
- Touch-friendly interactive elements

## 🔧 JavaScript Features

- **Mobile Navigation**: Hamburger menu functionality
- **Smooth Scrolling**: Anchor link navigation
- **Scroll Effects**: Navbar background changes on scroll
- **Animations**: Intersection Observer for scroll-triggered animations
- **Form Validation**: Contact form with email validation
- **Notifications**: Success/error message system
- **Modal Gallery**: Clickable certificate images
- **Counter Animation**: Animated statistics
- **Typing Effect**: Hero title typing animation

## 🌐 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain or use the provided Netlify URL

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. Get a custom domain or use the provided Vercel URL

## 📧 Contact Form

The contact form includes:
- Form validation
- Email format checking
- Success/error notifications
- Loading states

**Note**: The current form simulates submission. To make it functional, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Configure email sending (SendGrid, Nodemailer, etc.)
3. Update the form action and method

## 🔍 SEO Optimization

The portfolio includes:
- Semantic HTML structure
- Meta tags for social sharing
- Alt text for images
- Proper heading hierarchy
- Fast loading times

## 🛠️ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Built with ❤️ for showcasing your amazing work!** 