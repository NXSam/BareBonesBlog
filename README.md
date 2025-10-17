# A Barebones Astro Blog!

This is the simplest a blog can get. It's almost one page, has a collection of tags, and a basic about page.
It's built off the Astro starter blog template, with the very starting of customization.

<img alt="Image of the site deployed as an example." src="https://github.com/user-attachments/assets/0f7f9bc9-51ae-475f-b7bb-947c541d0307" />

## ❓Why?

This simple repo is meant to test building a site similar to [Steph Ango's blog](https://stephango.com/) using Astro. The layout seemed perfect for Astro, something that could be whipped up in an afternoon as a coding exercise.

This project isn't styled yet. This is just building the very basics first as a proof of concept. The rough layout is there. It's only a little CSS and some tweaks away from being a great little blog.


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |


## Credit

This theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).
