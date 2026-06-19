---
layout: post
title: "Hello World"
date: 2026-06-19
# thumbnail: /assets/blog/hello.png   # optional, delete if unused
# description: "A short one-line summary shown on the blog list page."   # optional
---

Welcome to my blog! This is a sample post that doubles as a template.

## Writing a new post

Create a new markdown file under `_blog/`, for example `_blog/my-post.md`. The
file name becomes the URL slug, so this post lives at `/blogs/hello-world`.

Each post needs a front matter block at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: 2026-06-19
# thumbnail: /assets/blog/your-image.png   # optional
# description: "Optional one-line summary for the list page."   # optional
---
```

## What you can write

Standard Markdown works out of the box, including **bold**, *italic*,
[links](https://song-siqi.github.io), lists, and more:

- Code blocks with syntax highlighting
- Inline math like $E = mc^2$ and display math:

$$
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
$$

```python
def hello():
    print("Hello, world!")
```

That's it. New posts automatically appear on the [Blog](/blogs) page, grouped by
year and sorted newest first.
