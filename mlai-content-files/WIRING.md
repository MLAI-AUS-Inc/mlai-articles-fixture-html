# Articles from MLAI

The article files are ready for wiring. Visitors can read them once the site serves them.

Each article has its own folder:

- `mlai-content-files/<slug>/index.md`: the article, with title, description and date in the front matter
- `mlai-content-files/<slug>/article.jsonld`: structured data for search engines
- `mlai-content-files/<slug>/<image>`: the article's images

## To publish them

Show each `index.md` at `/articles/<slug>/` with your site's own Markdown support, link
`/articles/` from your menu, add the JSON-LD to each article page's `<head>`, and add the
URLs to your sitemap. When an article answers at its URL on your live site, MLAI counts it
as published.

