# Nyashadzashe Chivaviro - Profile and mini portifolio
A semantic HTML5 profile and mini-portifolio built for the Web technologies(CIS2103) Practical assignment
## Part C - AI prompt log
### 1. Exact Prompt
>"Act as a web developer portifolio copywriter.Write a concise, 3 sentence 'About me' bio for Nyashadzashe Chivaviro, a second-year Computer Information Systems interested in web development and AI."
### 2. AI Raw Output
> "Nyashadzashe Chivaviro is a dedicated Computer Information Systems student with a passion for building dynamic web applications.Driven by motivation, Nyasha explores the intersection of AI and web technologies to create seamless digital experiences. Always eager to learn, Nyasha is building a strong foundation in modern software development."
### 3. Final Edited Version 
>"I am Nyashadzashe Chivaviro, a second-year Computer Information Systems student passionate about web development and AI-assisted UI design.I enjoy creating accessible, semantic web projects and exploring modern frameworks.My focus is on writing clean code that delivers intuitive user experiences."
### 4. Reflection 
I adjusted the AI output from third-person to first person ("I am") to make it feel more authentic and personal for my portifolio page. I also refined the technical terms to explicitly highlight semantic HTML and UI design to align with our current coursework.
## Part D - Accessibility Review & Fixes 
* **Image Accessibility:** Added descriptive 'alt' text to all image elements to ensure compatibility with screen readers.
* **Form labels and Inputs:** Explicitly associated every form '<label> with its corresponding '<input> using matching 'for' and 'id' attributes.
* **Peer Review Feedback:** During Thursdays peer review, it was noted that button text colour contrast needed improvement.
* **Fix Applied:** Updated the submit button styles to ensure high contrast against the background for better readability.
## Part F - Responsive Notes & Testing

### Breakpoints Tested
* **Mobile (375px):** Verified clean layout without horizontal scrolling in DevTools.
* **Tablet (768px):** Navigation and forms adjust gracefully for medium screens.
* **Desktop (1280px):** Page content centers neatly with a maximum container width.

### Flexbox & Grid Implementation
* **Flexbox:** Used in the `#skills` list (`display: flex`, `flex-wrap: wrap`, `gap: 12px`) to render skill tags inline cleanly.
* **CSS Grid:** Used in `#projects` (`grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`) to dynamically scale project card columns using `fr` units.

### Tailwind Utility & Custom CSS Split
* **Tailwind Sections:** Applied to `<header>` and `<form>` (`#contact`) for fast responsive layout tweaks and hover states.
* **Custom CSS:** Written in `style.css` for global box model defaults, custom Flexbox lists, CSS Grid layouts, and custom `@media` queries.