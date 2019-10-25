Basic Readme to get the steps out there. Will loop back to build on this.

# To use

1. `yarn` in this directory
2. `yarn build` or `yarn build:dev` (only difference is dev is not minified)
3. Copy `package.json` and `dist` folder to the `node_modules` of the RN app you want to test with
4. Import this plugin and call `.use(myPlugin())` on reactotron (myPlugin would be whatever you name the default import)
5. If you have a feature (see source code) call that when needed to wire up to whatever you are trying to monitor
