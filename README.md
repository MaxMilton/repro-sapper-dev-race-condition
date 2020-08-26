# Repro for Sapper `dev` Build Race Condition

The only changes are:

- `package.json` - pin sapper to version `0.28.1`
- `rollup.config.js` - force the client build to take a long time via novel rollup plugin
