# Mike Portfolio

Minimal Astro portfolio for Michele Rinaldi.

## Project Structure

```text
/
+-- public/
|   +-- favicon.ico
|   +-- favicon.svg
+-- src/
|   +-- img/
|   +-- layouts/
|   |   +-- Layout.astro
|   +-- pages/
|       +-- about.astro
|       +-- index.astro
+-- package.json
```

## Image Ordering

Images in `src/img/` are ordered by the leading number in their file name.

```text
src/img/
+-- 1_Cover_Simba.webp
+-- 2_Ragazzi.webp
+-- 5_Merch_Fiks/
|   +-- 1_Front.webp
|   +-- 2_Back.webp
```

Folders become carousel works. The folder number controls the work order, and image numbers inside the folder control the carousel order. Numbers are hidden from the titles shown on the site.

## Commands

| Command | Action |
| :-- | :-- |
| `npm install` | Installs dependencies |
| `npm run dev` | Starts the local dev server |
| `npm run build` | Builds the production site to `./dist/` |
| `npm run preview` | Previews the production build locally |
