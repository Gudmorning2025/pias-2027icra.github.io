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

CSS and JavaScript are included in the same file. The page uses system fonts, an original inline SVG illustration, and local speaker photos in `assets/`; no package installation or build is required. Without JavaScript, all three robotics cases remain readable. With JavaScript, they become keyboard-accessible tabs.

The website is at the **proposal stage**. Final workshop acceptance, contribution deadlines, and the exact event date are not represented as confirmed. The draft schedule and robotics cases follow the supplied full-proposal snapshot; website copy does not edit or supersede the proposal.

The October 27, 2026 content update incorporates the supplied workshop workbook. Rika Antonova, Jiajun Wu, Bolei Zhou, and Keerthana Gopalakrishnan are listed as confirmed participants; talk titles, formats, and session assignments remain pending. Keerthana Gopalakrishnan's and Tianyu Shi's affiliations are explicitly left to be confirmed. No pending or declined invitees, invitation correspondence, private contact details, or internal task records are published.

The [official ICRA workshop call](https://2027.ieee-icra.org/contribute/call-for-workshop-and-tutorial/) supplies the November 2, 2026 organizer-proposal deadline, January 31, 2027 workshop decision, and May 24 or May 28 workshop dates. Organizer deadlines are kept separate from contributed-paper dates, which remain unannounced.

Chongyu Zhu and Xinge Liu are included in the organizing team as PhD candidates at the University of Toronto, using the names, affiliations, roles, and color portraits supplied by the user.

## Profile photos

Photos are stored locally and each speaker card links to the corresponding professional profile. Photos remain the property of their respective rights holders.

- Rika Antonova: https://contactrika.github.io/img/rika_photo_one.jpg
- Jiajun Wu: https://jiajunwu.com/images/Jiajun_Wu.jpg
- Bolei Zhou: https://boleizhou.github.io/assets/img/prof_pic2.jpg
- Keerthana Gopalakrishnan: https://storage.googleapis.com/gweb-research2023-media/pubtools/7002.png
- Chongyu Zhu: user-supplied color portrait, stored at `assets/chongyu-zhu.jpg`.
- Xinge Liu: user-supplied color portrait, stored at `assets/xinge-liu.jpg`.

Before the public call, replace pending details, review the schedule and affiliations, and remove the `noindex, nofollow` robots meta tag once the site is ready for indexing. The public website does not contain the reviewers' text, review ID, or private proposal files.

## Deployment

Push or upload the website files to `main`. In repository **Settings → Pages**, select **Deploy from a branch**, **main**, **/ (root)**, then Save. The empty `.nojekyll` file disables Jekyll processing. GitHub will rebuild after subsequent commits.

The original Word and Overleaf proposal files are maintained separately and are not part of this public website repository.
