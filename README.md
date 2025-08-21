# Paperwhite

A minimalist Hugo theme using Tailwind CSS and vanilla JavaScript.

## Features

- Tailwind CSS
- Footnote reference tooltips
- Table of contents scrollspy
- Google Analytics
- Search Engine Optimization (SEO)
- Social Links (with Font Awesome icons)

## Installation

```bash
git submodule add git@github.com:nickolashkraus/paperwhite.git themes/paperwhite
```

`hugo.toml`

```toml
theme = 'paperwhite'
```

Install Node packages:

```bash
npm install --save-dev tailwindcss @tailwindcss/cli @tailwindcss/typography
```

## Configuration

### Google Analytics

To add support for Google Analytics, add the following to your configuration
file:

```toml
[services]
  [services.googleAnalytics]
    id = 'G-MEASUREMENT_ID'
```

### Search Engine Optimization (SEO)

This theme provides intelligent configuration of SEO meta tags that adhere to
best practices with sensible fallbacks.

For documentation on configuring SEO and social media appearance, see the
[documentation](docs/search-engine-optimization.md).

## Social Links (with Font Awesome icons)

Social links (with Font Awesome icons) can be added via the configuration file.

```toml
[[params.socials]]
  icon = 'fa-sharp fa-regular fa-envelope'
  name = 'Email'
  url = 'mailto:0x@nickolaskraus.io'
```

## Development

Install Node packages:

```bash
npm install
```

Run Hugo server:

```bash
cd exampleSite/
hugo server --themesDir ../..
```
