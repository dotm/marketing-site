TODO:

- Collect email newsletter
- Connect contact us to Google form

shop:
- product list based on rss: search/sort/filter, product grid
  - product grid: image, name, price and discount, cta (contact us or add to cart)
- product detail page:
  - images + videos, name, price and discount, short description, stock available, cta (contact us or add to cart)
  - long description, additional info, reviews

review:
- banner
- privacy notice
- review color and spacing
- check with seo tools

other (optional):
- color:
  - menu bg color
  - menu text color
  - bg color
  - primary color
  - body text color
  - h1-6: shades of one color (most contrast with bg to less)
  - button bg
  - button text
- blog post detail: related posts
- CTA section
- bento grids
- pricing section
- newsletter section
- statistics section
- our team section
- logo cloud
- FAQs

ecommerce (optional):

- wishlist
- cart
- checkout (shipping and payment)
- thank you page

account (optional):

- account sign up, sign in, sign out.
- account details: wishlist, order history, addresses, contact details (email, phone), payment methods, etc.

## Usage

- copy and adjust astro.config.mjs
- add plugins: npx astro add sitemap
- npm install -D @tailwindcss/typography
  - then add require('@tailwindcss/typography') in tailwind.config.mjs
- copy components and pages as necessary
  - you can also add new and modify existing components
- customize: url, logo, favicon, copy, fonts, color scheme
- setup google analytics
- test and then deploy

# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
