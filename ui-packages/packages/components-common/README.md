# Kogito Components-common

The kogito **components-common** package consist of all the common components used by both **Management-console** and **Task-console**.

#### The Common Components Shared across both Consoles are listed below :

 * DataTable
 * EndpointLink
 * FormFooter
 * FormNotification
 * Form Renderer
 * ItemDescriptor
 * KogitoEmptyState
 * KogitoSpinner
 * LoadMore
 * ServeErrors
 * utils


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

