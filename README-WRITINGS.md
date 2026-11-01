# Publishing a new writing

Your website uses Jekyll, Markdown, and one shared stylesheet. You do not need to write HTML or CSS for articles.

## Add a new article

1. Open the `_posts` folder in your repository. Create it if it does not exist.
2. Add a Markdown file named using this format: `YYYY-MM-DD-your-article-title.md`.
   Example: `2026-11-02-why-i-write.md`
3. Copy the contents of `templates/writing-template.md` into the new file.
4. Replace the title, subtitle, date, category, and sample text.
5. Commit the file to the `main` branch. GitHub Pages will build and publish it.
6. The article will automatically appear on the Writings page.

## Writing with Markdown

- `## Heading` creates a section heading.
- A blank line separates paragraphs.
- `**bold text**` makes text bold.
- `*italic text*` makes text italic.
- `> quotation` creates a blockquote.
- `[link text](https://example.com)` creates a link.

Keep the YAML front matter at the top between the two sets of `---`. The date in the filename should match the date in the front matter.

## Where the files live

- `_posts/` — your published articles.
- `_layouts/writing.html` — shared article page layout.
- `templates/writing-template.md` — copy this for every new article.
- `assets/css/style.css` — shared design for the entire website.

To edit the look of the website, change the CSS file rather than adding styles to individual HTML pages.
