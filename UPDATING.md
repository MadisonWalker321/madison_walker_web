# Updating your site

You can do everything below in the GitHub web editor (open a file, click the pencil, then **Commit changes**). The site rebuilds automatically in about two minutes.

1. **Add a paper.** Open `data/papers.yaml`, copy an existing entry, and edit it. Upload the PDF to `static/files/` and set `pdf: "files/your-file.pdf"`. Status values: `published`, `accepted`, `revise and resubmit`, `under review`, `working paper`, `in preparation`.
2. **Mark a paper as published.** Change `status` to `"published"` and fill in `venue`.
3. **Job market paper.** Set `job_market_paper: true` on that entry.
4. **Update your bio.** Edit `content/_index.md` (it is plain text with a blank line between paragraphs). The tagline, role, advisor and email are in `hugo.yaml`.
5. **Add a talk.** Edit `data/talks.yaml`. Add `link` and `link_text` to show a link.
6. **Add teaching, outreach, honors, tools, experience.** Edit `data/teaching.yaml`, `data/outreach.yaml`, `data/awards.yaml`, `data/projects.yaml`, `data/experience.yaml`.
7. **Add a news item.** Edit `data/news.yaml`. Leave `date` empty to omit it.
8. **Update your CV.** Replace `static/files/cv.pdf` (same filename).
9. **Change your photo.** Upload a square image named `photo.jpg` to `static/images/`. It appears in the About panel automatically.
10. **Change the look.** Colors are the variables at the top of `assets/css/style.css`. Or ask your assistant to run the design quest at https://gking.harvard.edu/mysite/files/QUEST_DESIGN.md.

If you rename the repository to `madisonwalker321.github.io`, change `baseURL` in `hugo.yaml` (and the two URLs in `static/robots.txt` and `static/llms.txt`) to `https://madisonwalker321.github.io/`.
