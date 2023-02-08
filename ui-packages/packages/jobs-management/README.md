# Kogito Jobs Management

Kogito jobs-management package consist of some common **Api's** and **envelope** used across both managment-console and runtime-tools webapp. 

### The common Api's used are :

 * JobsManagementApi
 * JobsManagementChannelApi
 * JobsManagementDriver
 * JobsManagementEnvelopeApi

### The common envelop used are :

 * JobsManagementEnvelopeApi
 * JobsManagementEnvelopeApiImpl
 * JobsManagementEnvelopeContext
 * JobsManagementEnvelopeView
 * JobsManagementEnvelopeViewDriver


## Building from source

- Check out the source:
```
git clone git@github.com:kiegroup/kogito-apps.git
```

- Install Node and NPM package manager

See detailed instructions [here](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) for your OS.

- Install [Yarn](https://classic.yarnpkg.com/)
```bash
cd kogito-apps/ui-packages
npm install -D yarn
```

- Install projects dependencies using Yarn
```bash
cd kogito-apps/ui-packages
yarn install
```

Build with Yarn:
```bash
cd kogito-apps/ui-packages
yarn run init

#prod
yarn run build:prod
```


