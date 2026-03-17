# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.











add package-lock.json
"homepage": "https://RikenVaghani.github.io/noteapp",


git init     
git remote add origin https://github.com/RikenVaghani/noteapp.git

git add .
git commit -m "first add"

git push -u origin main 



npm install --save gh-pages



package.json
add below 2 line in scripts

+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",















