# Electron
Electron App

- [Electron](https://www.electronjs.org/docs/)
- [Tauri](https://tauri.app/) is an alternative to Electron.

## 1. Fundaments & Setup

- Introduction and Showcase
- Electron Arquitecture

Renderer Layer: Destkop frontend
Main Layer: Server Backend
Preload Layer: 

- Figma: [Rotion](https://www.figma.com/file/oDWCeuEWPkoSJytDBuTax5/Rotion-(Curso-de-Electron)?type=design&node-id=0-1)
- Application Setup
    - [electron-vite](https://evite.netlify.app/) / [Github](https://github.com/alex8088/electron-vite)
    - [electron-app](https://github.com/daltonmenezes/electron-app)

Create the project:
```sh
npm create @quick-start/electron
```
Select the follow options:
```sh
Need to install the following packages:
  @quick-start/create-electron@1.0.12
Ok to proceed? (y) 
✔ Project name: … Rotion
✔ Package name: … rotion
✔ Select a framework: › react
✔ Add TypeScript? … No / Yes
✔ Add Electron updater plugin? … No / Yes
✔ Enable Electron download mirror proxy? … No / Yes

Scaffolding project in /home/atmark/Projects/Electron/Electron/Rotion...

Done. Now run:

  cd Rotion
  npm install
  npm run dev
```

- Add External Text Fonts

    - [Inter](https://fonts.google.com/specimen/Inter)
    - Press "F12" to view the developer inspection mode.

- TailwindCSS Setup
Install the development dependencies:
```sh
npm i -D tailwindcss postcss autoprefixer
```
Go to the renderer directory:
```sh
cd /src/renderer
```
Create the tailwind.config.js:
```sh
npx tailwindcss init -p
```

Install the VScode Extensions: [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) and [PostCSS Language Support](https://marketplace.visualstudio.com/items?itemName=csstools.postcss).

- TypeScript & ESLint

Install the developments dependecies:
```sh
npm i -D @rocketseat/eslint-config
```

Fix all the ESLint errors:
```sh
npm run lint
```

- Application Icons and Name

Use the Figma plugin: icns/ico Generator.

- Global Styles and Colors

To create the colors pallet you can use the Figma plugin: Foundation Color Generator.

- Application Skeleton

Install the dependecies (clsx, phosphor-react and [cmdk](https://cmdk.paco.me/)):
```sh
npm i clsx phosphor-react cmdk
```

## 2. Application Construction
- Routing Setup
- Layout Setup
- Document Page
- Text Editor
- Flexible Sidebar

## 3. Communication and Storage
- Example of IPC communication
- Setting up React Query
- Insights on storage
- Setting up the store
- Structuring IPC Handlers
- Structure of CRUD via IPC
- Connecting to the store
- Creating a new document
- Document preview
- Document removal
- Document changes
## 4. Electron Features
- Creating the tray menu
- Creating document by the tray
- Configuring the hotkeys
- Search in the application

## 5. Build aand Distribution

- Sign and Distribution
- Build Settings
- Multi-platform CI Flow