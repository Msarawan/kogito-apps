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


### Install dependencies

To install dependencies you need to have yarn installed globally and run in the terminal:
```
yarn install
```

### Build the project
```
yarn run build:prod
```
Builds the app for production to the dist folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.