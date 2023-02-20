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