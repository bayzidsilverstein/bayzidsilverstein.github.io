# Updating your website

The website uses Jekyll and Markdown. Keep the HTML pages and shared CSS as they are; you can add writing and project entries using Markdown templates.

## Publish an article

1. Open `writing/articles/`.
2. Copy `template.md` and rename the copy, for example `my-first-article.md`.
3. Edit the title, subtitle, date, category, and article text.
4. Set a unique permalink in the front matter, such as `/writing/articles/my-first-article/`.
5. Commit the file. It will be rendered with the shared writing layout and listed on the Writings page.

## Add a project

1. Open `projects/my-projects/`.
2. Copy `template.md` and rename the copy, for example `my-website.md`.
3. Edit the title, summary, date, and project details.
4. Set a unique permalink, such as `/projects/my-projects/my-website/`.
5. Commit the file. It will be rendered with the shared project layout and listed on the Projects page.

## Folder guide

- `writing/writing.html` — Writings landing page.
- `writing/articles/` — article Markdown files and the article template.
- `projects/project.html` — Projects landing page.
- `projects/my-projects/` — project Markdown files and the project template.
- `_layouts/` — shared HTML layouts for articles and projects.
- `assets/css/style.css` — shared styling for the website.

You only need Markdown when adding an article or project. You do not need to write HTML or CSS for each entry.
