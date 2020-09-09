# Typescript Starter Project

This is bare minimum project starter for Typescript with Node.js. 

This starter offers automatic code reloading for development and it uses `ts-node` and `nodemon` to implement that.

`Eslint` is used for code linting and `Prettier` for code formatting. There is tight separation of concern and all stylistic and formatting related rules are turned off from `eslint` and handled with `prettier`.

`Husky` pre-push hook is used for enforcing linting and formatting on `git push`. This `pre-push` hook can be removed from `package.json` if not needed. 

## Scripts

### npm run start:dev

Start `ts-node` development server

### npm run build

Creates production Javascript build to `/build`-directory

### npm run clean 

Removes content from production build directory `/build`

### npm run lint

Does code linting check with `eslint`

### npm run lint-and-fix

Does code linting check with `eslint` and tries to autofix warnings and errors.

### npm run prettier-format

Does code formatting with `prettier`