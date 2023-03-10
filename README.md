# Welcome to [Astro](https://astro.build)

Astro is an all-in-one web framework for building fast, content-focused websites.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/s/github/withastro/astro/tree/latest/examples/basics)

## Key Features

- Section titled Key Features
- Component Islands: A new web architecture for building faster websites.
- Server-first API design: Move expensive hydration off of your usersβ devices.
- Zero JS, by default: No JavaScript runtime overhead to slow you down.
- Edge-ready: Deploy anywhere, even a global edge runtime like Deno or Cloudflare.
- Customizable: Tailwind, MDX, and 100+ other integrations to choose from.
- UI-agnostic: Supports React, Preact, Svelte, Vue, Solid, Lit and more.

> π§βπ **Seasoned astronaut?** Delete this file. Have fun!

![basics](https://user-images.githubusercontent.com/4677417/186188965-73453154-fdec-4d6b-9c34-cb35c248ae5b.png)

## π Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
βββ public/
β   βββ favicon.svg
βββ src/
β   βββ components/
β   β   βββ Card.astro
β   βββ layouts/
β   β   βββ Layout.astro
β   βββ pages/
β       βββ index.astro
βββ package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## π§ Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                             |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Installs dependencies                              |
| `npm run dev`          | Starts local dev server at `localhost:3000`        |
| `npm run build`        | Build your production site to `./dist/`            |
| `npm run preview`      | Preview your build locally, before deploying       |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro preview` |
| `npm run astro --help` | Get help using the Astro CLI                       |

## π Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
