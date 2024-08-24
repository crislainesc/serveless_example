
<div align="center">
  <h1> <img alt="code-image" width="1100px" src=".github/workflows/assets/banner.jpeg"> </h1>
  <h2> Serveless Example </h2>
  <h3>
Serverless - AWS Node.js Typescript</h3>
  <p>
    <a href="https://github.com/crislainesc">
      <img alt="Made by Crislaine" src="https://img.shields.io/badge/solved%20by-Crislâine%20Santos-blueviolet?style=plastic">
    </a>
   <br/>
    <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/crislainesc/serveless_example?color=blue&style=plastic">
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/crislainesc/serveless_example?style=plastic"/>
    <a href="https://opensource.org/licenses/MIT">
      <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=plastic">
    </a>
  </p>
</div>

### 📖 About the project
This project has been generated using the `aws-nodejs-typescript` template from the [Serverless framework](https://www.serverless.com/).

For detailed instructions, please refer to the [documentation](https://www.serverless.com/framework/docs/providers/aws/).

### ✨ Features
- Serverless lambda
### 💻 Technologies
- [json-schema-to-ts](https://github.com/ThomasAribart/json-schema-to-ts) - uses JSON-Schema definitions used by API Gateway for HTTP request validation to statically generate TypeScript types in your lambda's handler code base
- [middy](https://github.com/middyjs/middy) - middleware engine for Node.Js lambda. This template uses [http-json-body-parser](https://github.com/middyjs/middy/tree/master/packages/http-json-body-parser) to convert API Gateway `event.body` property, originally passed as a stringified JSON, to its corresponding parsed object
- [@serverless/typescript](https://github.com/serverless/typescript) - provides up-to-date TypeScript definitions for your `serverless.ts` service file
### ▶️ Running The Project
Depending on your preferred package manager, follow the instructions below to deploy your project.

> **Requirements**: NodeJS `lts/fermium (v.14.15.0)`. If you're using [nvm](https://github.com/nvm-sh/nvm), run `nvm use` to ensure you're using the same Node version in local and in your lambda's runtime.

#### Using NPM

- Run `npm i` to install the project dependencies
- Run `npx sls deploy` to deploy this stack to AWS

#### Using Yarn

- Run `yarn` to install the project dependencies
- Run `yarn sls deploy` to deploy this stack to AWS
### 📝 License

This project is under the MIT license. See the [LICENSE](/LICENSE) file for more details.

<div align="center">
  <p>🚀 Made by <a href="https://github.com/crislainesc">Crislâine Santos</a> </p>
</div>
