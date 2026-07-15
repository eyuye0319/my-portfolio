# Premium 2026 Developer Portfolio

A responsive, high-end, futuristic personal portfolio website designed for **Wubgzer Alemayehu** using a sleek **Glassmorphic Dark Space** theme.

Built using only **HTML5**, **CSS3**, and **Bootstrap 5**.

---

## 📁 Project Directory Structure

```text
Portfolio/
│
├── index.html           # Main HTML5 document (structure & content)
│
├── css/
│     ├── style.css      # Custom styles, animations, and typography pairings
│     └── responsive.css # Media query definitions for mobile/tablet optimization
│
├── images/
│     ├── image.jpg     # My professional profile photo
│     ├── hero-bg.jpg    # Main background graphics
│     ├── project1.jpg   # Travel Booking System thumbnail
│     ├── project2.jpg   # Knowledge Management System thumbnail
│     └── project3.jpg   # Cafe Mobile App thumbnail
│
├── assets/
│     └── cv.pdf         # Downloadable curriculum vitae / resume
│
└── README.md            # Project instruction guide & notes
```

---

## 🎨 Premium Style Guide

- **Background:** `#050816` (Deep space cosmic tone)
- **Cards & Backdrops:** `#111827` with `backdrop-filter: blur(16px)` and a thin subtle border `rgba(255,255,255,0.08)`
- **Primary Accent:** `#00E5FF` (Electric glowing cyan)
- **Secondary Accent:** `#7C3AED` (Royal neon purple)
- **Sub-Accents:** `#38BDF8` (Sky blue)
- **Typography:**
  - Headings & Logos: **Space Grotesk** (Futuristic sans-serif)
  - General UI & Copy: **Inter** (Clean Swiss sans-serif)
  - Accent / Badges: **Poppins** (Symmetrical geometric font)

---

## 🚀 Customization Guide (How to Edit in VS Code)

All information is stored directly inside semantic, well-commented HTML elements so you can edit it in seconds.

### 1. Edit Your Name, Biography, or Links
Open `index.html` in VS Code, and search for the text you want to change:
- **Logo Name:** Search for `ALEMAYEHU` (approx. line 22).
- **Biography Paragraph:** Search for the `<p id="aboutBio">` block (approx. line 118) and replace it with your custom story.
- **Email Link:** Search for `wubgzeralemayehu18@gmail.com` and change the text and the `href="mailto:..."` attribute.

### 2. Update Your Skills & Progress Indicators
In `index.html`, locate the `#skills` section (approx. line 161). 
- To edit the progress level bar, modify the `style="width: XX%;"` inline attribute of the inner `.progress-custom-fill` div. For example, to set skill level to 100%, update:
  ```html
  <div class="progress-custom-fill" style="width: 100%;"></div>
  ```
- Change the badge titles and add custom icons from **FontAwesome 6** or **Bootstrap Icons**.

### 3. Replace Placeholder Images with Your Own
The HTML currently uses high-resolution Unsplash URLs to guarantee that your online preview renders beautifully out of the box. To transition to your offline local copies:
1. Drag and drop your images into the `images/` directory.
2. Ensure they are named `profile.jpg`, `project1.jpg`, etc.
3. In `index.html`, swap the online `src="..."` URLs with the relative local paths:
   ```html
   <!-- For Profile -->
   <img src="images/profile.jpg" alt="Wubgzer Alemayehu" class="about-img">

   <!-- For Projects -->
   <img src="images/project1.jpg" alt="Travel Booking System" class="project-img">
   ```

### 4. Upload Your CV / Resume
- Rename your PDF resume file to `cv.pdf`.
- Drop it into the `assets/` folder, replacing the empty placeholder.
- Clicking the "Download CV" button will automatically download your new PDF!

---

## ⚡ Key Features

- **Pure CSS Subtitle Slider:** Dynamic auto-sliding typography slider displaying your titles (Software Engineer, AI Enthusiast, Cybersecurity Researcher, Full Stack Developer) with zero Javascript load overhead.
- **Glassmorphic Grid Cards:** Modern visual card design with custom glows, thin glassy borders, and responsive mouse hover translations.
- **Fully Responsive Matrix:** Fluid columns that shift seamlessly from 3-column desktop layouts to single-column phone screens, completely eliminating horizontal scrolls.
- **Pure CSS Glowing Orb Illustration:** Abstract neural illustration that rotates and floats using CSS `@keyframes` only.

---

Designed with care by **Wubgzer Alemayehu** &bull; © 2026.
