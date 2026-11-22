# Teachweek — Teacher Planner Generator

A seven-day teacher planner generator with live previews and hyperlinked PDF downloads. Built with plain HTML, CSS, and JavaScript; no dependencies, build step, API keys, or backend.

## Publish on GitHub Pages

1. Create a public GitHub repository named `teacher-planner`. Select **Add a README file** to initialise its main branch.
2. Extract this ZIP on your computer or phone.
3. In the repository, choose **Add file → Upload files**.
4. Upload `index.html`, `style.css`, `app.js`, and this `README.md` directly into the repository root. Do not upload the ZIP or a containing folder. Replace the initial README if prompted.
5. Commit the files to `main`.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose branch **main**, folder **/(root)**, and click **Save**.
9. Wait for deployment, then use the website link GitHub displays in Pages settings.

If the repository belongs to zero6git and is named teacher-planner, the expected address is https://zero6git.github.io/teacherplanner/ (not live until deployment succeeds).

## Features

- Personalised cover and teacher/class name
- Any seven consecutive dates between 1900 and 2100
- Monday or Sunday calendar and weekly overview ordering
- Adjustable teaching hours and 15-, 30-, or 60-minute schedule intervals
- Zero, one, or two notes pages per day
- Four accent colours; left- or right-side navigation
- Monthly calendar, weekly overview, daily plan, cover, and notes previews
- Downloadable vector PDF with internal links and selectable text
- Browser-local settings saved on the visitor's device

## Using the planner

Customise settings, preview the pages, and select **Download planner**. Import the PDF into a compatible PDF annotation app to write on it. Some apps require reading/navigation mode for links and pen mode for handwriting.

## Prototype limitations

This is a dated seven-day prototype, not an undated or full academic-year planner. The monthly calendar links only included dates. Scheduling is limited to 32 slots per day to preserve writing space. Exported text currently supports basic English characters. No editing of handwriting or typing is provided in the generator. Device and PDF-app compatibility should be tested before making compatibility claims.

## Privacy

Planner generation happens in the browser. Settings are saved in localStorage on the visitor's device. No planner settings are uploaded by this application. GitHub Pages hosts the site and may process standard website request information under GitHub's policies.

## Source licensing

No open-source licence has been selected. Public visibility alone does not grant a general licence to reuse or redistribute the code. The repository owner can add a licence later.
