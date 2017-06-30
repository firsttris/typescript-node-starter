## minimal typescript-node-starter

- [**Typescript**](https://www.typescriptlang.org/) Javascript that scales (ES++ with types)
- [**Jest**](https://facebook.github.io/jest/) for testing, mocking and coverage report
- [**Webpack**](https://webpack.js.org/) module bundler
- [**Docker**](https://www.docker.com/) create container

## script jobs
* you have to run one babel-build before you can run the dev server
```bash
npm run / yarn
dev-server ----- run dev server, with hot-reload
webpack-build -- creates bundled webpack build
babel-build ---- create transpiled babel build
test ----------- runs tests with coverage reports
test-watch ----- runs tests with coverage & watch
docker-build --- build docker image
docker-up ------ run docker container in dev mode
```
#### Sources
##### Offical TypeScript-Node-Starter:
https://github.com/Microsoft/TypeScript-Node-Starter
##### The definitive guide to TypeScript and possibly the best TypeScript book
https://basarat.gitbooks.io/typescript/docs/quick/nodejs.html