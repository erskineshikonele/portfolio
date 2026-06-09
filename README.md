# Erskine Brister Shikonele — Portfolio

Personal portfolio website built with plain HTML, CSS, and JavaScript. No build tools, no frameworks — works directly on GitHub Pages.

## Pages

| File | Page |
|------|------|
| `index.html` | Home / Hero |
| `about.html` | About Me |
| `skills.html` | Technical Skills |
| `experience.html` | Work Experience |
| `projects.html` | Projects |
| `education.html` | Education & Certifications |
| `contact.html` | Contact |

## How to deploy on GitHub Pages

1. **Create a new GitHub repository** — name it `your-username.github.io` (replace with your actual GitHub username) for it to be your main site, OR name it anything (e.g. `portfolio`) for it to be at `your-username.github.io/portfolio`.

2. **Upload all files** — drag and drop the entire folder contents into the repository, or use git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click **Settings** → scroll to **Pages** (left sidebar)
   - Under **Source**, select `Deploy from a branch`
   - Choose `main` branch, `/ (root)` folder
   - Click **Save**

4. **Your site will be live** at `https://YOUR_USERNAME.github.io` (or `https://YOUR_USERNAME.github.io/REPO_NAME`) within a few minutes.

## Customisation

- All styles are in `assets/style.css`
- Navigation JS is in `assets/nav.js`
- Each page is a standalone HTML file — edit them directly
- To add a profile photo, place a `photo.jpg` in the `assets/` folder and add an `<img>` tag to `index.html` or `about.html`

## Contact form

The form on `contact.html` uses `mailto:` links — it opens the visitor's email client pre-filled. To handle form submissions server-side, consider [Formspree](https://formspree.io) (free tier available — just replace the `mailto:` action with a Formspree endpoint).
