Creating react app---

npx create-react-app my-app
npm install react-router-dom
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
 (--full  for default configuration)	


Vite---


npm create vite@latest



Setting up tailwind---

-in tailwind.config.js-

module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

-in index.css-

@tailwind base;
@tailwind components;
@tailwind utilities;


Optional---
1.) npm install firebase
create a file in src-- firebaseConfig.js

2.) Tailwind CSS IntelliSense--vscode ext
PostCSS Language Support-- vscode ext

