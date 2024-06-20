There are Git Hooks with Husky library

# Getting Started

There are only 3 git hook examples here:

| Git hook   | Description |
| ---------- | :--------- |
| commit-msg | It takes a single parameter, the name of the file that holds the proposed commit log message.  |
| pre-commit | It takes no parameters, and is invoked before obtaining the proposed commit log message and making a commit  |
| pre-push   | This hook can be used to prevent a push from taking place, the hook is called with two parameters.  |

## How to use

You can use [Git Hooks](https://git-scm.com/docs/githooks) manually in .git directory of your repository
or working with [Husky library](https://github.com/typicode/husky), insert files in husky directory of your repository

### With Husky

Firstly, you need to [install Husky](https://www.npmjs.com/package/husky)

```
yarn add --dev husky
// or
pnpm add --save-dev husky
// or
npm install --save-dev husky
```

The next steps are described in detail on the [official website](https://typicode.github.io/husky/) of the project.

Happy coding...