# Kavita Teja - Personal Portfolio Website

A modern, responsive, and elegant single-page portfolio website built for **Kavita Teja**, a Certified Nail & SPMU (Semi-Permanent Makeup) Educator and Beauty Trainer. The website features a sleek "Glassmorphism" dark-mode UI, smooth animations, and interactive navigation.

---

## 🚀 Key Features

- **Modern Glassmorphism UI:** Built with dark theme aesthetics (`#080c13`), gradient backgrounds, glowing ambient orbs, and frosted glass cards (`backdrop-filter`).
- **Fully Responsive Design:** Optimized for mobile phones, tablets, and desktop screens using CSS Media Queries and flexible grids.
- **Custom Font Support:** Uses local custom TrueType fonts (`Poppins-Regular` and `Poppins-SemiBold`).
- **Interactive Navigation:** Fixed top navbar with a dynamic **ScrollSpy** feature that automatically highlights the active section link as the user scrolls.
- **Animated Hero Section:** Features a custom glowing, shaking hexagon frame (`hex-wrapper`) showcasing the profile image.
- **Security Protections:** Built-in JavaScript restrictions to disable right-click context menu, Inspect Element (F12, Ctrl+Shift+I/C/J), and View Source (Ctrl+U).

---

## 🛠️ Built With

- **HTML5:** Semantic markup structure.
- **CSS3:** Advanced styling including Flexbox, CSS Grid, `@keyframes` animations, and CSS variables.
- **JavaScript (Vanilla):** Dynamic scroll-spy, smooth navigation scrolling, and DOM event restrictions.

---

## 📂 Section Breakdown

1. **Navigation Bar (`<nav>`):** 
   - Logo with initials ("KT") that scrolls back to the top when clicked.
   - Quick links to all major sections of the portfolio.

2. **Hero Section (`#home`):**
   - Introduction with title, profession subtitle, and a professional summary box.
   - Animated glowing hexagon image container for the profile picture.

3. **Introduction (`#About`):**
   - Detailed professional background, passion for teaching, and teaching philosophy.

4. **Journey (`#journey`):**
   - Step-by-step career milestones (from Nail Artist to Certified Educator and continuous learning).

5. **Certifications (`#certifications`):**
   - Highlighted list of professional certifications (Nail Educator, SPMU Educator, Advanced Nail Art, PMU, etc.).

6. **Expertise (`#expertise`):**
   - Grid layout showcasing specific skills like Nail Extensions, Russian Manicure, Microblading, Ombre Brows, etc.

7. **Training & Experience (`#experience`):**
   - Two-column layout detailing Professional Training (Academies) and Work Experience (with active employment badges and outbound links).

8. **Education (`#education`):**
   - Academic qualifications ranging from CBSE 10th/12th to Bachelor of Arts and Master in Cosmetology (MIC).

9. **Training & Workshops (`#training`):**
   - Visual gallery showcasing student practices, workshops, and live demonstrations with hover zoom effects and captions.

---

## ⚙️ JavaScript Functionality

- **Smooth Scrolling:** Intercepts anchor clicks and smoothly scrolls to the target section with an offset for the fixed navbar.
- **ScrollSpy:** Listens to window scroll events to dynamically update the `.active` class on navigation links based on the user's current viewport position.
- **Content Protection:** 
  - Disables right-click (`contextmenu`).
  - Blocks developer shortcut keys (`F12`, `Ctrl+Shift+I/C/J`, `Ctrl+U`).

---

## 💻 How to Run Locally

1. Clone or download this repository into a local folder.
2. Ensure you have the following assets in the same directory:
   - Font files: `Poppins-Regular.ttf`, `Poppins-SemiBold.ttf`
   - Profile image: `kavitaTeja.jpeg`
   - Gallery images: `studentPractice.jpeg`, `workshops.jpeg`, `demo.jpeg`
3. Double-click on `index.html` to open and view the website in any modern web browser.
