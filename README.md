# Travel with Pramo

A Vite-powered static website for the Travel with Pramo Sri Lankan travel brand.

## Run locally

Requirements: Node.js 20.19+ (or a compatible newer Node release) and npm.

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

Vite outputs the production site to `dist/`.

## Deploy to Vercel

1. Upload this project folder to a GitHub repository.
2. Import the repository in Vercel.
3. Use the Vite framework preset.
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.

The `esbuild` dependency is intentionally not pinned in `package.json` because this project does not directly use it. `.npmrc` enables legacy peer resolution as requested; if you later add packages, remove that setting if possible and resolve any actual peer conflicts directly.

The inquiry form is currently a front-end demo and does not send messages. Connect an email service or backend before using it for real bookings.
