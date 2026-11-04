# Pritam Das — Personal Portfolio

The editable source of my personal website. This repository is separate from the EconPrep MSQE preparation application.

## Files

- `index.html`: biography, education, experience, projects and interests.
- `style.css`: colours, typography, layouts and mobile styles.
- `assets/pritam-das-portrait.jpg`: profile portrait.
- `COPYRIGHT.md`: copyright notice.

## Make an update on GitHub

1. Open `index.html` and click the pencil button to edit.
2. Change the relevant text or add a project card.
3. Choose **Commit changes** and enter a short description.

To add a project, find `<div class="project-list">` in the `work` section and insert a card like this inside it:

```html
<article class="page-card">
  <div class="project-meta">Year · Project type</div>
  <h3>Project name</h3>
  <p>A short explanation of the problem, your work, and the result.</p>
  <a href="https://github.com/PritamD21/REPOSITORY-NAME">View project ↗</a>
</article>
```

Use a separate repository for each project's code and link to it from this portfolio. Replace the example URL with the actual repository or project address.

## Preview and publishing

Download or clone this repository and open `index.html` in a browser. No installation or build is needed.

Committing here saves the source and its version history. It does **not** automatically update the existing hosted website. Redeploy the updated files after editing; automatic deployment has not been configured.

The EconPrep links in this source copy point to the private MSQE project repository. Its hosted demo address is intentionally omitted. You can change those links to your preferred project destination later.

## Privacy

Keep this repository private. It contains only the public-facing portfolio and portrait, with no CV document, contact details, exam papers, question bank or application credentials.
