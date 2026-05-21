# nikotesla.net

Minimalist landing page showing "Niko Tesla" in the middle, styled with premium dark theme aesthetics. Built with Astro and configured for GitHub Pages deployment.

## 🛠️ Getting Started

### 1. Requirements
Ensure you are using **Node.js v22** or higher. If you use NVM, switch to Node 22:

```sh
nvm use 22
```
*(If v22 is not installed, run `nvm install 22` first).*

### 2. Install Dependencies
Install all package dependencies from the project root:

```sh
npm install
```

### 3. Run in Dev Mode
Start the local development server:

```sh
npm run dev
```
Once started, open [http://localhost:4321/](http://localhost:4321/) in your browser.

### 4. Build for Production
Generate the static production build:

```sh
npm run build
```
The output will be created inside the `dist/` directory.

## 🚀 Deployment

The site is configured to automatically build and deploy to GitHub Pages on every push to the `master` branch using the GitHub Actions workflow in `.github/workflows/deploy.yml`.
