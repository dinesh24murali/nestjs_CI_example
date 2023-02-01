# nestjs_CI_example

- This repo has a simple [nestJS](https://docs.nestjs.com/) backend, and a [svelte](https://svelte.dev/) frontend.

- In this [Pull request](https://github.com/dinesh24murali/nestjs_CI_example/pull/2) we have created a github action that runs the backend test cases and backend eslint

- This repo uses [yarn Workspaces](https://classic.yarnpkg.com/lang/en/docs/workspaces/).

- Both the backend and frontend will have individual `package.json` files

## Setup the project

- Run `yarn install` from the root of the repo or withing backend or frontend folders

- From the root of the repo run the following command to run the backend server
```
yarn server
```
- From the root of the repo run the following command to run the frontend server
```
yarn web-start
```
