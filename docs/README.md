# SITE 1101 Personal Portfolio

A personal portfolio website created for SITE 1101. It introduces the author, shares background and activities through an interactive About page, presents Project 1, and summarizes education and career development.

> Before publishing, replace the sample name, text, photo, project details, and GitHub repository link with your own.

## Project structure

```text
.
├── index.html      # Home page and introduction
├── about.html      # Background, qualifications, activities, and quest tracker
├── projects.html   # Project 1 description and screenshot
├── career.html     # Education, technical skills, volunteering, and career activity
├── style.css       # Shared layout, typography, and responsive styles
├── docs/
│   ├── README.md   # Project documentation
│   └── Chat.md     # Project notes
└── media/
    ├── turan-profile.png
    ├── Turan Picture.png
    ├── certificate.jpg
    └── Project 1.jpg
```

## Features

- Responsive layout with consistent navigation and footer across pages.
- Interactive About page with a gamified milestone tracker.
- Project 1 card with a description and screenshot.
- Shared CSS for a consistent visual style.

## Run locally

1. Open this project folder in Visual Studio Code.
2. Install the **Live Server** extension if it is not already installed.
3. In the Explorer, right-click `index.html` and choose **Open with Live Server**.
4. The site opens in your browser. Use the navigation links to visit the About, Projects, and Career pages.

## Publish with GitHub Pages

1. Push the project files to a GitHub repository. Make sure `index.html` is in the repository's published folder.
2. Open the repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your default branch (commonly `main`) and the `/(root)` folder, then click **Save**.
5. After GitHub Pages finishes deploying, use the URL shown in the Pages settings. It is usually `https://<username>.github.io/<repository>/`.

If you update the site later, push the changes to the selected branch and allow GitHub Pages a few minutes to redeploy.