# jonMey.github.io

# Personal Website

A personal website starter for a Machine Learning / AI student at Georgia Tech looking for an MLE position. This website includes sections for resume/CV, portfolio projects, and contact links.

## Directory Structure
├─ README.md
├─ index.html
├─ css/
│   └─ style.css
├─ js/
│   └─ main.js
├─ images/
│   └─ sample-profile-pic.jpg
├─ docs/
│   └─ resume.pdf

- **index.html**: Main landing page. Contains the structure of your site.
- **css/style.css**: All CSS styles. You can change colors, fonts, and layout here.
- **js/main.js**: JavaScript functionalities (e.g., theme toggling).
- **images/**: Folder for profile picture(s) and other images.
- **docs/**: Folder for your PDF resume/CV or other reference documents.

## How to Add Content or Update the Site

1. **Update text in `index.html`**:
   - Change your name, background, and summary in the `<section id="intro">`.
   - Link your real GitHub repos in the Portfolio section.
   - Update your contact information in the Contact section.

2. **Add a new portfolio project**:
   - Open `index.html` and go to `<section id="portfolio">`.
   - Copy/paste an existing `<div class="portfolio-item">...</div>` block and update the text, project name, and GitHub link.

3. **Replace or add images**:
   - Place any new images inside `images/`.
   - Update `<img src="images/..." />` in `index.html` to reference the correct filename.

4. **Update your resume**:
   - Replace `docs/resume.pdf` with your updated PDF.
   - Make sure `<a href="docs/resume.pdf" ...>` in `index.html` points to the correct file name.

5. **Change color themes or fonts**:
   - Open `css/style.css`.
   - Modify the `:root` variables for the light theme and `[data-theme='dark']` for the dark theme.
   - Adjust the fonts by updating `--heading-font` and `--body-font`.

6. **JavaScript / Interactivity**:
   - If you want to add new interactive features, you can do so in `js/main.js`.
   - For example, you can add form validations or other scripts.

## How to Publish on GitHub Pages

1. Make sure your repository is named `username.github.io` if this is for a personal website.
2. Commit and push all files (including `index.html`, `css/style.css`, `js/main.js`, etc.).
3. Go to the repository’s **Settings** -> **Pages**.
4. Under **Source**, select the branch (e.g., `main`) and folder (e.g., `/root`) if prompted.
5. Click **Save**. 
6. GitHub Pages will give you a URL: `https://username.github.io` (or `https://username.github.io/my-website` if it’s a project site).
7. Wait a minute and then navigate to the URL.

## Best Practices

- Keep commit messages descriptive: *Add new portfolio item*, *Update resume*, etc.
- Use meaningful file names for images and documents.
- Update your site regularly with new projects, experiences, and skills.

---

Happy coding!
