# Alex Taylor-Barreto · alexxx-db.github.io

Personal site and portfolio: **Data & AI Practice Lead**, Databricks architect, GenAI and Lakehouse.

- **Live (when published):** `https://alexxx-db.github.io`
- **Stack:** Jekyll + Clean Blog (Bootstrap) on GitHub Pages

## What’s here

- **Home** — Short intro and links to About, Writing, Projects, Contact.
- **About** — Bio: Entrada AI, Databricks, geospatial/GenAI, education, certifications.
- **Writing** — Links to Substack (GenAI, RAG, MCP, A2A, orchestration, fine-tuning) and Entrada blog.
- **Projects** — Curated list of repos under [alexxx-db](https://github.com/orgs/alexxx-db/repositories) (GenAI/MCP, Databricks tooling, ML/forecasting).
- **Contact** — Substack, GitHub, Entrada, LinkedIn.

## Run locally

```bash
# If you use Bundler
bundle install
bundle exec jekyll serve

# Or with a global Jekyll install
jekyll serve
```

Then open `http://localhost:4000`.

## Customize

- **`_config.yml`** — Site title, subtitle, `url`, `github_username`, `linkedin_username` (optional). Add `analytics` when you have a tracking ID.
- **`about.html`** — Edit your bio and roles.
- **`writing.html`** — Add or change Substack/Entrada links and titles.
- **`projects.html`** — Add or change GitHub repo links and short descriptions.

## Legacy content

The `_posts/` folder still contains the original theme author’s blog posts. They are not linked from the new nav or index. To remove them from the build, either delete the files or add `_posts` (or specific patterns) under `exclude` in `_config.yml`.

## Publish

Push to the `main` branch of the `alexxx-db.github.io` repo; GitHub Pages will build and serve the site.
