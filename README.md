 # NNPC AI Training Timetable - Jake Riley Academy

## 📋 Project Overview

This is a professional HTML timetable for the **5-Day AI Training Program for KRPC Staff**, organized by Jake Riley Academy and NNPC Academy.

**Training Details:**
- **Dates:** October 27-31, 2025
- **Venue:** Jake Riley Academy Office, Abuja
- **Trainer:** Suleiman Shaibu
- **Participants:** 20 Middle Managers & Operators

---

## 📦 **Two Versions Available**

### 1. **Desktop Version** (Standalone HTML)
- **File:** `NNPC_AI_Training_Timetable_Desktop.html`
- **Usage:** Open directly in any web browser
- **Features:** 
  - All CSS embedded in the HTML file
  - Works offline
  - No dependencies required
  - Ready to use immediately

### 2. **Vercel Version** (For Web Hosting)
- **Folder:** `vercel-version/`
- **Files:**
  - `index.html` - Main HTML file
  - `styles.css` - Separate CSS file
  - `vercel.json` - Vercel configuration
  - `README.md` - This file
- **Features:**
  - Optimized for web deployment
  - SEO-ready with meta tags
  - Separated CSS for better caching
  - Responsive design

---

## 🚀 **Deployment to Vercel**

### **Prerequisites:**
1. A GitHub account
2. A Vercel account (free) - Sign up at [vercel.com](https://vercel.com)

### **Step-by-Step Deployment:**

#### **Step 1: Push to GitHub**

1. **Initialize Git in your repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - NNPC AI Training Timetable"
   ```

2. **Create a new repository on GitHub:**
   - Go to [github.com](https://github.com)
   - Click "New repository"
   - Name it (e.g., `nnpc-ai-training-timetable`)
   - Don't initialize with README (you already have files)
   - Click "Create repository"

3. **Push your code:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

#### **Step 2: Deploy to Vercel**

##### **Option A: Using Vercel Dashboard (Easiest)**

1. Go to [vercel.com/dashboard](https://vercel.com/dashboard)
2. Click "Add New" → "Project"
3. Import your GitHub repository
4. Vercel will auto-detect settings
5. Click "Deploy"
6. Done! Your site will be live at `https://your-project-name.vercel.app`

##### **Option B: Using Vercel CLI**

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy from the vercel-version folder:**
   ```bash
   cd vercel-version
   vercel
   ```

4. **Follow the prompts:**
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - Project name? (press Enter for default)
   - Directory? **.**
   - Want to modify settings? **N**

5. **Your site is now live!** Vercel will provide a URL.

#### **Step 3: Custom Domain (Optional)**

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow DNS configuration instructions

---

## 🖥️ **Using the Desktop Version**

1. Open `NNPC_AI_Training_Timetable_Desktop.html` in any browser
2. No installation required
3. Works offline
4. Print-ready (Ctrl+P or Cmd+P)

---

## 📁 **File Structure**

```
├── NNPC_AI_Training_Timetable_Desktop.html  (Standalone version)
├── vercel-version/
│   ├── index.html              (Web version HTML)
│   ├── styles.css              (Separated CSS)
│   ├── vercel.json             (Vercel config)
│   └── README.md               (This file)
```

---

## 🎨 **Features**

✅ **Professional Design**
- Color-coded learning outcomes (Knowledge, Skills, Attitudes, Actions)
- Clean, modern layout with proper spacing
- Jake Riley and NNPC Academy logos

✅ **Complete 5-Day Schedule**
- Day 1: AI Fundamentals, Ethics & Personal Productivity
- Day 2: Advanced AI Tools & Prompt Engineering
- Day 3: AI in Refinery Operations
- Day 4: Collaboration & Implementation
- Day 5: Capstone Project & Wrap-Up

✅ **Responsive Design**
- Works on desktop, tablet, and mobile
- Print-friendly styling
- Optimized for all screen sizes

✅ **SEO Optimized**
- Proper meta tags
- Semantic HTML
- Accessible design

---

## 🔧 **Customization**

### **To Update Content:**

1. **Desktop Version:**
   - Edit `NNPC_AI_Training_Timetable_Desktop.html`
   - Content and styles are in the same file

2. **Vercel Version:**
   - Edit `vercel-version/index.html` for content
   - Edit `vercel-version/styles.css` for styling

### **To Replace Logos:**

Currently, logos are embedded as SVG data URLs. To use real logo images:

1. Add your logo files (e.g., `jake-riley-logo.png`, `nnpc-logo.png`) to the project
2. Replace the `src` attributes in the HTML:
   ```html
   <!-- Replace this: -->
   <img src="data:image/svg+xml;base64,..." alt="Jake Riley Academy">
   
   <!-- With this: -->
   <img src="jake-riley-logo.png" alt="Jake Riley Academy">
   ```

---

## 📱 **Browser Compatibility**

✅ Chrome/Edge (Latest)
✅ Firefox (Latest)
✅ Safari (Latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🆘 **Troubleshooting**

### **Vercel Deployment Issues:**

**Issue:** Deployment fails
- **Solution:** Check that all files are in the repository
- Verify `vercel.json` is in the root of your vercel-version folder

**Issue:** CSS not loading
- **Solution:** Ensure `styles.css` is in the same directory as `index.html`
- Check that the link tag in HTML points to correct path: `<link rel="stylesheet" href="styles.css">`

**Issue:** Site not updating
- **Solution:** Vercel caches files. Go to Vercel dashboard → Deployments → Redeploy

### **Desktop Version Issues:**

**Issue:** Page looks broken
- **Solution:** Ensure you're opening the HTML file in a modern browser
- Try a different browser

---

## 📞 **Support & Contact**

For questions about the training program:
- **Jake Riley Academy Office, Abuja**
- **Trainer:** Suleiman Shaibu

For technical issues with the website:
- Check GitHub repository issues
- Contact your web administrator

---

## 📜 **License**

© 2025 Jake Riley Academy & NNPC Academy. All rights reserved.

---

## 🎓 **About the Training**

This comprehensive 5-day AI training program is designed to transform KRPC staff into confident AI practitioners who can immediately apply AI tools to improve refinery operations and efficiency.

**Learning Outcomes:**
- **Knowledge:** AI fundamentals, tools, opportunities, ethics
- **Skills:** Prompt engineering, data analysis, AI solutions, collaboration
- **Attitudes:** Confidence with AI, seeing AI as practical tool
- **Actions:** Immediate implementation, knowledge sharing, transformation

---

**Last Updated:** October 25, 2025
**Version:** 1.0