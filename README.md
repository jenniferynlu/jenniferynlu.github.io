# Personal website

A static, responsive personal website built with HTML and CSS. No dependencies, JavaScript, build step, or external fonts.

## Edit your information

- `index.html`: Jennifer’s editable introduction and personal boxes (hobbies, favorites, current interests, and work topics) inside the About Me panel, plus personal links. Personal preferences not supplied yet are labeled “To be added.”
- `technical.html`: résumé, skills, projects, experience, and education. Duplicate an `<article class="entry">` to add another project or role.
- `style.css`: all shared styles, with palette variables at the top.
- Replace `assets/profile-placeholder.svg` with your headshot and update the image `src` and `alt` in `index.html`.
- `assets/resume.pdf` is a copy of the supplied résumé, connected to working view and download links. Replace it to update the résumé. Website content is edited separately in HTML.
- Email and LinkedIn links are connected. Replace the GitHub “coming soon” span on both pages with an anchor when you have a URL to add.
- Update the footer year and personal sections as needed. The technical page is populated from the supplied résumé.
- All authored interface and SVG colors are pure black and white. Small bunny graphics live in `assets/bunny.svg` and `assets/bunny-pair.svg`.

## Preview

Open `index.html` directly in a browser, or run `python3 -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish with GitHub Pages

Commit these files to your repository. In the repository’s **Settings → Pages**, choose **Deploy from a branch**, select your branch and **/ (root)**, then save. All assets and page links are relative, so this works for both user and project sites. No build configuration is required.

The bunny and headshot placeholder are original SVG artwork included in this project.
