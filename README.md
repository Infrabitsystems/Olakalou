# Ol Kalou Technical and Vocational College (TVC) Website

This is a modern, responsive, and fully functional front-end website for Ol Kalou TVC, designed to reflect a professional Kenyan TVET institution. It focuses on accessibility, clarity, student engagement, and fast performance.

## 🧱 File Structure

```
olk/
├── index.html           # Homepage (Hero, Highlights, Featured Courses, Announcements)
├── about.html           # About Us (History, Vision, Mission, Core Values, Leadership)
├── courses.html         # Courses/Programs with JS filtering
├── admissions.html      # Admissions info and online application form
├── student-life.html    # Facilities, Clubs, and Gallery
├── contact.html         # Contact information, map, and inquiry form
├── css/
│   └── style.css        # Main stylesheet (Vanilla CSS, custom properties, responsive design)
└── js/
    └── main.js          # Core functionality (Mobile nav, sticky header, course filtering)
```

## 🎨 Design System

- **Primary Color:** Navy Blue (`#0f3057`)
- **Secondary Color:** Bright Blue (`#0088cc`)
- **Accent Color:** Vibrant Orange (`#ff7b00`)
- **Typography:** 'Poppins' (Headings) and 'Inter' (Body content)
- **Icons:** FontAwesome 6

## 🚀 Deployment Instructions

Since this is a lightweight, static frontend built with pure HTML, CSS, and JavaScript, it can be deployed quickly and easily on any static web hosting provider. 

### Option 1: Hostinger / cPanel (Common for Kenyan Institutions)
1. Purchase a domain name (e.g., `olkaloutvc.ac.ke`) and a web hosting package.
2. Log into your cPanel dashboard.
3. Open the **File Manager** and navigate to the `public_html` directory.
4. Upload all the files and folders from this project directly into `public_html`.
5. Your website is now live!

### Option 2: GitHub Pages (Free, great for testing)
1. Create a new repository on GitHub.
2. Upload the contents of this project to the repository.
3. Go to the repository **Settings** > **Pages**.
4. Select the `main` branch as the source and click Save.
5. GitHub will provide you with a live URL to access the site.

### Option 3: Netlify / Vercel
1. Create a free account on [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/).
2. Drag and drop the `olk` project folder into their deployment area, OR link your GitHub repository.
3. The site will deploy instantly and provide you with a live URL.

## 🔧 Future Integrations (Backend)

To make the contact form and online application form functional:
1. **PHP (cPanel approach):** You can change the forms' `action` attributes to point to a simple `process.php` script that sends emails using the `mail()` function or PHPMailer.
2. **Formspree / Web3Forms:** An easier alternative is to use a free service like [Web3Forms](https://web3forms.com/). Just replace the form `action` URL with the one they provide, and you'll receive form submissions directly to your email without writing backend code.
