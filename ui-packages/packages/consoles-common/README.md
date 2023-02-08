# Kogito Consoles-Common

Kogito **consoles-Common** Package consist of all the common _**layouts**_,_**Pages**_,_**graphql codegen**_ and _**Environments**_ used across all the packages.

The common Layouts are :

  * AboutModalBox
  * BrandContext
  * PageLayout
  * PageSectionHeader
  * PageTitle
  * PageToolbar

The common pages are :

  * KeycloakUnavailablePage
  * NoData
  * PageNotFound
  * ServerUnavailablePage

The common Environments are :

  * Authentication Environment
  * Context


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







