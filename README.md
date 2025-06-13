# Kita Farsi

Kita Farsi is a clean, elegant and simple blog theme for Zola.

This theme is based on Kita theme [Kita](https://github.com/st1020/kita) with some features added.

[Demo](https://daradege.ir/kitafarsi)

![Screenshot](https://raw.githubusercontent.com/daradege/kita-farsi/main/screenshot.png)

## Features

- Easy to use and modify
- No preset limits (This theme does not limit your content directory structure, taxonomy names, etc. It's applicable to all zola sites.)
- Inject support
- Dark mode
- Responsive design
- Social icons
- Taxonomies support
- Projects page
- Archive page
- Table of Content
- Admonition shortcode
- SEO friendly
- Comments using [Giscus](https://giscus.app/)
- Mathematical notations using [KaTeX](https://katex.org/)
- Diagrams and charts using [Mermaid](https://mermaid.js.org/)

## Installation

The easiest way to install this theme is using this repo as a template:

![cloning repo](https://docs.github.com/assets/cb-76823/mw-1440/images/help/repository/use-this-template-button.webp)

then put your pat (get from [here](https://github.com/settings/tokens)) in the repo secrets (actions) as PERSONAL_TOKEN.

Then set your website address the blog is deploying on it as your base_url in `config.toml`.

```toml
base_url = "https://daradege.ir/kita-farsi"
```

after that, go to repo settings, from 'page' section, select deploy from a branch
and select gh-pages

## Configuration

See the `extra` section in [config.toml](https://github.com/daradege/kita-farsi/blob/main/config.toml) as a example.

## Inject support

You can easily use inject to add new features to your side without modifying the theme itself.

To use inject, you need to add some HTML files to the `templates/injects` directory.

The available inject points are: `head`, `header_nav`, `body_start`, `body_end`, `page_start`, `page_end`, `footer`, `page_info`.

For example, to load a custom script, you can add a `templates/injects/head.html` file:

```html
<script src="js-file-path-or-cdn-url.js"></script>
```

## License

[MIT License](https://github.com/daradege/kita-farsi/blob/main/LICENSE)

Copyright (c) 2025-present, daradege
