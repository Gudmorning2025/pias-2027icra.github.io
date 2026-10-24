# PIAS 2027 workshop website

Static, buildless website for **Physical Intelligence at Scale**.

- Organization: `PIAS-2027ICRA`
- Repository: `PIAS-2027ICRA/pias-2027icra.github.io`
- Intended URL: https://pias-2027icra.github.io/
- Contact: **PIAS.2027ICRA@outlook.com**
- Entry point: `index.html`
- GitHub Pages source: `main`, `/ (root)`; leave Custom domain empty.

## Edit the website

Edit `index.html`. HTML comments identify the main content areas:

| Area | Find in the file |
| --- | --- |
| Workshop status, title and location | `HERO` and `.status-bar` |
| Introduction | `ABOUT` |
| Four research themes | `id="themes"` |
| Three interactive discussion cases | `CASES` |
| Draft schedule | `PROGRAM` |
| Contribution instructions and dates | `CFP` |
| Organizers and speakers | `PEOPLE` |
| Contact email | `PIAS.2027ICRA@outlook.com` |

CSS and JavaScript are included in the same file. The page uses system fonts and an original inline SVG illustration; no package installation or build is required. Without JavaScript, all three robotics cases remain readable. With JavaScript, they become keyboard-accessible tabs.

The initial website is a **proposal-stage template**. Final acceptance, speakers, contribution deadlines and event date are not represented as confirmed. The draft schedule and organizing team follow the supplied full-proposal snapshot; website copy does not edit or supersede the proposal.

Before the public call, replace pending details, review the schedule and affiliations, and remove the `noindex, nofollow` robots meta tag once the site is ready for indexing. The public website does not contain the reviewers' text, review ID, or private proposal files.

## Deployment

Push or upload the website files to `main`. In repository **Settings → Pages**, select **Deploy from a branch**, **main**, **/ (root)**, then Save. The empty `.nojekyll` file disables Jekyll processing. GitHub will rebuild after subsequent commits.

The original Word and Overleaf proposal files are maintained separately and are not part of this public website repository.
