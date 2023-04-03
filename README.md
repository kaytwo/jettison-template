# Jettison
A few clicks to escape from Instagram and self-host a copy of your own content.

This template is meant to be used via the [Jettison](https://jettison.kaytwo.org) webapp. Once you've created your own copy, basic instructions about how to use this template are below.

## 🚀 Project Structure

This website is built using the [Astro](https://astro.build) web framework.
Inside this project, you'll see the following folders and files:

```
/
├── public/
│   └── jettison.png
├── src/
│   ├── assets/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   ├── components/
│   │   └── Post.astro
│   ├── data/
│   │   └── posts.json
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       └── posts/
│           └── [post].astro
└── package.json
```

## Jettison specifics

After you've deployed the empty template, the Jettison webapp populates `posts.json` with metadata about all of your posts, and `src/assets` with all of your photos. By default, Jettison deploys to Vercel, but you can just as easily deploy this repository to [Netlify](https://netlify.com), [Cloudflare Pages](https://pages.cloudflare.com), or any other static hosting provider.

## Astro details

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets can be placed in the `public/` directory. This template uses Astro's [optimized asset support](https://docs.astro.build/en/guides/assets/), any images that could benefit from optimization should be placed in `src/assets/`.

## 🧞 Commands

To view local changes before pushing them (which causes an automated build and deploy to your public website), you can run the commands below. All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more about how to customize this template?

Check out the  [Astro documentation](https://docs.astro.build).