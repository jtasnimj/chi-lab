# Chi Lab

Standalone landing page prepared for GitHub Pages. All imagery, typography, styling, and interaction code are embedded in `index.html`. The page includes the latest copy edits.

## Publish

1. Create a repository named `chi-lab` in the intended GitHub account or organization. GitHub Free supports Pages from public repositories; paid plans can also support private repositories.
2. Upload `index.html` and `.nojekyll` to the root of the `main` branch. This README is optional. Do not upload the ZIP itself.
3. In **Settings → Pages**, choose **Deploy from a branch**, **main**, and **/(root)**. Save.
4. Wait for the Pages deployment to complete and check the published `github.io` address shown in Settings → Pages.
5. Before requesting DNS changes, enter `chilab.ai` in **Settings → Pages → Custom domain** and save. GitHub creates a `CNAME` file containing `chilab.ai`; retain it on future updates. The default Pages address will then redirect to the custom domain.
6. Send the separately prepared DNS handoff to the colleague who manages GoDaddy, replacing its GitHub-owner placeholder with the actual publishing account or organization.
7. After DNS resolves and a certificate is issued, enable **Enforce HTTPS** and check both `https://chilab.ai` and `https://www.chilab.ai`.

## Updating

Replace `index.html` with the latest version and commit to `main`. Keep `.nojekyll` and the custom-domain `CNAME` file in place. GitHub Pages will deploy the change automatically.

## Waitlist

The email form is a clearly marked design preview. It does not send or save email addresses. GitHub Pages serves static files; real subscriptions require a separate form service or API and an update to the form handler.

## Official documentation

- [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Configure the custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
