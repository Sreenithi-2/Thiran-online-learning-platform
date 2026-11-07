# THIRAN (திறன்) – Online Learning Platform
**Official Tagline: Learn. Grow. Shine.**

> Premier EdTech Platform designed for students to discover industry-vetted courses, develop practical capabilities, track learning progress, and earn verified certifications.

---

## 🌟 Brand Identity

- **Platform Name:** THIRAN
- **Tamil Name:** திறன் (Talent, Capability, Skill, Capacity)
- **Tagline:** *Learn. Grow. Shine.*
- **Official Color Palette:**
  - **Primary Teal:** `#087E8B`
  - **Secondary Teal:** `#14B8A6`
  - **Light Mint:** `#E9F7F5`
  - **Background:** `#F5FAF9`
  - **White:** `#FFFFFF`
  - **Main Text:** `#1F2937`
  - **Secondary Text:** `#64748B`
  - **Success:** `#16A34A`
- **Typography:** Poppins & Inter via Google Fonts, with Noto Sans Tamil for the Tamil script.

---

## 🚀 Key Features

1. **Eight Interconnected Pages:**
   - `index.html` – High-converting modern landing page with hero search, categories, featured/trending courses, instructors, testimonials, and why choose THIRAN.
   - `login.html` – Modern student sign-in with 1-click evaluator quick-fill, show/hide password, and error validation.
   - `register.html` – Comprehensive student registration with password strength meter and validation.
   - `courses.html` – Complete catalog with live search, category pills, level filters, price filters, and sorting.
   - `course-details.html` – Syllabus accordion, outcomes checklist, instructor bio, and instant enrollment.
   - `dashboard.html` – Responsive sidebar, 4 analytics cards, continue learning widget, weekly activity bar chart, and recent enrollments.
   - `my-learning.html` – Interactive Classroom player, curriculum sidebar, lesson notes, and completion recalculation.
   - `profile.html` – Student profile editor, avatar rotation, stats showcase, password changer, and demo data reset.

2. **Technology Stack:**
   - Pure **HTML5**, **CSS3**, and **Vanilla JavaScript** (No external frameworks like React/Vue).
   - LocalStorage data persistence for courses, enrollments, user session, notes, and theme.
   - Full dark/light mode toggle with smooth transitions.
   - Mobile-first responsive design for 320px, 375px, 425px, 768px, 1024px, and 1440px displays.

---

## 💻 Quick Start with VS Code Live Server

1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by *Ritwick Dey*) if not already installed.
3. Right-click `index.html` (or `THIRAN/index.html`) and click **"Open with Live Server"**.
4. The application will launch in your browser at `http://127.0.0.1:5500/THIRAN/index.html`.

### Default Demo Credentials for Evaluation
- **Email:** `karthik@thiran.edu`
- **Password:** `password123`
*(Or click the **"Auto Fill"** button on `login.html`)*

---

## 📁 Project Structure

```text
THIRAN/
├── index.html              # Home Landing Page
├── login.html              # Student Login Page
├── register.html           # Student Registration Page
├── courses.html            # Course Catalog Page
├── course-details.html     # Course Details & Syllabus Page
├── dashboard.html          # Student Analytics Dashboard
├── my-learning.html        # Interactive Classroom & Enrolled Courses
├── profile.html            # Student Profile & Settings Page
├── css/
│   ├── style.css           # Global Design System, Navbar, Footer, Toast
│   ├── auth.css            # Login & Register Split Layouts
│   ├── courses.css         # Catalog Grid & Course Details Page
│   └── dashboard.css       # Sidebar, Analytics Cards, Classroom Player
└── js/
    ├── storage.js          # LocalStorage Engine, 12 Courses Seed, Analytics
    ├── main.js             # Global Navbar, Theme Toggle, Mobile Drawer
    ├── auth.js             # Form Validations, Password Visibility
    ├── courses.js          # Catalog Filters, Live Search, Details & Enroll
    ├── dashboard.js        # Analytics Cards, Weekly Bar Chart, Profile Edit
    └── learning.js         # Classroom Video Player, Lesson Progress & Notes
```

---

## 📋 Comprehensive Testing Checklist

| Test Item | Expected Result | Status |
|---|---|---|
| **Theme Toggle** | Switches between light and dark mode across all 8 pages | ✅ Verified |
| **Mobile Drawer** | Hamburger menu opens and closes smoothly with backdrop click | ✅ Verified |
| **Catalog Search** | Filters courses in real-time by title, topic, or instructor | ✅ Verified |
| **Category Filter** | Filters catalog by Web Dev, AI, Data Science, Python, etc. | ✅ Verified |
| **Course Details** | Dynamically loads course data via `?id=...`, accordion expands | ✅ Verified |
| **Enrollment Action** | Adds course to user's LocalStorage and directs to classroom | ✅ Verified |
| **Classroom Player** | Video playback controls, previous/next lesson switching | ✅ Verified |
| **Lesson Completion** | Progress percentage updates immediately and persists | ✅ Verified |
| **Profile Update** | Updates name, phone, bio, and changes avatar | ✅ Verified |
| **Responsive Layout** | Flawless display from 320px mobile to 1440px desktop | ✅ Verified |
