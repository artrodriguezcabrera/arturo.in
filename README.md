# arturo.in website

My personal website to display blogs, work experience, and projects.

Website built with Astro and publiched on GitHub Pages.
Using the Astro Theme - Super Solstice: https://super-solstice.vercel.app/

# 🤖 Tech stack

Main Framework - Astro
Type Checking - TypeScript
JS framework - Vanilla JS
Styling - TailwindCSS
Icons - Iconoir
Code Formatting - Rustwind & Prettier (`pnpm format`)
Deployment - Vercel
Illustrations & Content - Midjourney & ChatGPT

# 🖥️ Running locally

```sh
pnpm install
pnpm dev
```

# Adding blog posts

Add markdown files similar to the ones in [blog/\*.md](src/pages/blog/), they need to have the following format:

```yaml
---
layout: ../../layout/MarkdownLayout.astro
title: My markdown capabilities
description: "This is everything I know about markdown"
pubDate: 2022-07-15
tags: ["astro", "learning in public", "setbacks", "community"]
---
```

