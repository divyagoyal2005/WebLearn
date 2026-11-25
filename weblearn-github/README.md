# WebLearn — Web Technology Learning Website

A responsive, interactive study website covering the five units in the supplied Web Technology syllabus.

## Run on your laptop

### Option 1: Open directly
1. Download and extract this project.
2. Open the `weblearn-github` folder.
3. Double-click `index.html`.
4. It opens in Chrome, Edge, Firefox or another modern browser.

No Node.js, npm, database or backend is required.

### Option 2: Run with VS Code
1. Open this folder in Visual Studio Code.
2. Install the **Live Server** extension (optional).
3. Right-click `index.html` and choose **Open with Live Server**.

## Features
- Five syllabus units with expandable topic lessons.
- Search within the selected unit.
- Unit cards and sidebar navigation.
- Topic checklist and unit completion tracking.
- Multiple-choice quizzes with explanations and best-score tracking.
- Personal study notes saved locally.
- Light/dark mode.
- Responsive layout for mobile, tablet and desktop.
- Progress, notes, theme and quiz scores persist in browser localStorage.

## Push to GitHub

Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Add WebLearn Web Technology learning website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with your own GitHub repository URL.

If you already created an empty repository on GitHub, use its HTTPS URL for `git remote add origin`.

## Publish with GitHub Pages
1. Push the project to GitHub.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish the site. The public URL will appear in the Pages section.

## Project structure

```text
weblearn-github/
├── index.html
├── style.css
├── script.js
├── README.md
└── .gitignore
```

## Notes
Learning progress is saved in the browser on the current device. It is not synchronised between devices or users. The Google Fonts import needs an internet connection; the site otherwise works offline with system font fallbacks.
