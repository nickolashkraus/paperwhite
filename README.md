# Paperwhite

A minimalist Hugo theme using Tailwind CSS and vanilla JavaScript.

## Features

- Tailwind CSS
- Footnote reference tooltips
- Table of contents scrollspy

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

None

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
