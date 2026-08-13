# Chanwoong Jhon - Portfolio Website

Chanwoong Jhon's public career portfolio, focused on infrastructure and platform engineering, automation, secure compute, and experimental distributed AI serving.

## 🎨 Features

- **Modern Dark Theme** - Professional gradient-based design
- **Fully Responsive** - Works on all devices
- **Smooth Animations** - Scroll-triggered animations
- **Evidence Oriented** - Separates professional experience from personal experiments and emphasizes verifiable impact
- **GitHub Pages Ready** - Deploy with one command

## 📁 File Structure

```
templeside.github.io/
├── index.html      # Main HTML file
├── styles.css      # All styles (16KB)
├── script.js       # Interactive features
└── README.md       # This file
```

## 🚀 Quick Start

### Local Development

```bash
# Open in browser directly
open index.html

# Or use a local server
python3 -m http.server 8000
# Visit http://localhost:8000
```

### Deploy to GitHub Pages

This repository is the user-site repository. Pushing the verified `master` branch publishes `https://templeside.github.io/` through GitHub Pages.

## ✏️ Customization

### Update Personal Info

Edit `index.html` and update:

1. **Hero Section** - Name, title, location, description
2. **About Section** - Summary and skills
3. **Experience** - Job details and responsibilities
4. **Projects** - Add/modify project cards
5. **Contact** - Email, GitHub, LinkedIn links

### Change Color Scheme

Edit `styles.css` CSS variables at the top:

```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --secondary-color: #8b5cf6;  /* Secondary accent */
    --accent-color: #06b6d4;     /* Highlight color */
}
```

### Add Profile Photo

Replace the `.blob` div in the hero section with an actual image:

```html
<div class="hero-image">
    <img src="profile.jpg" alt="Chanwoong Jhon" class="profile-photo">
</div>
```

Then add CSS:

```css
.profile-photo {
    width: 400px;
    height: 400px;
    object-fit: cover;
    border-radius: 30% 70% 70% 30% / 30% 30% 70% 70%;
    animation: blob-bounce 8s ease-in-out infinite;
}
```

## Content boundary

- Professional work and personal experiments are labeled separately.
- Only externally shareable, verified facts belong on this public site.
- Client-confidential diagrams, configuration values, source documents, private finance, immigration details, and internal company material must never be published here.
- Experimental GPU serving remains a personal project until it has a sanitized public repository with reproducible deployment, benchmark, observability, and recovery evidence.

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome (icons)
- Google Fonts (Inter)

## 📝 TODO

- [ ] Add actual profile photo
- [ ] Update LinkedIn URL
- [ ] Add LeetCode/Codeforces links if applicable
- [ ] Include blog/technical writing section
- [ ] Publish a sanitized, reproducible AI-serving lab repository
- [ ] Add an architecture diagram and benchmark methodology after privacy review
- [ ] Create dark/light mode toggle
- [ ] Add resume download button

## 📄 License

Free to use and modify for personal and commercial purposes.

---

**Public evidence for infrastructure and platform engineering work.**
