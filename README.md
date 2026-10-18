# mursalin.is-a.dev — starter kit

This ZIP contains:
- `website/`: a complete, responsive personal software-developer portfolio.
- `domains/mursalin.json`: a starter domain-registration file for the `is-a.dev/register` repository.

**Important:** I cannot submit the domain claim or fork the upstream GitHub repository from this ZIP. You must fork `https://github.com/is-a-dev/register`, copy `domains/mursalin.json` into that fork's `domains/` folder, update the two placeholders, and open a pull request. Registration is not guaranteed until maintainers approve and merge it.

## 1. Customize the portfolio
Open `website/index.html` and replace the sample contact links and any text you want to personalize. The portfolio uses your software-development background as a starting point (Java, Spring Boot, Temenos/IRIS APIs, Oracle, Linux, Docker, and your Bangla cyberbullying-detection research). Review every claim before publishing.

## 2. Publish the website with GitHub Pages
1. Create a new public GitHub repository for the site (for example, `mursalin-portfolio`).
2. Upload the **contents** of `website/` to the repository root.
3. In the repository, open **Settings → Pages** and publish from the `main` branch, `/ (root)`.
4. Wait until GitHub Pages gives you a working URL. Test it in a private/incognito window.
5. In **Settings → Pages → Custom domain**, enter `mursalin.is-a.dev` and save. If GitHub asks you to add a verification TXT record, follow its current instructions.
6. Keep the repository's generated `CNAME` file if GitHub Pages creates one. Do not point the domain at the custom domain itself.

## 3. Prepare the is-a.dev claim
1. Sign in to GitHub and fork: https://github.com/is-a-dev/register
2. In your fork, open `domains/` and add `mursalin.json`.
3. Edit `domains/mursalin.json`:
   - Replace `YOUR_GITHUB_USERNAME` with your exact GitHub username.
   - Replace the CNAME target with the hostname GitHub Pages tells you to use. For a standard GitHub Pages account site, it is usually `YOUR_GITHUB_USERNAME.github.io`.
4. Validate the JSON (for example, at https://jsonlint.com/).
5. Open a pull request from your fork to `is-a-dev/register`. Keep the repository's PR template intact and complete it.
6. Include both the live website URL and a screenshot of the working website in the PR description, as required by the project's instructions.
7. Watch the PR for maintainer feedback. Do not assume the domain is registered until it is merged.

## 4. After the PR is merged
Make sure GitHub Pages has `mursalin.is-a.dev` saved as the custom domain. DNS may take time to propagate. Test `https://mursalin.is-a.dev` after the repository and Pages settings are both configured.

## Files
- `website/index.html` — page content and metadata
- `website/styles.css` — responsive design
- `website/script.js` — mobile navigation and current year
- `domains/mursalin.json` — claim template
