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