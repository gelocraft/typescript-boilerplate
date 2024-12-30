# Introduction

The purpose of this project is to create a TypeScript project with support for Jest and ESLint. 

See the `scripts` section of the `package.json` file to see what `npm run` commands are available.. For example, you can run:

```shell
npm run build # builds the project, and places the index.js file in `dist/index.js`.
npm start     # executes the aforementioned `index.js` file.
npm run test  # runs all tests in the `tests/` folder
```

# Installation/Setup

- Clone this repo, and `cd` into the created directory. This will be your project directory.
- Make the `setup.sh` file executable:
```shell
chmod a+x ./setup.sh
```
- Run the `setup.file`:
```shell
./setup.sh
```
- After, remove the `use_this-*` files, and reset the git repository:
```shell
rm use_this-*
rm -rf .git
git init
git add .
git commit -m "Initial commit after cloning the respository from https://github.com/shafiquejamal/create-typescript-jest-eslint-project"
```


# References
- [.gitignore file](https://github.com/github/gitignore/blob/main/Node.gitignore)
- [setup process for jest typescript eslint](https://sharvishi9118.medium.com/setting-up-typescript-eslint-jest-project-3621a6d43609)
- [Add the tsconfig.json file](https://learn.microsoft.com/en-us/visualstudio/javascript/compile-typescript-code-npm?view=vs-2022)
- [nodemon config](https://www.npmjs.com/package/nodemon)
