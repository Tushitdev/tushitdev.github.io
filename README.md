# Tushit Dev Maheshkumar - Portfolio Website

A professional portfolio website showcasing my experience, skills, and projects as a Quality Engineer and Industrial Engineering professional.

## 🚀 Live Demo

Visit the live website: [https://tushitdev.github.io](https://tushitdev.github.io) *(replace with your actual GitHub username)*

## 📋 About

This portfolio website features:
- Professional experience in Quality Engineering and Industrial Engineering
- Technical skills and certifications
- Project showcase with detailed descriptions
- Educational background
- Contact information and form

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript** - Interactive features and animations
- **Font Awesome** - Icons
- **Responsive Design** - Mobile-first approach

## 📦 Features

- ✅ Fully responsive design (desktop, tablet, mobile)
- ✅ Smooth scrolling navigation
- ✅ Animated sections on scroll
- ✅ Interactive project cards
- ✅ Contact form with email integration
- ✅ Professional timeline for experience
- ✅ Modern gradient designs
- ✅ SEO optimized

## 🚀 Deployment to GitHub Pages

Follow these steps to deploy your portfolio to GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top-right corner
3. Select **"New repository"**
4. Name your repository: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is `tushitdev`, name it `tushitdev.github.io`
5. Make sure the repository is **Public**
6. Click **"Create repository"**

### Step 2: Upload Your Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Scroll down and click **"Commit changes"**

#### Option B: Using Git Command Line

```bash
# Navigate to your portfolio directory
cd /Users/DEV

# Initialize git repository
git init

# Add all files
git add index.html styles.css script.js README.md

# Commit the files
git commit -m "Initial portfolio website commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"main"** branch
5. Click **"Save"**
6. Wait 1-2 minutes for deployment

### Step 4: Access Your Website

Your website will be live at: `https://your-username.github.io`

For example: `https://tushitdev.github.io`

## 🎨 Customization Guide

### Update Personal Information

1. **Contact Details** - Edit the contact section in `index.html`:
   ```html
   <a href="mailto:your-email@gmail.com">your-email@gmail.com</a>
   <a href="tel:+1234567890">+1 234-567-0890</a>
   ```

2. **LinkedIn & GitHub Links** - Update in the contact and footer sections:
   ```html
   <a href="https://www.linkedin.com/in/your-profile">LinkedIn</a>
   <a href="https://github.com/your-username">GitHub</a>
   ```

3. **Experience & Projects** - Modify the content in respective sections

### Change Color Scheme

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;  /* Change primary color */
    --secondary-color: #1e40af; /* Change secondary color */
    --accent-color: #3b82f6;    /* Change accent color */
}
```

### Add Your Photo

Replace the profile placeholder in `index.html`:

```html
<div class="profile-placeholder">
    <i class="fas fa-user-tie"></i>
</div>
```

With:

```html
<img src="your-photo.jpg" alt="Tushit Dev" style="width: 250px; height: 250px; border-radius: 50%; object-fit: cover;">
```

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📧 Contact Form Setup

The contact form currently uses `mailto:` links. For production use, consider integrating:

- [Formspree](https://formspree.io/) - Free form backend
- [Netlify Forms](https://www.netlify.com/products/forms/) - If hosting on Netlify
- [EmailJS](https://www.emailjs.com/) - JavaScript email service

## 🔧 Local Development

To run locally:

1. Clone or download the repository
2. Open `index.html` in your web browser
3. Or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Then visit http://localhost:8000
```

## 📄 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
└── README.md          # Documentation
```

## 🎯 Future Enhancements

- [ ] Add blog section
- [ ] Implement dark mode toggle
- [ ] Add more project details with images
- [ ] Integrate analytics
- [ ] Add testimonials section
- [ ] Create downloadable resume PDF

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Tushit Dev Maheshkumar**

- Email: tushitdev1582@gmail.com
- Phone: +1 248-417-0323
- LinkedIn: [linkedin.com/in/tushit-dev](https://www.linkedin.com/in/tushit-dev)
- Location: Michigan, USA

## 🙏 Acknowledgments

- Design inspiration from modern portfolio websites
- Icons by [Font Awesome](https://fontawesome.com/)
- Reference website: [Santhakumar Ramesh Portfolio](https://santhakumarramesh.github.io)

---

⭐ If you like this portfolio template, please give it a star on GitHub!

**Made with ❤️ and Industrial Engineering Excellence**

