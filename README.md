# Abhay Tevatia — Portfolio Website

A minimal, dark-themed personal portfolio built with pure HTML, CSS and JavaScript. Designed to be hosted on GitHub Pages.

## 📁 File Structure

```
portfolio/
├── index.html              ← Main page
├── assets/
│   ├── style.css           ← All styles
│   ├── script.js           ← Interactions & animations
│   └── Abhay_Tevatia_Resume.pdf  ← ⚠️ ADD YOUR RESUME HERE
└── images/
    └── avatar.jpg          ← ⚠️ OPTIONAL: Add your photo here
```

## 🚀 Setup

### 1. Add Your Resume
Drop your resume PDF into the `assets/` folder and name it exactly:
```
Abhay_Tevatia_Resume.pdf
```

### 2. Add Your Photo (Optional)
Add a headshot to `images/avatar.jpg`  
Then in `index.html`, find the `.hero__avatar` div and replace:
```html
<div class="hero__avatar-placeholder"><span>AT</span></div>
```
with:
```html
<img src="images/avatar.jpg" alt="Abhay Tevatia" />
```

### 3. Host on GitHub Pages
1. Create a new GitHub repo (e.g. `abhaytevatia.github.io` or any name)
2. Upload all files
3. Go to **Settings → Pages → Source → main branch**
4. Your site will be live at `https://yourusername.github.io/repo-name`

## ✏️ Customisation

- **Projects**: Edit the project cards in `index.html` under the `#projects` section
- **Stats**: Change the `data-target` values on `.stats__num` elements
- **Colors**: Edit CSS variables at the top of `style.css`
- **Socials**: Update LinkedIn and email links throughout `index.html`

## 🎨 Design

- **Theme**: Dark minimal with purple accent (`#6c63ff`)
- **Fonts**: DM Serif Display (headings) + DM Sans (body)
- **Features**: Animated counters, scroll reveal, project filter tabs, mobile responsive
