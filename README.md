# Braden Covington — Portfolio

Personal portfolio website for Braden Covington, Construction Science & Management student.

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### 1. Create a GitHub repository
- Go to [github.com](https://github.com) → click **New repository**
- Name it `bradencovington.github.io` (replace with your actual GitHub username)
- Set it to **Public**
- Do **not** initialize with a README (you'll push your own files)

### 2. Upload your files
Either use the GitHub web UI (drag & drop) or push via terminal:

```bash
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Under **Source**, select **GitHub Actions**
- The workflow in `.github/workflows/deploy.yml` will auto-run on every push

### 4. Your site will be live at:
```
https://YOUR_USERNAME.github.io
```
(or `https://YOUR_USERNAME.github.io/REPO_NAME` if you used a different repo name)

---

## ✏️ Customizing Your Portfolio

Open `index.html` and search for the following placeholders to replace with your real info:

| Placeholder | What to replace |
|---|---|
| `braden.covington@email.com` | Your real email |
| `linkedin.com/in/bradencovington` | Your LinkedIn URL |
| `github.com/bradencovington` | Your GitHub URL |
| `Your University — City, State` | Your actual university |
| `ABC General Contractors` | Your actual employer |
| `XYZ Construction Services` | Your second internship employer |
| `resume.pdf` | Add a `resume.pdf` file to the same folder |

### Adding your photo
In the About section, find the `about-image-block` div and replace the placeholder with:
```html
<img src="your-photo.jpg" alt="Braden Covington" style="width:100%;height:100%;object-fit:cover;" />
```

### Adding/editing projects
Find the `projects-grid` section. Each project is a `project-card` div. Copy one and update the tag, title, description, and icons.

---

## 📁 File Structure

```
/
├── index.html              ← Main portfolio (single file)
├── resume.pdf              ← Add your resume here
├── your-photo.jpg          ← Add your photo here (optional)
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml      ← Auto-deploy on push to main
```

---

Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, loads instantly.
