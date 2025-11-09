# Portfolio Website Customization Guide

This guide will help you personalize this portfolio template for your own use.

## 🔧 Quick Customization Checklist

### 1. **Personal Information** (Update in `index.html`)

- [ ] **Name**: Replace "Varad Bhogayata" with your name throughout the file
- [ ] **Title/Job Role**: Replace "Software Developer" with your title
- [ ] **Profile Image**: Replace `/assets/img/passport-new.jpg` with your profile photo path
- [ ] **Email**: Replace `vbhogayata@gmail.com` with your email
- [ ] **Phone**: Replace `+14805722456` with your phone number (optional)
- [ ] **Resume**: Update the resume link to point to your resume PDF

### 2. **Social Media Links** (Update in `index.html`)

- [ ] **LinkedIn**: Update all LinkedIn profile URLs
- [ ] **GitHub**: Update all GitHub profile URLs  
- [ ] **Twitter**: Update Twitter handle (if applicable)
- [ ] Remove or add other social media links as needed

### 3. **SEO & Analytics** (Update in `index.html` - HEAD section)

- [ ] **Google Tag Manager**: Remove or replace `GTM-PGZH8HT` with your GTM ID
- [ ] **Google Analytics**: Remove or replace `UA-126939217-2` with your GA tracking ID
- [ ] **Google Site Verification**: Remove or replace with your verification code
- [ ] **Meta Tags**: Update Open Graph and Twitter meta tags with your info
- [ ] **Page Title**: Update `<title>` tag
- [ ] **OG Image**: Update the preview image URL for social sharing

### 4. **Content Sections** (Update in `index.html`)

#### About Section (`#about`)
- [ ] Update personal bio/description
- [ ] Update skills list (Languages, Databases, Libraries, Frameworks, Tools)
- [ ] Update current focus/interests

#### Experience Section (`#experience`)
- [ ] Replace all job experiences with your own
- [ ] Update company names, logos, dates, and descriptions
- [ ] Add or remove experience entries as needed

#### Projects Section (`#projects`)
- [ ] Replace all projects with your own
- [ ] Update project images, titles, descriptions, and links
- [ ] Add or remove project entries as needed

#### Skills Section (`#skills`)
- [ ] Update skill categories and items
- [ ] Replace skill images/logos if needed

#### Education Section (`#education`)
- [ ] Update school/university names
- [ ] Update degree information and dates
- [ ] Update relevant coursework
- [ ] Add or remove education entries as needed

#### Contact Section (`#contact`)
- [ ] Verify all contact information is correct
- [ ] Update all social media links

### 5. **Typing Animation** (Update in `index.html` - near end of file)

- [ ] Update the typing animation strings array:
  ```javascript
  strings: ["Pythonist", "Developer", "Fast Learner"]
  ```
  Replace with your own descriptors.

### 6. **Images & Assets**

- [ ] Replace profile picture at `/assets/img/passport-new.jpg`
- [ ] Replace company logos in `/assets/img/` directory
- [ ] Replace project images in `/assets/img/` directory
- [ ] Update favicon files in `/assets/img/favicon/` directory

### 7. **Repository Settings** (for GitHub Pages)

- [ ] Ensure your repository is named `<your-username>.github.io`
- [ ] Enable GitHub Pages in repository settings
- [ ] Update all GitHub URLs to match your username

### 8. **Optional Customizations**

- [ ] Update color scheme in `assets/css/style.css` if desired
- [ ] Update fonts if desired
- [ ] Add additional sections if needed
- [ ] Update README.md with your information

## 📝 Step-by-Step Instructions

### Step 1: Basic Personal Information
Open `index.html` and use Find & Replace (Ctrl+H) to replace:
- `Varad Bhogayata` → `Your Name`
- `varadbhogayata` → `yourusername` (for URLs)
- `vbhogayata@gmail.com` → `your-email@example.com`

### Step 2: Remove/Comment Out Analytics
Since you're using this as a template, you likely don't have the same analytics IDs:
1. Comment out or remove the Google Tag Manager script
2. Comment out or remove the Google Analytics script
3. Remove the Google Site Verification meta tag

### Step 3: Update Social Links
Search for social media links and update them:
- LinkedIn: Search for `linkedin.com/in/` and update
- GitHub: Already set to `github.com/rexorth/` - verify this is correct
- Twitter: Update or remove if not using

### Step 4: Content Updates
Go through each section and update with your own:
- About section: Your bio and skills
- Experience: Your work history
- Projects: Your projects
- Education: Your education history

### Step 5: Test Locally
Open `index.html` in a browser to preview your changes before deploying.

### Step 6: Deploy
Push your changes to your GitHub repository. GitHub Pages will automatically update your site.

## 🎨 Color Customization (Optional)

The main color scheme uses teal (`#004d40`, `#00796b`). To change colors:
1. Open `assets/css/style.css`
2. Search for color codes and replace them
3. Common colors to update:
   - `#004d40` (dark teal)
   - `#00796b` (teal)
   - `#009688` (lighter teal)

## 📸 Image Requirements

- **Profile Picture**: Recommended size: 400x400px or larger, square format
- **Project Images**: Recommended size: 800x600px or similar aspect ratio
- **Company Logos**: Recommended size: 200x200px, transparent background preferred

## ⚠️ Important Notes

1. **Analytics**: If you want to use Google Analytics, you'll need to:
   - Create a Google Analytics account
   - Get your tracking ID
   - Replace the placeholder in the code

2. **Favicon**: Update all favicon files if you want a custom icon

3. **Resume**: Make sure your resume PDF is accessible at the path specified

4. **Testing**: Always test your site after making changes, especially:
   - All links work correctly
   - Images load properly
   - Mobile responsiveness
   - Contact form functionality (if added)

## 🚀 Deployment Checklist

Before deploying:
- [ ] All personal information updated
- [ ] All links tested and working
- [ ] All images uploaded and paths correct
- [ ] Analytics IDs removed or updated
- [ ] Resume link working
- [ ] Mobile view tested
- [ ] README.md updated (optional)

---

Good luck with your portfolio! 🎉

