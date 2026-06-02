# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

## Deploying to Render

This project uses Vite and builds static assets into the `dist` folder. To deploy on Render (static site):

1. Push the repository to GitHub and connect the repo in the Render dashboard.
2. Create a new "Static Site" on Render and point it to the `main` branch.
3. Use the build command: `npm run build` and the publish directory: `dist`.
4. Render will run the build and serve the `dist` folder.

If you prefer a simple Node static server for previewing, the `start` script uses `serve -s dist` and the project includes a `serve` dependency in `package.json`.
