# React + Vite

## About this project

This project is a modern web application built with React and Vite. It features fast development with Hot Module Replacement (HMR), optimized build performance, and a minimal setup to get started quickly. The project includes ESLint for code quality and supports both Babel and SWC for fast refresh during development.

## How to start

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Start the development server:**
   ```sh
   npm run dev
   ```
3. Open your browser and navigate to the local server URL (usually `http://localhost:5173/`).

4. To build the project for production:
   ```sh
   npm run build
   ```

5. To preview the production build:
   ```sh
   npm run preview
   ```

---
## Features

- ⚡️ Fast development with Vite and HMR
- ⚛️ Modern React (JSX, hooks, functional components)
- 🧹 ESLint integration for code quality
- 🔥 Supports both Babel and SWC for fast refresh
- 🎨 Custom assets and images in `public/`
- 📦 Easy build and preview commands

## Folder Structure

```
├── public/               # Static assets
│   ├── 20250505_1316_Futuristic Fashion Pose_remix_01jtfpfprqen293p9pr685wnqw.png
│   ├── bg.png
│   ├── girlbg.png
│   ├── imag.png
│   ├── logo18.png
│   ├── pricedown.otf
│   ├── ps5.png
│   └── sky.png
├── src/                  # Source code
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html            # Main HTML file
├── package.json          # Project metadata and scripts
├── vite.config.js        # Vite configuration
├── eslint.config.js      # ESLint configuration
└── README.md             # Project documentation
```

## Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [ESLint](https://eslint.org/)
- [Babel](https://babeljs.io/) / [SWC](https://swc.rs/)

## Getting Started

Follow the steps below to set up and run the project locally.

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd GTAVI-main
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Start the development server:**
   ```sh
   npm run dev
   ```
4. Open your browser and navigate to the local server URL (usually `http://localhost:5173/`).
5. **Build for production:**
   ```sh
   npm run build
   ```
6. **Preview the production build:**
   ```sh
   npm run preview
   ```
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
