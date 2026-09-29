# Yatharth Verma - Professional Web Developer Portfolio

A modern, responsive, and performance-optimized personal portfolio website built with clean, semantic HTML5, modern CSS3 (with CSS Custom Properties, Glassmorphism, and animations), and Vanilla JavaScript.

## 🌟 Key Features

- **Personalized Hero Section**:
  - Highlights **Yatharth Verma** with gradient typography.
  - Interactive typewriter effect cycling through core developer specialties.
  - Interactive code terminal mock showcasing developer profile and core competencies.
  - Quick metrics banner (3+ Years Experience, 25+ Projects, 100% Satisfaction).
  - Floating tech pill micro-animations.

- **About Me Section**:
  - Detailed developer narrative highlighting philosophy, journey, and problem-solving mindset.
  - Developer identity card with key bio points (location, education, languages, availability).
  - 4 Engineering pillars: *Modern Frontend*, *Scalable Backends*, *Performance & SEO*, *Clean Code Standard*.

- **Dynamic Skills & Competencies Page/Section**:
  - Interactive category filter tabs: *All*, *Frontend & UI*, *Backend & APIs*, *Database & Cloud*, *DevOps & Tools*.
  - Skill cards with animated proficiency meters, proficiency badges (Expert, Advanced, Proficient), and description tags.

- **Featured Projects Showcase**:
  - Production-grade mock project cards (*NexusFlow SaaS*, *DevPulse Analytics*, *Aura E-Commerce*).
  - Tech tags, live demo buttons, and GitHub source links.

- **Interactive Contact Me Section**:
  - Functional contact form with client-side field validation (Name, Email, Subject, Message).
  - Simulated send action with button loading state and custom toast alert.
  - Direct communication cards with click-to-copy email functionality (`yatharthverma.dev@gmail.com`).
  - Social media links (GitHub, LinkedIn, Twitter/X, Dev.to).

- **Theme Switcher**:
  - Dark mode (default) and Light mode toggle with smooth color transitions.
  - Persists preference across sessions using `localStorage` and respects system `prefers-color-scheme`.

- **Responsive & Accessible**:
  - Fluid mobile navigation drawer with backdrop blur.
  - Keyboard accessible, ARIA tags, and responsive breakpoints for mobile, tablet, and desktop screens.

---

## 📁 File Structure

```text
yatharth-portfolio/
│
├── index.html          # Main HTML structure with semantic sections
├── css/
│   └── styles.css      # Design tokens, themes, layouts, animations
├── js/
│   └── main.js         # Theme toggle, typewriter, skill filter, form logic, toast
└── README.md           # Documentation and deployment instructions
```

---

## 🚀 How to Run Locally

Because the project is built with vanilla web technologies, you don't need any npm installations or build steps!

### Option 1: Python Built-in Server
Open your terminal, navigate to the portfolio directory, and run:

```bash
cd /Users/macbook/.gemini/antigravity/scratch/yatharth-portfolio
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

### Option 2: Direct Browser Opening
Simply double-click `index.html` or open it with your favorite browser:
- On macOS: `open index.html`

---

## 🎨 Customization Guide

1. **Changing Social Links**:
   In `index.html`, search for `social-icons` and update the `href` attributes for GitHub, LinkedIn, and Twitter/X with your real profile URLs.

2. **Updating Your Email**:
   In `index.html`, update the email address displayed in the `#contact` section, and update the default email address in `js/main.js` inside the `initCopyActions()` function.

3. **Adding More Skills or Projects**:
   - Skills can be added by copying a `.skill-card` block in `index.html` and setting the appropriate `data-category="frontend|backend|database|tools"`.
   - Projects can be added or adjusted by copying a `.project-card` block in the `#projects` section.

---

## 🌐 Free Deployment Options

- **Vercel**: Run `npx vercel` or link your GitHub repo directly in the Vercel dashboard.
- **GitHub Pages**: Push this directory to a repository named `<your-username>.github.io` or enable GitHub Pages under repository Settings -> Pages.
- **Netlify**: Drag and drop the `yatharth-portfolio` folder into [Netlify Drop](https://app.netlify.com/drop).
