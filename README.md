# Article content for GitHub Pages

Three published articles and the original About landing page as Markdown, with only their referenced images. No WordPress theme files, plugins, scripts, thumbnail variants, attachment pages, category/tag archives or API responses.

- articles/: three editable Markdown articles, with permalink values preserving their existing addresses.
- assets/images/: one copy of each image referenced in the articles and eight original certificate badges.
- _config.yml and _layouts/default.html: minimal Jekyll settings and a plain reading layout.
- index.md: the original About text and all eight certificate badges at /.
- posts.md: the article list at /posts/.
- sonicwall-legacy.html: browser redirect for the old undated SonicWall address.

To publish: upload this folder's contents to a GitHub repository, then choose Settings > Pages > Deploy from a branch > main > /(root). GitHub's built-in Jekyll build converts the Markdown to HTML. Do not add .nojekyll. Configure lukasharris.com as the custom domain when ready to migrate.

For another Jekyll design, keep the Markdown, images and permalink values, and change layout to match your design. Hugo requires adapting the front matter.

Images use paths from the domain root. Use your custom domain or a USERNAME.github.io repository for a preview at the domain root. A project URL under /repository-name/ requires adjusting base-path references.

The legacy redirect uses a browser refresh, not HTTP 301. Direct legacy image URLs under /wp-content/uploads/ are not part of this article-only package. The earlier recovery copy remains separately in the workspace if needed.

Historical wording, dates and code examples are preserved; technical instructions have not been updated. The undated SonicWall page contained only a moved notice and is represented by the redirect, not a fourth article.

The HackTheBox article uses Liquid raw guards around its body so its template-injection code examples display literally on GitHub Pages. Keep those guards when publishing with Jekyll.
