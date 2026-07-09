# Academic Website Setup Instructions

## 📝 Overview

This is your academic website built with Jekyll and the al-folio theme, ready to be published on GitHub Pages at `https://lvodoleyl.github.io`.

## 🚀 Quick Start Guide

### Step 1: Customize Your Information

#### 1.1 Update Personal Information (`_config.yml`)
- Lines 6-8: Update your name (Kirill Abrosimov is already set)
- Line 20: URL is already set to `https://lvodoleyl.github.io`

#### 1.2 Update Social Links (`_data/socials.yml`)
Replace the following placeholders:
- `email`: Your actual email address
- `scholar_userid`: Your Google Scholar ID
- Uncomment and add other profiles (GitHub, LinkedIn, ORCID, ResearchGate) as needed

#### 1.3 Update About Page (`_pages/about.md`)
Replace placeholder text with:
- Your actual biography
- Research interests
- Institution and contact information
- Update the profile section with your location

#### 1.4 Update Research & Publications (`_pages/publications.md`)
- Add your actual research interests
- List your publications (journal papers, conference papers, preprints)
- Update academic profile links (Google Scholar, ORCID, etc.)

#### 1.5 Update Education & Work Experience (`_pages/experience.md`)
- Replace placeholder education entries with your actual degrees
- Add your work experience
- Click items to expand - they use accordion functionality

#### 1.6 Update Teaching & Mentoring (`_pages/teaching.md`)
- Add courses you've taught or assisted with
- Include student mentoring activities
- Each item is expandable with detailed information

### Step 2: Add Your Content

#### 2.1 Add Your Photo
1. Place your profile photo in `assets/img/`
2. Name it `prof_pic.jpg` (or update the filename in `_pages/about.md`)

#### 2.2 Add Your CV
1. Place your CV PDF in `assets/pdf/`
2. Name it `cv.pdf` (or update the path in `_data/socials.yml`)

#### 2.3 Add News/Announcements
- News items are in `_news/` folder
- Create new files following the format:
  ```markdown
  ---
  layout: post
  date: YYYY-MM-DD
  inline: true
  related_posts: false
  ---
  
  Your news text (1-3 lines recommended).
  ```
- Files are named `announcement_X.md` but you can use any name
- Latest 5 news items will appear on the home page

### Step 3: Publish to GitHub Pages

#### 3.1 Initialize Git Repository
```bash
cd ~/research/web_site_KA
git init
git add .
git commit -m "Initial commit: Academic website setup"
```

#### 3.2 Create GitHub Repository
1. Go to https://github.com/new
2. Repository name MUST be: `lvodoleyl.github.io`
3. Keep it public
4. Do NOT initialize with README, .gitignore, or license
5. Click "Create repository"

#### 3.3 Push to GitHub
```bash
git remote add origin https://github.com/lvodoleyl/lvodoleyl.github.io.git
git branch -M main
git push -u origin main
```

#### 3.4 Enable GitHub Pages
1. Go to your repository settings: `https://github.com/lvodoleyl/lvodoleyl.github.io/settings/pages`
2. Under "Source", select "Deploy from a branch"
3. Select branch: `main` and folder: `/ (root)`
4. Click "Save"

#### 3.5 Wait for Deployment
- GitHub will automatically build your Jekyll site
- Check the "Actions" tab to see the build progress
- After 2-5 minutes, your site will be live at `https://lvodoleyl.github.io`

### Step 4: Local Development (Optional)

If you want to test locally before publishing:

#### Install Dependencies
```bash
# Install Ruby (if not already installed)
sudo apt install ruby-full build-essential

# Install Bundler
gem install bundler

# Install Jekyll and dependencies
bundle install
```

#### Run Local Server
```bash
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## 📁 File Structure

```
├── _config.yml              # Main configuration
├── _pages/                  # Your main pages
│   ├── about.md            # Home/About page
│   ├── publications.md     # Research & Publications
│   ├── experience.md       # Education & Work Experience
│   └── teaching.md         # Teaching & Mentoring
├── _news/                   # News announcements
├── _data/
│   └── socials.yml         # Social media links
├── assets/
│   ├── img/                # Images (add prof_pic.jpg here)
│   └── pdf/                # PDFs (add cv.pdf here)
└── Gemfile                 # Ruby dependencies
```

## 🎨 Customization Tips

### Navigation Menu
The navigation menu is controlled by the `nav: true` and `nav_order` settings in each page's front matter.

### Color Theme
Users can toggle between light/dark mode using the button in the navbar.

### Adding More Pages
Create new `.md` files in `_pages/` with the format:
```markdown
---
layout: page
permalink: /your-page/
title: Your Page Title
nav: true
nav_order: 5
---

Your content here
```

## 🔧 Troubleshooting

### Site Not Building?
- Check the "Actions" tab in your GitHub repository for error messages
- Ensure your repository name is exactly `lvodoleyl.github.io`
- Make sure GitHub Pages is enabled in repository settings

### Changes Not Appearing?
- GitHub Pages can take 1-5 minutes to rebuild after you push changes
- Clear your browser cache or use incognito mode
- Check if the build completed successfully in the "Actions" tab

### Local Development Issues?
- Make sure Ruby and Bundler are installed
- Run `bundle install` to install all dependencies
- Check `Gemfile.lock` is not corrupted

## 📚 Resources

- **al-folio Documentation**: https://github.com/alshedivat/al-folio
- **Jekyll Documentation**: https://jekyllrb.com/docs/
- **GitHub Pages Documentation**: https://docs.github.com/en/pages
- **Markdown Guide**: https://www.markdownguide.org/

## 🆘 Need Help?

- **Jekyll Issues**: https://github.com/jekyll/jekyll/issues
- **al-folio Issues**: https://github.com/alshedivat/al-folio/issues
- **GitHub Pages Issues**: https://github.com/orgs/community/discussions

## ✅ Checklist Before Publishing

- [ ] Updated personal information in `_config.yml`
- [ ] Updated social links in `_data/socials.yml`
- [ ] Customized About page with your bio
- [ ] Added your publications and research interests
- [ ] Added your education and work experience
- [ ] Added teaching activities (if applicable)
- [ ] Added profile photo to `assets/img/prof_pic.jpg`
- [ ] Added CV PDF to `assets/pdf/cv.pdf`
- [ ] Created/updated news announcements
- [ ] Tested locally (optional but recommended)
- [ ] Created GitHub repository `lvodoleyl.github.io`
- [ ] Pushed code to GitHub
- [ ] Enabled GitHub Pages in repository settings
- [ ] Verified site is live at `https://lvodoleyl.github.io`

---

**Good luck with your academic website! 🎓**
