# Professional Portfolio

A modern, responsive portfolio website built with HTML and Tailwind CSS.

## Tech Stack

- HTML5
- Tailwind CSS v3
- Google Fonts (Inter)

## Local Development

To run this project locally:

```bash
npx http-server
```

The site will be available at `http://localhost:8000`

## Deployment to Vercel

This project is ready to be deployed to Vercel. Follow these steps:

### Option 1: Deploy from GitHub (Recommended)

1. Push your repository to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect the static site
6. Click "Deploy"

### Option 2: Deploy with Vercel CLI

1. Install the Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Run from the project directory:
   ```bash
   vercel
   ```

3. Follow the CLI prompts to deploy

### Configuration

The `vercel.json` file contains the deployment configuration. The root `index.html` is automatically served as the homepage.

## Project Structure

```
.
├── index.html      # Main portfolio page
├── package.json    # Project metadata and scripts
├── vercel.json     # Vercel deployment configuration
├── .gitignore      # Git ignore rules
└── README.md       # This file
```

## License

MIT
