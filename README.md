# Academic Portfolio Website

This is a simple academic portfolio website built with HTML and CSS, designed to showcase academic achievements, research projects, and publications.

## Pages

- **Myself**: Personal introduction and background
- **Work & Study**: Educational background and academic journey
- **Projects**: Current research projects and interests
- **Publications and Conferences**: List of conference presentations and academic contributions

## GitHub Pages Setup

To host this website on GitHub Pages:

1. Create a new repository on GitHub (if not already created)
2. Push the code to GitHub:

   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. Go to your repository's Settings on GitHub
4. Scroll down to the "GitHub Pages" section
5. Under "Source", select "main" branch
6. Click Save

The site will be published at `https://YOUR_USERNAME.github.io/REPOSITORY_NAME/`

Note: Since this is a multi-page website, all internal links are relative (e.g., `work-study.html`), so they will work automatically on GitHub Pages.

## Local Development

To run this website locally:

1. Clone the repository
2. Open `index.html` in your web browser

## File Structure

```
/
├── index.html           # Homepage/About Me
├── work-study.html     # Education and Work Experience
├── projects.html       # Research Projects
├── publications.html   # Publications and Conferences
└── styles.css         # Shared styles
```

## Technologies Used

- HTML5
- CSS3
- GitHub Pages for hosting
