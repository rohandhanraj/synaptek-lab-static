# Synaptek Lab - Static Website

A modern, futuristic website for Synaptek Lab, a non-profit AI education platform.

## 🎯 Project Overview

Synaptek Lab is a free educational platform providing knowledge on trending AI technologies including AI, ML, MLOps, Gen AI, and Agentic AI. The platform features an interactive Agent Studio for building and testing AI agents.

## 📁 File Structure

```
synaptek-lab/
├── index.html              # Home page
├── agent-studio.html       # Agent Studio playground
├── about.html              # About Us page
├── contact.html            # Contact page
├── privacy-policy.html     # Privacy Policy
├── terms-of-service.html   # Terms of Service
├── data-deletion.html      # Data Deletion Instructions
├── robots.txt              # Search engine crawler instructions
├── sitemap.xml             # XML sitemap for SEO
└── README.md               # This file
```

## 🎨 Design Features

### Visual Style
- **Futuristic Tech Aesthetic**: Circuit board patterns, neon accents, cyberpunk-inspired design
- **Color Scheme**: 
  - Primary: #00d4ff (Cyan)
  - Secondary: #0066cc (Blue)
  - Accent: #ff00ff (Magenta)
  - Background: #050814 (Dark blue-black)
  
### Typography
- **Headings**: Orbitron (futuristic, tech-inspired)
- **Body**: Rajdhani (modern, readable)

### Animations
- Sliding circuit board background
- Smooth page transitions
- Hover effects on cards and buttons
- Gradient animations

## 🌐 Pages Description

### 1. Home (index.html)
- Hero section with tagline
- Feature showcase
- Technology tags
- Call-to-action buttons

### 2. Agent Studio (agent-studio.html)
- Interactive playground interface (static mockup)
- Sidebar with agent templates
- Code editor mockup
- Feature highlights

### 3. About Us (about.html)
- Mission statement
- Organization overview
- Core values
- Educational approach

### 4. Contact (contact.html)
- Contact form
- Email addresses
- Response time information
- Multiple contact methods

### 5. Privacy Policy (privacy-policy.html)
- Data collection practices
- User rights (GDPR compliant)
- Cookie policy
- Security measures

### 6. Terms of Service (terms-of-service.html)
- Acceptable use policy
- Service description
- User responsibilities
- Liability limitations

### 7. Data Deletion (data-deletion.html)
- Step-by-step deletion process
- Timeline for processing
- Browser data clearing instructions
- Contact information

## 🔗 Important URLs for App Integration

### Legal/Policy Endpoints
```
Privacy Policy:         /privacy-policy.html
                       OR
                       https://yourdomain.com/privacy-policy.html

Terms of Service:       /terms-of-service.html
                       OR
                       https://yourdomain.com/terms-of-service.html

Data Deletion:          /data-deletion.html
                       OR
                       https://yourdomain.com/data-deletion.html
```

## 🚀 Deployment Instructions

### Option 1: GitHub Pages
1. Create a new repository on GitHub
2. Upload all HTML files to the repository
3. Go to Settings → Pages
4. Select branch (main/master) and root folder
5. Save and get your GitHub Pages URL

### Option 2: Netlify
1. Create account on Netlify
2. Drag and drop all files to Netlify dashboard
3. Get instant deployment URL
4. Optional: Configure custom domain

### Option 3: Vercel
1. Create account on Vercel
2. Import project from Git or upload files
3. Deploy with one click
4. Configure custom domain if needed

### Option 4: Traditional Web Hosting
1. Upload all files via FTP to your web server
2. Ensure index.html is in the root directory
3. Configure domain settings with your hosting provider

## 🔧 Customization

### Updating Content
1. Open the relevant HTML file in a text editor
2. Modify text content within HTML tags
3. Save and re-upload to your hosting

### Changing Colors
All color variables are defined in the `:root` section of each page's `<style>` tag:
```css
:root {
    --primary: #00d4ff;
    --secondary: #0066cc;
    --accent: #ff00ff;
    --dark: #0a0e27;
    --darker: #050814;
    --light: #e0f4ff;
    --gradient: linear-gradient(135deg, #0066cc 0%, #00d4ff 50%, #ff00ff 100%);
}
```

### Adding Logo Images
Replace the text logo with images by modifying the `.logo` class in the navigation:
```html
<!-- Current text logo -->
<div class="logo">Synaptek Lab</div>

<!-- Replace with -->
<div class="logo">
    <img src="path/to/logo.png" alt="Synaptek Lab" style="height: 50px;">
</div>
```

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1920px and above)
- Laptop (1366px - 1920px)
- Tablet (768px - 1366px)
- Mobile (320px - 768px)

## ⚡ Performance

- Minimal dependencies (only Google Fonts)
- Lightweight CSS animations
- Optimized for fast loading
- No JavaScript frameworks required

## 🔒 Privacy & Security

- Minimal data collection
- No third-party analytics (can be added if needed)
- GDPR compliant
- Clear data deletion process
- Secure by default

## 📞 Contact Information

Update these email addresses in the contact pages:
- General: info@synapteklab.org
- Support: support@synapteklab.org
- Privacy: privacy@synapteklab.org
- Legal: legal@synapteklab.org

## 🌟 Features

- ✅ Modern, futuristic design
- ✅ Fully responsive
- ✅ SEO optimized (meta tags, sitemap, robots.txt)
- ✅ Accessible navigation
- ✅ Smooth animations
- ✅ Professional legal pages
- ✅ Contact form ready
- ✅ Fast loading
- ✅ Cross-browser compatible

## 🛠️ Technical Stack

- HTML5
- CSS3 (with animations and gradients)
- Google Fonts (Orbitron, Rajdhani)
- No JavaScript dependencies (pure CSS)

## 📄 License

This is a non-profit educational website. Content is provided for educational purposes.

## 🤝 Contributing

To contribute or suggest improvements:
1. Fork the repository
2. Make your changes
3. Submit a pull request
4. Or contact via the contact form

## 📊 SEO Optimization

Included features:
- Meta descriptions on all pages
- Semantic HTML structure
- robots.txt file
- XML sitemap
- Proper heading hierarchy
- Alt tags ready for images

## 🎓 Educational Use

This website is designed for a non-profit educational initiative. All content is provided free of charge for learning purposes.

## 📝 Notes

- The Agent Studio is currently a static mockup - backend functionality needs to be implemented separately
- Contact form requires backend implementation for actual email sending
- Update domain URLs in robots.txt and sitemap.xml before deployment
- Consider adding actual logo images to replace text logo

---

**Built with ❤️ for AI Education**

*Synaptek Lab - Powering Your Future with Intelligence*
