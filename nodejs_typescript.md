```
  npm i -D ts-node nodemon typescript  
```

```
npm i jsonwebtoken cors express
```
  
```
tsc --init   
```
  
in your `tsconfig.json` in `compilerOptions`

```
  "target": "es6",
  "outDir": "./dist",
"rootDir": "./src",
"moduleResolution": "node"
```
  

in your `package.json`

```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node dist/app.js",
    "dev": "nodemon src/app.ts",
    "build": "tsc -p ."
  }
```
  
  
  
  