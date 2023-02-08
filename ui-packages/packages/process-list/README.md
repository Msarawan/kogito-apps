# Kogito Process-List

![ProcessListPage](./docs/processlist.png "ProcessListPage")

The Process-List shows details of the process instances. Initially it loads only the parent process instances. The following are the details shows in the list :

 * Checkbox
 * Process name
 * State of the process
 * when was the process created
 * when was the process updated
 * a kebab button to provide process-management functions

The list has a toggle button on the left end, which when toggled would load all the child process instances of that parent process instance. The child process instance also has a similar sturcture as mentioned above.

For detailed Explination about the working of Process-List pacakge, please check the readme file of Management-console-webapp [README](../management-console-webapp/README.md) file.
<br />

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