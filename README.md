# Serenity Springs Couples Retreat Website - October 2025

A beautiful, responsive website for a couples retreat center built with modern web technologies. Specifically designed for the October 2025 romantic getaway programs.

## 🌟 Features

- **Couples-Focused Design**: Romantic theme perfect for couples retreats
- **October 2025 Programs**: Three distinct retreat packages for different needs
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, romantic design with smooth animations
- **Interactive Elements**: Contact form, mobile navigation, scroll effects
- **Accessibility**: Keyboard navigation and focus indicators
- **Performance Optimized**: Lightweight and fast-loading
- **SEO Ready**: Semantic HTML structure and meta tags

## 📁 Project Structure

```
retreat-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Local Testing

### Method 1: Simple File Opening
1. Navigate to the `retreat-website` folder
2. Double-click `index.html` to open in your default browser
3. The website will load locally with `file://` protocol

### Method 2: Local Server (Recommended)
For better testing experience, use a local server:

#### Using Python (if installed):
```bash
# Navigate to the retreat-website folder
cd retreat-website

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Then visit: `http://localhost:8000`

#### Using Node.js (if installed):
```bash
# Install a simple server globally
npm install -g http-server

# Navigate to the retreat-website folder
cd retreat-website

# Start the server
http-server -p 8000
```
Then visit: `http://localhost:8000`

#### Using VS Code Live Server Extension:
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🌐 Public Hosting Options

### 1. GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### 2. Netlify (Free Tier Available)
1. Visit [netlify.com](https://netlify.com)
2. Drag and drop the `retreat-website` folder to deploy
3. Get instant HTTPS URL
4. Optional: Connect to GitHub for automatic deployments

### 3. Vercel (Free Tier Available)
1. Visit [vercel.com](https://vercel.com)
2. Import from GitHub or upload files
3. Automatic deployments and HTTPS

### 4. Surge.sh (Free)
```bash
# Install surge globally
npm install -g surge

# Navigate to your project folder
cd retreat-website

# Deploy
surge
```

### 5. Firebase Hosting (Free Tier Available)
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login and initialize
firebase login
firebase init hosting

# Deploy
firebase deploy
```

## 🎨 Customization

### Colors
Edit the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #2c5530;    /* Main green color */
    --secondary-color: #8fbc8f;  /* Light green */
    --accent-color: #d4a574;     /* Gold accent */
    /* ... other colors */
}
```

### Content
- **Retreat Name**: Currently set to "Serenity Springs Couples Retreat"
- **Dates**: October 2025 programs (Weekend: Oct 4-6, Week: Oct 11-18, Ultimate: Oct 25-Nov 1)
- **Contact Info**: Update the contact section with real details
- **Programs**: Three couples-focused programs with romantic themes
- **Images**: Replace emoji placeholders with real romantic/couples images

### Adding Real Images
1. Create an `images` folder in the project
2. Add your images (recommended: WebP format for better performance)
3. Replace the `.image-placeholder` divs with `<img>` tags:
```html
<img src="images/hero-image.webp" alt="Mountain retreat view" class="hero-image">
```

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Flexible grid layouts
- Touch-friendly buttons and forms
- Optimized typography for all screen sizes

## ⚡ Performance Features

- **Lightweight**: No external dependencies except Google Fonts
- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Lazy Loading Ready**: Infrastructure for image lazy loading
- **Debounced Events**: Optimized scroll event handling

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Form

The contact form includes:
- Client-side validation
- Email format checking
- Success/error notifications
- Form reset after submission
- Accessibility features

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
1. Add a backend service (Node.js, PHP, etc.)
2. Use a form service like Formspree, Netlify Forms, or EmailJS
3. Integrate with your preferred email service

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta tags for description and viewport
- Proper heading hierarchy (H1, H2, H3, etc.)
- Alt text ready for images
- Clean URL structure

## 🚀 Next Steps

1. **Test Locally**: Open the website and test all functionality
2. **Customize Content**: Replace placeholder content with real information
3. **Add Images**: Replace emoji placeholders with professional photos
4. **Set Up Hosting**: Choose a hosting platform and deploy
5. **Configure Domain**: Point your custom domain to the hosting service
6. **Add Analytics**: Integrate Google Analytics or similar service
7. **Set Up Contact Form**: Implement backend or use a form service

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Support

For questions or customization help, feel free to reach out or create an issue in the repository.

---

**Happy hosting! 🌿✨**