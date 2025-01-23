## Tailwind Demo

This app is a demonstration of tailwind

### Setup VSCode
1. Install Extension - LiveServer (Setting -> Full Reload true)
2. Install Extension - Tailwind CSS IntelliSense

### Bootstrapping (OMG, I mean tailwinding)
1. npm i -D tailwindcss@3
2. npm i -D prettier-plugin-tailwindcss
3. npx tailwindcss init
4. Create 2 new folders `build` and `src` in root of the project
5. Add files input.css, img/{all_png}.png, index.html, .gitignore (add node_modules)
6. npm init -y
7. Go to index.html (in VSCode), type ! (Emmet) -> Autocomplete to get a html boilerplate
8. Learn more about emmets in vscode like button#mobile.text-3x1.sm:hidden means button tag with id mobile and classes text-3xl, sm:hidden, press tab to autocomplete