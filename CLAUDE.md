# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Hugo Theme Development Commands
- Build: `hugo server` - Start development server
- Build with drafts: `hugo server -D` - Include draft content
- Production build: `hugo --minify` - Create optimized site
- Check links: `hugo --gc --minify --cleanDestinationDir`

## Code Style Guidelines
- HTML: Use semantic HTML elements, 2-space indentation
- CSS: Follow BEM methodology for classes, organize by component
- JS: Vanilla JS only, follow ES6 standards
- Markdown: Use ATX-style headers, reference-style links
- File naming: kebab-case for templates, snake_case for partials
- Hugo templates: Use partial templates for reusable components
- Content organization: Follow Hugo's content organization best practices
- Comments: Use descriptive comments for complex template logic