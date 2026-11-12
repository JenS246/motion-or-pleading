# Motion or Pleading?

A short, interactive game for introductory civil litigation students at the Community College of Philadelphia. It distinguishes pleadings from motions and introduces motion practice in Pennsylvania through 12 questions.

## Run locally

Open `index.html` in a browser. The game is self-contained and does not collect data or require a server or dependencies.

## Publish on GitHub Pages

1. Create a public GitHub repository named `motion-or-pleading` under `jens246`.
2. Upload all files in this folder, including `.github/workflows/pages.yml`, to its `main` branch. GitHub's web upload does not reliably include hidden folders; create that workflow using **Add file → Create new file**, entering `.github/workflows/pages.yml` as the filename, or push the folder using Git.
3. In **Settings → Pages → Build and deployment**, choose **GitHub Actions** as the source.
4. In **Actions**, wait for the Pages workflow to succeed. Visit https://jens246.github.io/motion-or-pleading/.

The game uses relative paths and works at the repository's Pages URL. No backend is needed.

## Pennsylvania rules

The questions are introductory and use Pennsylvania civil procedure, including [Rule 1017](https://www.pacodeandbulletin.gov/secure/pacode/data/231/chapter1000/s1017.html), [Rule 1030](https://www.pacodeandbulletin.gov/secure/pacode/data/231/chapter1000/s1030.html), [Rule 1033](https://www.pacodeandbulletin.gov/secure/pacode/data/231/chapter1000/s1033.html), and [Rule 208.1](https://www.pacodeandbulletin.gov/secure/pacode/data/231/chapter200/s208.1.html).
