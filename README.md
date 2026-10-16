# Swamp Markdown Blog

Deterministic Markdown-to-HTML previews, hash-checked local writes and
verification for a consumer-owned static blog. No JavaScript renderer
dependencies and no deployment credentials.

See the [package README](extensions/models/markdown-blog/README.md) for
requirements, configuration, examples and safety boundaries. The package is
`@mgreten/markdown-blog` and uses the MIT license bundled with it.

The model lives in `extensions/models/markdown-blog/`; the reusable
write-and-verify workflow lives in `workflows/`. Nothing deploys automatically.

```bash
~/.swamp/deno/deno test -A extensions/models/markdown-blog/markdown_blog_test.ts
```
