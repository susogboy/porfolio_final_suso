## Project Structure

/TODO: cambiar la estructura

     ┣ 📂public
     ┃ ┣ 📜cv-20240219.pdf
     ┃ ┣ 📜favicon.webp
     ┃ ┣ 📜gl_flag_128x.png
     ┃ ┣ 📜profile.webp
     ┃ ┣ 📜snap-md.png
     ┃ ┣ 📜snap_laptop.webp
     ┃ ┗ 📜snap_mobile.webp
     ┣ 📂src
     ┃ ┣ 📂components
     ┃ ┃ ┣ 📜Card.astro
     ┃ ┃ ┣ 📜ContactCard.astro
     ┃ ┃ ┣ 📜Container.astro
     ┃ ┃ ┣ 📜Footer.astro
     ┃ ┃ ┗ 📜Header.astro
     ┃ ┣ 📂layouts
     ┃ ┃ ┣ 📜AccordionLayout.astro
     ┃ ┃ ┗ 📜BaseLayout.astro
     ┃ ┣ 📂pages
     ┃ ┃ ┣ 📂about
     ┃ ┃ ┃ ┗ 📜about.md
     ┃ ┃ ┣ 📂blogs
     ┃ ┃ ┃ ┗ 📜home-mmouzo.md
     ┃ ┃ ┣ 📂certificates
     ┃ ┃ ┃ ┗ 📜backend2022.md
     ┃ ┃ ┣ 📂contact
     ┃ ┃ ┃ ┣ 📜email.md
     ┃ ┃ ┃ ┣ 📜github.md
     ┃ ┃ ┃ ┣ 📜linkedin.md
     ┃ ┃ ┃ ┗ 📜telegram.md
     ┃ ┃ ┣ 📂projects
     ┃ ┃ ┃ ┗ 📜spotfilm.md
     ┃ ┃ ┣ 📂studies
     ┃ ┃ ┃ ┣ 📜dam.md
     ┃ ┃ ┃ ┗ 📜smr.md
     ┃ ┃ ┣ 📂works
     ┃ ┃ ┃ ┣ 📜work1.md
     ┃ ┃ ┃ ┗ 📜work2.md
     ┃ ┃ ┗ 📜index.astro
     ┃ ┗ 📜env.d.ts
     ┣ 📜.gitattributes
     ┣ 📜.gitignore
     ┣ 📜LICENSE
     ┣ 📜README.md
     ┣ 📜astro.config.mjs
     ┣ 📜package-lock.json
     ┣ 📜package.json
     ┣ 📜tailwind.config.mjs
     ┗ 📜tsconfig.json

## Installation

#### Commands

All commands are run from the root of the project, from a terminal:

| Command         | Action                                      |
| :-------------- | :------------------------------------------ |
| `npm install`   | Installs dependencies                       |
| `npm run dev`   | Starts local dev server at `localhost:4321` |
| `npm run build` | Build your production site to `./dist/`     |

## Tech Stack

**JAVASCRIPT FRAMEWORKS**

- [Astro](https://astro.build/ "Astro")

**UI FRAMEWORKS**

- [TailwindCSS](https://tailwindcss.com/ "TailwindCSS")
- [daisyUI](https://daisyui.com/ "daisyUI")

## Use and editing of content

All content is in Markdown files classified in directories in `/src/pages`

![alt text](https://github.com/susogboy/porfolio_final_suso.git)

To edit the content simply add, delete or modify the .md files.

### Adding or Removing a field

**Add a new field:**

Go to `Container.astro` in` src/components/`.

To add a new field, add a new `<AccordionLayout />` component with the appropriate properties and the corresponding child component.
