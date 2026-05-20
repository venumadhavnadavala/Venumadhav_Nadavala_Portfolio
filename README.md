# Venu Madhav Nadavala - Portfolio Website

A personal portfolio website built with React JS and styled-components.

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm

### Installation

1. **Extract** this zip file to a folder.

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```
   Opens at [http://localhost:3000](http://localhost:3000)

4. **Build for production:**
   ```bash
   npm run build
   ```

## 📁 Project Structure

```
src/
├── components/
│   ├── About/
│   ├── Cards/           (EducationCard, ExperienceCard, ProjectCards)
│   ├── Contact/
│   ├── Education/
│   ├── Experience/
│   ├── Footer/
│   ├── HeroBgAnimation/
│   ├── HeroSection/
│   ├── Navbar/
│   ├── ProjectDetails/
│   ├── Projects/
│   └── Skills/
├── data/
│   └── constants.js     ← Edit this to update your info!
├── themes/
│   └── default.js
└── utils/
    └── Themes.js
```

## ✏️ Customization

### Update your personal info
Edit `src/data/constants.js`:
- `Bio` - name, roles, description, social links
- `skills` - add/remove your tech skills
- `experiences` - update work history
- `education` - update education details
- `projects` - add your projects

### Update Hero Image
Replace the image URL in `src/components/HeroSection/index.js`:
```js
src="YOUR_IMAGE_URL_HERE"
```

### Update EmailJS (Contact Form)
In `src/components/Contact/index.js`, replace the EmailJS credentials:
```js
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form.current, 'YOUR_PUBLIC_KEY')
```

### Deploy to GitHub Pages
1. Install: `npm install --save-dev gh-pages`
2. Add to package.json:
   ```json
   "homepage": "https://venumadhavnadavala.github.io/portfolio",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }
   ```
3. Run: `npm run deploy`

## 🔗 Social Links
- GitHub: https://github.com/venumadhavnadavala
- LinkedIn: https://www.linkedin.com/in/venumadhav-nadavala/
- LeetCode: https://leetcode.com/u/VenumadhavNadavala/
- Instagram: https://www.instagram.com/venumadhavnadavala
