# Yarn starter
> A project starter that includes linting, formatting, testing and Git hooks

This toolkit is using ESLint, Prettier, Husky, Lint-staged and Jest. Happy hacking!

## Installation

- Clone repository or [download zip](https://github.com/freddjah/yarn-starter/archive/master.zip)
```sh
git clone https://github.com/freddjah/yarn-starter.git
```

- Install dependencies
```sh
yarn
```

- Start building your app

## Usage example

* If you are using VSCode with the plugins [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) you'll get a lot of help when you're writing your code. Regardless of your setup, when you commit something both ESLint and Prettier will analyze for any errors and try to fix them. If it isn't possible to fix, the commit won't happen and you'll have to fix the errors manually before committing again.

* When you initiate a `git push`, your test suite will run. If there's any failed tests, the code won't be pushed and you'll have to fix the errors before pushing again. 
