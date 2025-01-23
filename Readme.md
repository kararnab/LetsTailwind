## Tailwind Demo

This app is a demonstration of [Tailwind CSS](https://v3.tailwindcss.com/docs/installation).

### Setup VSCode

1. Install Extension - LiveServer (Setting -> Full Reload true)
2. Install Extension - Tailwind CSS IntelliSense

### Bootstrapping (OMG, I mean tailwinding)

1. Install Tailwind CSS:
    ```sh
    npm i -D tailwindcss@3
    ```
2. Install Prettier plugin for Tailwind CSS:
    ```sh
    npm i -D prettier-plugin-tailwindcss
    ```
3. Initialize Tailwind CSS:
    ```sh
    npx tailwindcss init
    ```
4. Create the required folders and files:
    - Create `build` and `src` folders in the root of the project.
    - Add files: `src/input.css`, `build/img/{all_png}.png`, `build/index.html`, `.gitignore` (add `node_modules`).
5. Initialize npm:
    ```sh
    npm init -y
    ```
6. Set up HTML boilerplate:
    - Go to `build/index.html` in VSCode, type `!` (Emmet) -> Autocomplete to get an HTML boilerplate.
    - Learn more about Emmet in VSCode, like `button#mobile.text-3xl.sm:hidden` means a button tag with id `mobile` and classes `text-3xl`, `sm:hidden`. Press tab to autocomplete.
7. Configure VSCode settings:
    - Go to File -> Preferences -> Settings and change as required under workspace. The configurations will be auto-populated in `.vscode/settings.json`, which can be used by teammates (useful when working in bigger teams).

### Scripts

- To build Tailwind CSS:
    ```sh
    npm run tailwind
    ```
- To format HTML files using Prettier:
    ```sh
    npm run prettier
    ```
- To build the CSS for production, run the following command:
    ```sh
    npm run build:css
    ```

### Hosting
You can host your site in multiple cloud providers like
1. [Vercel](https://vercel.com/)
2. [Render](https://render.com/)
3. [Heruku](https://www.heroku.com/)
4. [Google App Engine](https://cloud.google.com/appengine)
5. [AWS ElasticBeanStack](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html)

### Contributing
We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Clone your forked repository.
3. Create a new branch for your feature or bugfix.
4. Make your changes and commit them.
5. Push your changes to your forked repository.
6. Submit a pull request to the main repository.