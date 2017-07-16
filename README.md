Template to bundle resources in hot-loader for NodeJS Express Typescript project

.ts -> [tsc target:es6] -> .js(es6) -> [babel presets:latest] -> .js(es5) -> Run on the fly!

# 1. Create the template
```bash
# Init package json
npm init -y

# Install all babel, ts, webpack & loaders
npm install --save-dev webpack typescript ts-node nodemon @types/debug @types/node @types/express
# ts-loader webpack-dev-server babel-core babel-loader babel-preset-env source-map-loader 

# Install express
npm install --save express

# Create tsconfig.json
node ./node_modules/typescript/lib/tsc --init
```

## Edit tsconfig.json
```javascript
```
