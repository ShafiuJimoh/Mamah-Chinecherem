# Chinecherem Mamah - Portfolio Website

A modern, interactive portfolio website showcasing social media management expertise, content creation, and digital marketing projects.

## ✨ Features

### 1. **Dynamic Background Images**
- Seamlessly transitioning background images from Unsplash
- 5 different professional social media themed backgrounds
- Smooth fade transitions every 5 seconds
- Maintains visual interest without distraction

### 2. **Interactive Portfolio Highlights**
- Click any portfolio card to view detailed information
- "Tap to see more" call-to-action on each project
- Modal popup with comprehensive project details including:
  - Project overview and context
  - Role and responsibilities
  - Key achievements and metrics
  - Social media showcase gallery
  - Direct links to live Instagram profiles

### 3. **Separate Detail Pages**
Each portfolio highlight has its own dedicated page:
- **tpe-detail.html** - The People's Economy project
- **boxes-detail.html** - Boxes by PG project
- More pages can be easily added following the same structure

### 4. **Embeddable Portfolio Sections**
Complete embed code library for integrating portfolio projects anywhere:
- Standard iframe embeds
- Responsive embeds (adapts to any screen size)
- WordPress compatible code
- JavaScript dynamic embed
- Modal/popup style embed
- View all embed options in `embed-code.html`

### 5. **Enhanced User Experience**
- Smooth scroll navigation
- Parallax hero section
- Animated stats section
- Interactive timeline for work experience
- Hover effects and transitions throughout
- Mobile-responsive design
- Loading animation

## 📁 File Structure

```
/home/user/webapp/
├── index.html              # Main portfolio website
├── portfolio-data.js       # Portfolio project data
├── tpe-detail.html        # The People's Economy detail page
├── boxes-detail.html      # Boxes by PG detail page
├── embed-code.html        # Embed code reference guide
└── README.md              # This file
```

## 🚀 Usage

### Viewing the Portfolio
1. Open `index.html` in a web browser
2. Navigate through sections using the top menu
3. Click on any portfolio card to see detailed information
4. Click "Tap to see more" to open the project modal

### Using Detail Pages
Each detail page can be:
- Viewed standalone in a browser
- Embedded in other websites using iframe
- Shared as a direct link
- Integrated into WordPress or other CMS

### Embedding Portfolio Projects
1. Open `embed-code.html` for complete embedding guide
2. Choose your preferred embedding method
3. Replace `YOUR-DOMAIN.com` with your actual domain
4. Copy and paste the code into your target website

## 🎨 Customization

### Adding New Portfolio Projects

1. **Add data to `portfolio-data.js`:**
```javascript
newproject: {
    title: "Project Name",
    overview: "Project description...",
    responsibilities: ["Item 1", "Item 2"],
    achievements: ["Achievement 1"],
    images: ["url1", "url2"],
    link: "https://instagram.com/..."
}
```

2. **Add card to `index.html` portfolio section:**
```html
<div class="project-card" data-project="newproject">
    <!-- Card content -->
</div>
```

3. **Create detail page:** (optional)
Copy `tpe-detail.html` and customize with project data

### Changing Background Images
Edit the background image URLs in `index.html`:
```html
<div class="bg-image" style="background-image: url('NEW-IMAGE-URL');"></div>
```

### Customizing Colors
Modify CSS variables in `index.html`:
```css
:root {
    --teal: #20B2AA;
    --blue-green: #1E90FF;
    --pink: #FF69B4;
    --gold: #FFD700;
}
```

## 🔗 Links

Portfolio includes links to:
- LinkedIn Profile
- Instagram (Boxes by PG)
- Instagram (The People's Economy)
- Email contact

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1920px and above)
- Laptop (1366px - 1920px)
- Tablet (768px - 1365px)
- Mobile (320px - 767px)

## 🌟 Key Sections

1. **Hero** - Introduction and CTA buttons
2. **Stats** - Key metrics showcase
3. **About** - Professional background
4. **Experience** - Timeline of work history
5. **Portfolio** - Featured projects with details
6. **Skills** - Core competencies
7. **Tools** - Software and platforms
8. **Testimonials** - Client feedback
9. **Contact** - Get in touch form

## 💻 Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Poppins & Playfair Display)
- Unsplash Images

## 📄 License

© 2024 Chinecherem Mamah. All rights reserved.

## 📧 Contact

- Email: mamahchinecherem@gmail.com
- Phone: +234 812 401 9450
- Location: Ogudu, Lagos State, Nigeria

---

**Note:** Remember to replace placeholder URLs and update the Formspree form ID in the contact section before deploying.
