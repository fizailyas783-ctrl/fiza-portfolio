# Fiza Ilyas - Portfolio Website

A modern, professional portfolio website for Fiza Ilyas, an aspiring Data Analyst and BS Mathematics final semester student.

## 🌟 Features

- **Modern Dark Purple Theme**: Elegant black and purple color scheme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects, hover transitions, and scroll animations
- **Professional Design**: Clean, recruiter-ready layout
- **Interactive Skills Section**: Animated progress bars
- **Contact Form**: Beautiful UI-only contact form
- **Mobile Navigation**: Responsive hamburger menu
- **GitHub Pages Ready**: Fully compatible with GitHub Pages hosting

## 🎨 Design Specifications

### Color Theme
- Background: `#0B0B0F` (Dark Black)
- Section Background: `#12121A` (Dark Gray)
- Primary Purple: `#7C3AED`
- Light Purple: `#A78BFA`
- Text: `#E5E7EB`
- Headings: `#C4B5FD`

### Typography
- **Headings**: Poppins (600-700 weight)
- **Body**: Inter (400-500 weight)
- **Font Sizes**: H1: 44px, H2: 30px, H3: 22px, Body: 16px

### Sections
1. **Hero Section** - Introduction with profile image and CTA buttons
2. **About Me** - Professional background and aspirations
3. **Skills** - Technical and soft skills with progress bars
4. **Education** - Academic qualifications with auto-calculated grades
5. **Contact** - Contact information and form

## 📁 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Complete CSS styling
├── script.js           # JavaScript functionality
├── README.md           # Documentation (this file)
│
├── profile.jpg         # Profile image (to be added)
└── Fiza_CV.pdf        # CV file (to be added)
```

## 🚀 GitHub Pages Deployment

### Step 1: Prepare Your Files

1. Create a new folder on your computer called `portfolio`
2. Add all files to this folder:
   - `index.html`
   - `style.css`
   - `script.js`
   - `profile.jpg` (your profile image)
   - `Fiza_CV.pdf` (your CV/resume)

### Step 2: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in (create an account if needed)
2. Click the **"+"** icon in the top right and select **"New repository"**
3. Name your repository: `portfolio` (or any name you prefer)
4. Set it to **Public**
5. Click **"Create repository"**

### Step 3: Upload Files to GitHub

**Option A: Using GitHub Web Interface (Easiest)**

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop all your files (HTML, CSS, JS, images, PDF)
3. Add a commit message: "Initial commit"
4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Navigate to your portfolio folder
cd path/to/portfolio

# Initialize git
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit"

# Add remote repository (replace USERNAME with your GitHub username)
git remote add origin https://github.com/USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (top right)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 5: Access Your Website

Your website will be available at:
```
https://USERNAME.github.io/portfolio/
```

Replace `USERNAME` with your GitHub username.

## 📝 Customization Guide

### Update Profile Image
1. Replace `profile.jpg` with your own photo
2. Recommended size: 500x500px or larger (square)
3. Keep the filename as `profile.jpg` or update in HTML

### Update CV/Resume
1. Replace `Fiza_CV.pdf` with your CV
2. Keep the filename or update the download link in HTML:
```html
<a href="YOUR_CV_FILENAME.pdf" download="Fiza_Ilyas_CV.pdf">
```

### Modify Content
- **Personal Info**: Edit text in `index.html`
- **Skills**: Update skill names and percentages in HTML
- **Colors**: Change CSS variables in `style.css` `:root` section
- **Education**: Update degrees and grades in HTML

### Add Your Contact Links
Update these sections in `index.html`:
```html
<a href="mailto:YOUR_EMAIL@gmail.com">
<a href="tel:+92YOUR_PHONE">
<a href="YOUR_LINKEDIN_URL">
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **JavaScript (Vanilla)**: Interactive features
- **Google Fonts**: Poppins and Inter

## ✨ Features Breakdown

### Animations
- Fade-in on scroll
- Smooth hover effects
- Progress bar animations
- Mobile menu transitions

### Responsive Design
- Mobile-first approach
- Breakpoints: 968px, 768px, 480px
- Flexible grid layouts
- Touch-friendly navigation

### Accessibility
- Semantic HTML5
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Profile Image Not Showing
- Ensure `profile.jpg` is in the same folder as `index.html`
- Check file name spelling (case-sensitive)
- Try a different image format (PNG, JPG)

### CV Download Not Working
- Ensure `Fiza_CV.pdf` is uploaded to GitHub
- Check the file path in the HTML
- Clear browser cache

### Website Not Appearing on GitHub Pages
- Wait 2-5 minutes after enabling Pages
- Check repository is set to Public
- Ensure `index.html` is in the root folder
- Check Settings > Pages for error messages

### Animations Not Working
- Clear browser cache (Ctrl+F5)
- Ensure JavaScript is enabled
- Check browser console for errors (F12)

## 📧 Support

For issues or questions:
- Email: fizailyas783@gmail.com
- LinkedIn: [Fiza Ilyas](https://www.linkedin.com/in/fiza-ilyas-7b0b082a6)

## 📄 License

This portfolio template is free to use and modify for personal use.

---

**Built with 💜 by Fiza Ilyas**

*Last Updated: February 2024*
