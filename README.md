# Personal Portfolio Website — Udit Khatri

A professional, modern, and fully responsive personal portfolio website showcasing the academic background, achievements, skills, and strategic interests of **Udit Khatri**.

Built with an executive aesthetic suited for finance, consulting, and business strategy—combining midnight navy, warm ivory, slate grey, and restrained gold accents.

---

## 1. Project Overview & Highlights

- **Live URL**: Hosted publicly via GitHub Pages.
- **Role/Profile**: Undergraduate Student (IIM Bangalore & JNVU Dual-Degree) | Finance Enthusiast | CFA Level I Aspirant | National Case Competition Winner.
- **Design Philosophy**: Minimalist, elegant, high-contrast, and content-first. Designed as an expanded, interactive professional resume.
- **Architecture**: Strictly **pure HTML5 and CSS3**—zero JavaScript, zero CSS frameworks (no Bootstrap, no Tailwind), and zero external script dependencies.

---

## 2. Technologies Used

- **HTML5**: Semantic document structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3**:
  - CSS Custom Properties (Variables) for color theming and design tokens.
  - Modern Layouts: **Flexbox** (`display: flex`) and **CSS Grid** (`display: grid`).
  - Native Smooth Scrolling (`scroll-behavior: smooth`).
  - CSS Media Queries for full multi-device responsiveness (Desktop, Laptop, Tablet, Mobile).
  - Pure HTML/CSS accessible mobile navigation using `<details>` and `<summary>`.
- **Google Fonts**:
  - *Playfair Display* — Editorial serif for headings, reflecting academic and financial prestige.
  - *Plus Jakarta Sans* — Clean, highly legible sans-serif for body typography.

---

## 3. Directory & File Structure

```text
personal-portfolio/
│
├── index.html          # Semantic HTML5 single-page structure
├── style.css           # Pure CSS3 styles, variables, grid/flex, responsive queries
├── assets/
│   └── profile.jpg     # Professional portrait photograph of Udit Khatri
└── README.md           # Documentation, architectural guide, and code explanations
```

### File Breakdown:
- **`index.html`**: Contains the complete markup divided into 7 distinct semantic sections:
  1. *Header / Navbar*: Sticky top bar with monogram logo, desktop navigation links, and pure-CSS mobile toggle.
  2. *Section 1: Hero / Introduction*: Prominent introduction, status pill, contact/education metadata, and action buttons.
  3. *Section 2: About Me*: Two-column layout pairing Udit's original photograph with his background and goals.
  4. *Section 3: Education*: Highlighting the dual-degree pursuit (IIM Bangalore + JNVU) and academic metrics (Class 12: 91.20%, Class 10: 81.83%).
  5. *Section 4: Achievements*: Detailed cards for national case competition wins (IIT Bombay, SCMHRD Pune) and chess tournaments (IIM Indore, District level).
  6. *Section 5: Skills*: Four competency cards (Problem Solving, Leadership, Community Management, Communication).
  7. *Section 6: Interests & Hobbies*: Intellectual and extracurricular pursuits (Reading, Web Research, Chess, Volleyball).
  8. *Section 7: Contact & Footer*: Direct channels (Email and LinkedIn) and copyright notice.
- **`style.css`**: Organised into 13 logical, commented modules for ease of understanding and demonstration.
- **`assets/profile.jpg`**: High-resolution, unedited photograph presented in a formal frame with subtle gold borders.

---

## 4. How to Open the Website Locally

You can run this website on any computer without installing servers or compilers:

1. **Directly via Browser**:
   - Navigate to the project directory: `personal-portfolio`.
   - Double-click `index.html` (or right-click → **Open with** → Google Chrome / Edge / Firefox / Safari).
   - The website will load immediately with all styling, icons, and image assets.

2. **Using VS Code Live Server (Optional)**:
   - Open the `personal-portfolio` folder in Visual Studio Code.
   - Install or enable the *Live Server* extension.
   - Right-click `index.html` and click **"Open with Live Server"**.

---

## 5. Basic HTML and CSS Concepts Used (Study Guide)

This section provides clear, simple explanations of the coding concepts used, making it easy to explain during interviews, presentations, or academic evaluations:

### A. Semantic HTML5 Tags
Instead of generic `<div>` containers everywhere, semantic elements describe their purpose to browsers and screen readers:
- `<header>`: Represents introductory content or navigational aids at the top of the page.
- `<nav>`: Encapsulates navigation links intended for site orientation.
- `<main>`: Contains the dominant, unique content of the document.
- `<section>`: Groups thematically related content (e.g., `#about`, `#education`, `#achievements`).
- `<article>`: Represents independent, self-contained units of content (e.g., individual achievement or education cards).
- `<footer>`: Defines the closing section containing copyright and author information.
- `<details>` and `<summary>`: Native HTML disclosure widget used here to build a 100% JavaScript-free mobile navigation toggle.

### B. Core CSS Layout Models
1. **Flexbox (`display: flex`)**:
   - Used for 1-dimensional alignment (along a row or a column).
   - Examples: Navbars, button rows (`gap`, `align-items: center`, `justify-content: space-between`).
2. **CSS Grid (`display: grid`)**:
   - Used for 2-dimensional layouts (rows and columns simultaneously).
   - Examples: The 4-column skills grid (`grid-template-columns: repeat(4, 1fr)`), the 3-column achievements grid, and the 2-column about layout.
3. **CSS Custom Properties (Variables)**:
   - Defined inside `:root` (e.g., `--color-navy-primary`, `--color-accent-gold`).
   - Enables centralized color theming and consistent spacing across the entire stylesheet.
4. **Smooth Scrolling**:
   - `scroll-behavior: smooth;` in `html` enables animated gliding between sections when anchor links are clicked.
   - `scroll-padding-top` ensures fixed/sticky navbars do not obscure section headers upon navigation.
5. **Transitions & Hover Effects**:
   - Subtle interactive feedback on buttons and cards using `transition: all 0.25s ease;` and `transform: translateY(-4px);`.
6. **Responsive Media Queries (`@media`)**:
   - Breakpoints at `1024px`, `768px`, and `480px` reorganize multi-column grids into single-column vertical stacks on mobile screens to prevent horizontal overflow.

---

## 6. Author

**Udit Khatri**  
- **Email**: [khatriudit1289@gmail.com](mailto:khatriudit1289@gmail.com)  
- **LinkedIn**: [linkedin.com/in/udit-khatri-73b508331](https://www.linkedin.com/in/udit-khatri-73b508331/)
