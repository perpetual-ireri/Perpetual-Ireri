# Perpetual Ireri – IT Infrastructure & Digital Innovation Specialist

![Profile Banner](assets/Ireri.jpeg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-perpetual--ireri.com-4169E1)](https://perpetual-ireri.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/perpetual-ireri-6b8aab247)

---

## 👋 About This Project

Welcome to the official repository of **Perpetual Ireri** — a modern, fully responsive personal portfolio website showcasing expertise in:

- IT Infrastructure & Networking  
- Web Development  
- UX/UI Design  
- Digital Marketing & Growth Systems  

Built using **HTML, CSS, and JavaScript**, this website combines a sleek dark theme with royal blue accents and interactive elements to deliver a powerful, professional online presence.

---

## ✨ Features

- 🌙 **Dark Theme Design** – Elegant dark UI with royal blue accents  
- 📱 **Fully Responsive** – Optimized for mobile, tablet, and desktop  
- ⚙️ **Interactive Preloader** – Smooth animated loading screen  
- ⌨️ **Typing Effect Hero Section** – Dynamic animated headline  
- 🧩 **Services & Pricing Sections** – Structured tiered offerings  
- 🏷️ **Skills Tags** – Visual display of technical expertise  
- 🖼️ **Portfolio Grid** – Live project showcase  
- 💬 **Testimonial Carousel** – Auto-rotating with manual navigation  
- 📊 **Animated Counters** – Scroll-triggered statistics  
- 📧 **Contact Form with EmailJS** – Sends emails without backend  
- 🔔 **Toast Notifications** – Submission feedback alerts  
- 🔎 **SEO Optimized** – Meta tags, Open Graph & favicon included  

---

## 🛠️ Technologies Used

- **HTML5** – Semantic structure  
- **CSS3** – Variables, Flexbox, Grid, animations  
- **JavaScript (ES6)** – DOM manipulation & interactivity  
- **EmailJS** – Serverless email functionality  
- **Font Awesome** – Icons  
- **Google Fonts (Poppins)** – Typography  

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Optional: Local development server (e.g., Live Server in VS Code)

---

### Installation

1. Clone the repository:

```bash
git clone https://github.com/perpetual-ireri/perpetual-ireri-portfolio.git
```

2. Navigate into the project folder:

```bash
cd perpetual-ireri-portfolio
```

3. Open `index.html` in your browser.

For best results, use a local server:
- In VS Code → Right-click `index.html`
- Select **Open with Live Server**

---

## ⚙️ EmailJS Configuration

The contact form uses **EmailJS** to send messages without a backend.

### Setup Steps

1. Create a free account at https://www.emailjs.com  
2. Create an Email Service (Gmail, Outlook, etc.)  
3. Create two templates:

   **1. Owner Notification Template**
   - Variables: `{{name}}`, `{{email}}`, `{{title}}`, `{{message}}`

   **2. Auto-Reply Template**
   - Set "To Email" field to `{{email}}`
   - Include a professional thank-you message

4. Update the constants inside `index.html`:

```javascript
const SERVICE_ID = "your_service_id";
const OWNER_TEMPLATE_ID = "your_owner_template_id";
const AUTO_REPLY_TEMPLATE_ID = "your_autoreply_template_id";

emailjs.init("your_public_key");
```

5. Replace with your actual EmailJS credentials.

---

## 🎨 Customization Guide

### Update Personal Details
Edit:
- Name
- Bio
- Contact details
- Social links

### Replace Profile Image
Replace:
```
assets/Ireri.jpeg
```

### Modify Projects
Update:
- Portfolio card titles
- Descriptions
- Project URLs

### Change Branding Colors
Edit CSS variables inside:

```css
:root {
  --royal: #4169E1;
  --dark-bg: #0b1120;
}
```

### Replace Favicon
Current favicon uses SVG gear emoji.
You may replace it with a branded icon.

---

## 📦 Deployment

This is a static website and can be deployed easily.

### Option 1: GitHub Pages

1. Push to GitHub
2. Go to **Settings → Pages**
3. Select branch (`main`)
4. Save

Your site will be live at:

```
https://yourusername.github.io/repository-name/
```

---

### Option 2: Netlify / Vercel

- Drag and drop the project folder  
OR  
- Connect your GitHub repository  

Deployment is automatic.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for more details.

---

## 📬 Contact

- 📧 Email: perpetualwairimu74@gmail.com  
- 🔗 LinkedIn: https://www.linkedin.com/in/perpetual-ireri-6b8aab247  
- 💻 GitHub: https://github.com/perpetual-ireri  
- 🌐 Website: https://perpetual-ireri.com  

---

## 💡 Vision

To build secure digital infrastructures, scalable platforms, and intelligent systems that empower businesses to operate confidently and grow sustainably.

---

© 2026 Perpetual Ireri – IT Infrastructure & Digital Innovation Specialist