# **Kogito Process-Details**

The process-details package consist of some common components used in Management-console.
<br />
<img src="./docs/ProcessDetails.png" width="900px" height="450px">
 
The components used are :

 * JobActionKebab
 * JobsPanel
 * ProcessDetails
 * ProcessDetailsErrorModal
 * ProcessDetailsMilestonesPanel
 * ProcessDetailsNodeTrigger
 * ProcessDetailsPanel
 * ProcessDetailsTimelinePanel
 * ProcessDiagram
 * ProcessVariables
 * SwfCombinedEditor

  For the details explination about all these components check management-console-webapp [Readme](../management-console-webapp/README.md)


## **Building from source**

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