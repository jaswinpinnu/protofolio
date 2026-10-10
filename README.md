# Jaswin — Modern Dark Developer Portfolio

A responsive, static portfolio built with HTML, CSS, and vanilla JavaScript. No build step or package installation is required.

## Included
- Dark charcoal design with violet/cyan accents
- Responsive mobile navigation
- Subtle scroll-reveal animation (respects reduced-motion preferences)
- About, skills, projects, education, and contact sections
- Direct links to GitHub, LinkedIn, email, and the RK Fashions website
- Profile photo placeholder until you add your own image

## Add your profile photo
1. Choose a clear photo of yourself.
2. Copy it into `assets/`.
3. Rename it to `profile.jpg` (or update the image path in `index.html` if using another format).
4. Keep the crop portrait-oriented; the site uses `object-fit: cover`.

The page intentionally uses an initials placeholder if `assets/profile.jpg` is missing.

## Run locally on Windows
**Option A — simplest:** Double-click `index.html` to open it in your browser.

**Option B — VS Code:** Open this folder in VS Code, install the Live Server extension if needed, right-click `index.html`, then select **Open with Live Server**.

## Deploy with GitHub Pages
1. Sign in to GitHub and create a new repository, for example `jaswin-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder to the repository root. Do not upload only the ZIP file.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the deployment to finish. Your site URL will usually be `https://YOUR-USERNAME.github.io/jaswin-portfolio/`.

If you want the site at `https://jaswinpinnu.github.io/`, create a repository named exactly `jaswinpinnu.github.io` and deploy the site files from its root. Check the repository settings before replacing anything already published there.

## Personal details to review
- Name: Jaswin
- Role: Graduate Student / Full Stack Developer Intern
- Education: GITAM University, B.Tech — CSE (AI & ML), 2026
- GitHub: https://github.com/jaswinpinnu
- LinkedIn: https://www.linkedin.com/in/jaswin-pinnu-5b99572a3/
- Email: jaswinpinnu@gmail.com

## Before publishing
- Add your real profile photo.
- Confirm the content, project descriptions, and links.
- Add a code/demo link for the satellite imagery capstone when you have a public repository.
- Only add a resume download button after placing your current resume PDF in the project and linking it.


## Email button behavior
The email links open Gmail's compose window addressed to `jaswinpinnu@gmail.com`. This is useful when the visitor uses Gmail in a browser. Visitors who do not use Gmail can still copy the address and send a message from their own email app. A website contact form that sends mail directly requires a service or backend; do not put private email-service API secrets in frontend code.
