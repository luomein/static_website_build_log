---
draft: false
date: 2024-05-13
categories:
  - markdown
  - configuration
  - mkdocs.yml

---

#Emojis markdown

The following icon sets are bundled with Material for MkDocs:

* [Material Design](https://materialdesignicons.com/)
* [FontAwesome](https://fontawesome.com/search?m=free)
* [Octicons](https://octicons.github.com/)
* [Simple Icons](https://simpleicons.org/)

Use the [icon search](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search) in Material for MKDocs to find corresponding shortcodes.

<!-- more -->

## Reference

[Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/)


## Configuration

### Additional lines in `mkdocs.yml`

[Download mkdocs.yml](https://github.com/luomein/static_website_build_log/blob/12317329e409eeb18d53fdb20020900802683e2e/mkdocs.yml)

```
markdown_extensions:
  - attr_list
  - pymdownx.emoji:
      emoji_index: !!python/name:material.extensions.emoji.twemoji
      emoji_generator: !!python/name:material.extensions.emoji.to_svg
```

## Markdown

* Material Design

| icon name | shortcode | markdown | icon | 
| -------- | --------- | --------- | ---- |
| material-design | material-material-design |  `:material-material-design:`  | [:material-material-design:](https://pictogrammers.com/library/mdi/icon/material-design/) |
