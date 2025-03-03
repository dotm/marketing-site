Usage:

- npm create astro@latest your-project-name -- --template dotm/marketing-site
- Find and replace all marketing-site to your-project-name
- Find and replace all Your Company to your real company name
- npm install
- Adjust astro.config.mjs and src/constenum.ts
- Add plugins if necessary: npx astro add sitemap
- Customize:
  - mandatory:
    - copywriting and images on all pages (mandatory)
    - Use https://flowbite.com/icons for HomeFeatures and HomeBlogEntrance icons
      - Or just remove the icons to save time
    - comment out HomeTestimonials and footer's social media if you don't have it yet
  - low priority: company logo (can be commented out), favicon, fonts, color scheme
- Create a GMail account
- Create a google form for email newsletter subscription (email marketing)
  - Add this in src/constenum.ts
- Create a google form for contact us
  - Add this in src/constenum.ts
- Make some SEO-optimized blog posts with good copywriting and sales psychology
- Setup google analytics
- Review:
  - banner
  - privacy notice
  - color and spacing
  - check with seo tools (Lighthouse, etc.)
- Test and then deploy

shop:
- product list based on rss: search/sort/filter, product grid
  - product grid: image, name, price and discount, cta (contact us or add to cart)
- product detail page:
  - images + videos, name, price and discount, short description, stock available, cta (contact us or add to cart)
  - long description, additional info, reviews

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
