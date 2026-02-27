# Handmade By July

A small, sunny website to showcase handmade pieces sewn by July – totes, scrunchies, home details, and more.

## Project structure

- `index.html` – main one-page site with sections for pieces, fabrics, reviews, and contact.
- `styles.css` – custom styling and layout.
- `script.js` – small enhancements (mobile navigation + smooth scrolling).
- `package.json` – optional helper scripts for running a local dev server.

## Using your logo

The header is already set up to display your logo:

- Create a folder called `assets` inside this project (at the same level as `index.html`).
- Copy your logo image into that folder and name it `logo.png`.
- If you prefer a different name or format, update the `<img>` tag in `index.html` accordingly.

```html
<img src="./assets/logo.png" alt="Handmade By July logo – hand-painted sun" />
```

## Updating content

You can safely edit the text directly in `index.html`:

- **Pieces section** – adjust the example pieces or add/remove cards.
- **Fabrics section** – list the materials you actually love using.
- **Reviews section** – replace the sample quotes with real messages from friends/customers.
- **Contact section** – set your real Instagram handle and preferred email.

No JavaScript changes are required for simple content edits.

## Run locally

From the `handmade-by-july` folder:

```bash
npm install
npm run dev
```

This uses `npx serve` to serve the static files. Open the printed URL (usually `http://localhost:3000` or `http://localhost:3001`) in your browser.

If you prefer, you can also open `index.html` directly in a browser without running any commands.

## Preparing a new GitHub repository

1. Create a new repository on GitHub named `handmade-by-july` (do not add any files from GitHub's UI).
2. On your computer, in a terminal:

   ```bash
   cd path/to/handmade-by-july
   git init
   git add .
   git commit -m "Initial Handmade By July website"
   git branch -M main
   git remote add origin git@github.com:YOUR_USERNAME/handmade-by-july.git
   git push -u origin main
   ```

   Replace `YOUR_USERNAME` with your GitHub username.

## Deploying to Vercel

Once the repository is on GitHub:

1. Go to the Vercel dashboard and choose **New Project**.
2. Import the `handmade-by-july` GitHub repository.
3. Framework preset: choose **Other** (this is just a static site).
4. Set **Root Directory** to `/` (or the default, if this repo only contains this project).
5. Leave build settings empty/automatic – Vercel will detect the `index.html` and serve it as a static site.
6. Click **Deploy**.

Vercel will give you a public URL (you can later connect a custom domain if you want). You can place this link on your Instagram profile so people can see your pieces, fabrics, and reviews.

# handmade-by-july
