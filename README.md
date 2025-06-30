# Chrome Extension (Vite + TypeScript + Tailwind)

This is a browser extension built with Vite, TypeScript, and Tailwind CSS. It is designed to make coding experience more smoother with assistance of Open AI.

## Features

- Fast development with Vite
- Fully typed with TypeScript
- Modern styling using Tailwind CSS
- Supports Manifest V3
- Modular structure for popup, content, and background scripts

## How to Setup Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```
### 2. Install Dependencies 

```bash
npm install
# or
pnpm install
# or
yarn install
```

### 3. Run Development Build 

```bash 
npm run dev
```

# Load Extension in Chrome
1. Open Chrome and go to chrome://extensions/.

2. Enable Developer Mode (toggle in the top-right).

3. Click Load unpacked.

4. Select the /dist folder generated after running npm run build.
   
# Project Structure 
.
├── .github/               → GitHub workflows (CI/CD)
├── dist/                  → Production build output (auto-generated)
├── node_modules/          → Installed dependencies (auto-generated)
├── public/                → Static assets (icons, manifest, etc.)
├── src/                   → Source code
│   ├── popup/             → Popup UI
│   ├── background/        → Background scripts
│   └── content/           → Content scripts injected into webpages
├── .gitignore             → Git ignore rules
├── .prettierrc            → Prettier config
├── components.json        → UI components config (optional)
├── index.html             → HTML entry (Vite dev)
├── manifest.json          → Extension manifest (V3)
├── package.json           → Project metadata and dependencies
├── pnpm-lock.yaml         → Lock file (optional)
├── tailwind.config.ts     → Tailwind CSS config
├── tsconfig.json          → TypeScript config
├── vite.config.ts         → Vite config
