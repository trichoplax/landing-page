# codidact/landing-page

The Codidact project landing page. It should contain a high-level overview of what the Codidact project is about, as well as references to resources such as the  [Wiki](https://github.com/codidact/docs/wiki), [Meta](https://meta.codidact.com/), and [chat](https://discord.gg/PSr9pmn).

This site is live at https://codidact.org.
A staging environment is available at https://codidact.github.io/landing-page *(deployed via [GitHub Pages](https://github.com/codidact/landing-page/deployments) based on the `gh-pages` branch)*.

## Setting up your local development environment

-   Ensure node and npm are installed locally [(nvm recommended)](https://github.com/nvm-sh/nvm).
-   Run `npm install` to install project dependencies.
-   Run `npm run start` to start the front-end. This can be viewed by navigating to `localhost:3000` in your browser.

## Build outputs are part of the repo

After you make changes, build:

`npm run build`

This should make changes in `dist`.  Include those in your commit.

## Linting

Whilst CI tools will be used at a later date, before submitting a PR ensure your code is linted by running `npm run lint`. Any submitted PRs will be rejected if linting does not pass.

-   All formatting (except JS) is handled by Prettier (we recommend installing an auto-formatter for your IDE). The configuration is located in `.prettierrc`.
-   JS formatting and linting is handled by ESLint. JSON config resides in `.eslintrc` (to be added).
-   CSS linting handled by stylelint. JSON config in `.stylelintrc`.

## Copying

MIT license applies to source code. It does not apply to assets under
`dist/assets/img/`, particulary not to those within
`dist/assets/img/3rd-party/`.
Same applies to `src/img/`.
