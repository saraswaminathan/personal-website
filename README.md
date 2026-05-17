# Sara Site

Static site for Sara built with [Hugo](https://gohugo.io/).

## Content

Generally, edit content in:

- The pages are in `site/content/`. (There is one markdown file per page.)
- Some config stuff is in `site/hugo.toml`.

Images are in:

- `site/static/images/` (pictures on site)
- `site/static/svgs/` (for the science art)

Don't worry about auto-generated content:

- `site/public/` (the generated site, which is what gets deployed)
- `site/resources/` (the generated resources, like resized images)

## Usage

Development

```sh
hugo server -D
```

Production

```sh
hugo
```

