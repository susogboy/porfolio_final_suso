## Project Structure

     ┣ 📂public
     ┃ ┣ 📜CertificadoCursoPropioCiber_20 23_Jesús Fernández Santiago.pdf
     ┃ ┣ 📜CiscoCertificado_2023_Jesus Fernandez Santiago.pdf
     ┃ ┣ 📜CV-INGLES-SinFoto-JesusFernandez.pdf
     ┃ ┣ 📜diplomaPythonIBM.pdf
     ┃ ┣ 📜favicon.webp
     ┃ ┣ 📜flag_madrid.png
     ┃ ┣ 📜me.jpeg
     ┃ ┣ 📜snap_laptop.png
     ┃ ┣ 📜snap_mobile.png
     ┃ ┗ 📜snap_project.png
     ┃ ┗ 📜snap-items.png
     ┃ ┣ 📜snap-md.png
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
     ┃ ┃ ┃ ┗ 📜home-susogboy.md
     ┃ ┃ ┣ 📂certificates
     ┃ ┃ ┃ ┗ 📜0webDevelopmentPython.md
     ┃ ┃ ┃ ┗ 📜1pythonFullStack.md
     ┃ ┃ ┃ ┗ 📜2Cybersecurity.md
     ┃ ┃ ┃ ┗ 📜3Cisco.md
     ┃ ┃ ┣ 📂contact
     ┃ ┃ ┃ ┣ 📜email.md
     ┃ ┃ ┃ ┣ 📜github.md
     ┃ ┃ ┃ ┣ 📜linkedin.md
     ┃ ┃ ┃ ┗ 📜malt.md
     ┃ ┃ ┣ 📂projects
     ┃ ┃ ┃ ┗ 📜dalhia.md
     ┃ ┃ ┣ 📂studies
     ┃ ┃ ┃ ┣ 📜dam.md
     ┃ ┃ ┃ ┗ 📜tfg.md
     ┃ ┃ ┣ 📂works
     ┃ ┃ ┃ ┣ 📜ey.md
     ┃ ┃ ┗ 📜index.astro
     ┃ ┗ 📜env.d.ts
     ┣ 📜.gitattributes
     ┣ 📜.gitignore
     ┣ 📜astro.config.mjs
     ┣ 📜LICENSE
     ┣ 📜package-lock.json
     ┣ 📜package.json
     ┣ 📜README.md
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
