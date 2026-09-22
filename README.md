# Marietta Dental Professionals — Static Website

Three-page HTML/CSS/JavaScript website prepared for GitHub + Netlify.

## Pages
- `index.html` — Home
- `about.html` — About Us
- `contact.html` — Contact Us

## Assets
- `assets/logo.jpg` is the supplied Marietta Dental Professionals logo.
- The logo is used in the header, hero, footer, favicon, and Open Graph image metadata.
- A few patient/team images are loaded from the official Marietta Dental Professionals website so the repository stays lightweight.

## Deploy to GitHub
1. Create a new GitHub repository.
2. Upload all files and folders from this project.
3. Make sure `index.html` is in the repository root.
4. Commit the files.

## Deploy to Netlify
1. Log in to Netlify.
2. Choose **Add new project → Import an existing project**.
3. Select the GitHub repository.
4. Build command: leave blank.
5. Publish directory: `.`
6. Deploy the site.

`netlify.toml` is included with the publish directory already configured.

## Contact form
The Contact Us form uses Netlify Forms with `data-netlify="true"`. After the site is deployed, submissions can be viewed in the Netlify dashboard under Forms.

## Notes
- The design uses a navy + bright blue palette based on the supplied brand logo and the current visual direction of the official website.
- The phone, address, and office hours are based on the current official website.
