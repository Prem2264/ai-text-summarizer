# AI Text Summarizer — Generative AI Mini Project

## Features
- Accepts a paragraph of text.
- Uses a pre-trained Hugging Face summarization model.
- Generates a short summary.
- Displays original and summary word counts.
- Calculates percentage reduction.
- Runs in the browser, so no Python server is required.

## Run locally
1. Install Node.js.
2. Open this folder in VS Code.
3. Run:
   npm install
   npm run dev
4. Open the local URL shown by Vite.

## Deploy on Vercel
1. Upload this project to GitHub.
2. Import the GitHub repository into Vercel.
3. Framework preset: Vite.
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.

## Deploy on Netlify
1. Upload the project to GitHub and import it into Netlify.
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Deploy.

## Note
The first summary may take longer because the browser downloads the pre-trained model. Later runs can use the browser cache.
