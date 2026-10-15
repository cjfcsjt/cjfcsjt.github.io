# cjfcsjt.github.io

Personal academic homepage of **Jingfan Chen** (Ph.D. student, Department of Computing, The Hong Kong Polytechnic University), built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template and deployed to GitHub Pages.

Live site: <https://cjfcsjt.github.io>

## Where to edit things

| What                                    | File                                                                |
| --------------------------------------- | ------------------------------------------------------------------- |
| Bio and research interests (home page)  | `_pages/about.md`                                                   |
| Profile photo                           | `assets/img/prof_pic.jpg` (replace the placeholder, keep the name)  |
| Publications                            | `_bibliography/papers.bib` (`selected = {true}` shows it on home)   |
| Publication teaser images               | `assets/img/publication_preview/` + `preview = {file.png}` in bib   |
| News                                    | one Markdown file per item in `_news/`                              |
| CV page                                 | `_data/cv.yml`                                                      |
| Social links (email, Scholar, GitHub)   | `_data/socials.yml`                                                 |
| Venue badge colors                      | `_data/venues.yml`                                                  |
| Co-author links                         | `_data/coauthors.yml`                                               |
| Site-wide settings                      | `_config.yml`                                                       |

## Deployment

Every push to `main` runs the **Deploy site** workflow, which builds the site and pushes it to the `gh-pages` branch.

One-time setup:

1. **Settings → Actions → General → Workflow permissions**: choose **Read and write permissions**.
2. **Settings → Pages → Build and deployment**: Source **Deploy from a branch**, branch **`gh-pages`** / root.

Citation counts on the publication badges are refreshed by the **Update Google Scholar citations** workflow (`_data/citations.yml`).

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Or with Docker: `docker compose up -d`, then open <http://localhost:8080>. See `docs/` for the full al-folio documentation.
