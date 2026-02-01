# Krrish - Engineer Portfolio

A cyberpunk-themed portfolio website showcasing skills, projects, and experience as a Full Stack Developer. Built with pure HTML and CSS (no JavaScript).

##  Single-Page Architecture

**Important**: This project uses a **single-file structure**. All sections (Boot, About, Internship, Skills, Projects, Contact, Footer) are contained within `index.html` itself, rather than being split into separate files. This makes the project lightweight, easy to maintain, and simple to deploy.

## File Structure

```
Portfolio assignment/
│
├── index.html          # Main HTML file (contains ALL sections in one file)
├── style.css          # All styling and animations
├── assets/
│   └── bg-grid.jpg    # Background grid image
└── README.md          # This file
```

## Features

### Design & Theme
- **Cyberpunk/Tech Aesthetic**: Neon cyan color scheme with glowing effects
- **Grid Background**: Custom grid pattern overlay
- **Smooth Animations**: CSS-only animations and transitions
- **Fully Responsive**: Mobile-friendly design
- **Pure HTML/CSS**: No JavaScript dependencies

### Sections

#### 1. Boot/Landing Section
- Animated typing effect
- Floating icon animations
- Glitch effect on title hover

#### 2. About Section
- System diagnostics display
- Contact information cards
- Interactive hover effects

#### 3. Internship Section
- Highlighted experience at Parben Private Limited
- Achievement list with bullet points
- Tech stack badges
- Special neon border styling

#### 4. Skills Matrix
- **Categorized Skills**:
  - Languages (JavaScript/TypeScript, C, C++, Java, Python, XML, JSON)
  - Frameworks (Qt, Next.js, Express.js, React.js, Expo, Django, FastAPI, OOPS)
  - Tools & Platforms (Git, GitHub, AWS, Docker, NRN, MongoDB, LangChain)
  - Soft Skills (Pragmatic Approach, Adaptability, Problem-Solving, Team Player)
- Individual progress bars for each skill
- Compact grid layout
- Hover interactions

#### 5. Projects Section
- AI Directory Management System
- Gesture Control System
- HTTP Server from Scratch
- Card-based layout with hover effects
- Status badges

#### 6. Contact Section
- Contact information display
- Contact form with CSS validation
- Real-time visual feedback (green/red borders)
- Submit button with hover effects

#### 7. Footer
- Clickable social media icons (GitHub, LinkedIn, Email)
- SVG icons with hover animations
- Copyright information

### Navigation
- Fixed top navigation bar
- Smooth scroll to sections
- Active hover states
- Responsive mobile menu

### Additional Features
- Custom scrollbar with neon styling
- Back-to-top button with rotation animation
- Backdrop blur effects on panels
- Scanline overlay effect
- Glow and shadow effects throughout

## Technologies Used

- **HTML5**: Semantic markup, form validation
- **CSS3**: Grid, Flexbox, animations, transitions, custom properties
- **SVG**: Social media icons

## Setup & Installation

1. Clone or download this repository
2. Ensure the `assets` folder contains `bg-grid.jpg`
3. Open `index.html` in a modern web browser

No build process or dependencies required!

## Browser Compatibility

Works best on modern browsers that support:
- CSS Grid
- CSS Flexbox
- CSS Custom Properties (Variables)
- CSS Animations & Transitions
- HTML5 Form Validation

Tested on:
- Chrome/Edge (Chromium)
- Firefox
- Safari

## Customization

### Colors
Edit CSS variables in `style.css`:
```css
:root {
    --bg-main: #050505;
    --panel-bg: #0d0d0d;
    --border-color: #1f1f1f;
    --neon: #00f7ff;
    --text-dim: #9aa0a6;
}
```

### Content
All content can be edited directly in `index.html`:
- Personal information
- Skills and percentages
- Project descriptions
- Contact details

### Background
Replace `assets/bg-grid.jpg` with your own image.

## Performance

- **No JavaScript**: Faster load times, no runtime overhead
- **Single HTML file**: Minimal HTTP requests
- **Optimized CSS**: Efficient selectors and animations
- **Lightweight**: Total size < 100KB (excluding background image)

## Features Highlights

### CSS-Only Form Validation
The contact form uses HTML5 validation with CSS pseudo-selectors:
- `:invalid` for error states
- `:valid` for success states
- `:placeholder-shown` for initial state
- Visual feedback without JavaScript

### Animations
- Typing effect
- Floating icons
- Progress bar fills
- Card hover effects
- Button transformations
- Glitch effects
- Pulse animations

### Accessibility
- Semantic HTML5 elements
- Proper heading hierarchy
- Alt text for visual elements
- Keyboard navigation support
- Focus states for interactive elements

## Contact

- **Email**: krrish7ds@gmail.com
- **GitHub**: [Krrish2401](https://github.com/Krrish2401)
- **LinkedIn**: [linkedin.com/in/krrish](https://linkedin.com/in/krrish)
- **Mobile**: +91-8178396138

## License

© 2026 Krrish. All rights reserved.

---

**Built with ❤️ using pure HTML & CSS**
