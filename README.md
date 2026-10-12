# Sanjai Birthday Surprise

A static, interactive birthday website packaged as a Vite project for local development and Vercel deployment.

## Run in VS Code

1. Extract this ZIP file.
2. Open the extracted `Sanjai_Birthday_Vite` folder in VS Code.
3. Open Terminal → New Terminal.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL printed by Vite (usually http://localhost:5173).

## Test production build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Push the contents of this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Vercel should detect Vite automatically. Use build command `npm run build` and output directory `dist`.
4. Click **Deploy**.

The photos are stored in `public/photos`, so Vite copies them into the production build. Keep filenames unchanged because the HTML refers to them.
