# React Boilerplate

## Flow:

1. `npm run husky:init`
2. `npm install`
3. `npm start`

## Tech Stack:

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/guide/)
- [SCSS](https://sass-scss.ru/guide/) (by default)

## Package Managers:

- npm

## Code Quality:

- [ESLint](https://eslint.org/)
- [Stylelint](https://stylelint.io/user-guide/get-started)
- [Commitlint](https://commitlint.js.org/) and [Husky](https://typicode.github.io/husky/)
- [Prettier](https://prettier.io/) and [Editorconfig](https://editorconfig.org/)
- [Vitest](https://vitest.dev/guide/) and [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

## Architecture:

- [Feature-Sliced Design](https://feature-sliced.design/) (by default)

## Prerequisites:

- [Node.js](https://nodejs.org/) >=18

[Commands](./package.json)

| Command                          | Description                                                                                       |
| -------------------------------- | ------------------------------------------------------------------------------------------------- |
| `npm install`                    | Installs dependencies                                                                             |
| `npm start`                      | Starts local dev server at port specified in [vite config](./vite.config.ts)                      |
| `npm run prebuild`               | Automatically runs directly before the command `npm run build`, cleans up `dist` folder           |
| `npm run build`                  | Builds project                                                                                    |
| `npm run preview`                | Starts local server to serve `dist` folder on specified port                                      |
| `npm run lint:js`                | Runs Javascript and Typescript linting                                                            |
| `npm run lint:style`             | Runs CSS and SCSS linting                                                                         |
| `npm run lint`                   | Runs `npm run lint:js` and `npm run lint:style`                                                   |
| `npm run test:unit`              | Runs unit tests using Vitest                                                                      |
| `npm run prehusky:install`       | Automatically runs directly before the command `npm run husky:install`, cleans up `.husky` folder |
| `npm run husky:install`          | Installs Husky                                                                                    |
| `npm run set-git-hook:prepush`   | Sets prepush hook                                                                                 |
| `npm run set-git-hook:precommit` | Sets precommit hook                                                                               |
| `npm run husky:init`             | Runs `npm run husky:install`, `npm run set-git-hook:prepush` and `npm run set-git-hook:precommit` |
