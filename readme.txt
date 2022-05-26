
- npm init
- npm install --save-dev lite-server
- tsc --init

-
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start": "lite-server"
    },

- index.html
    <script src="app.js" defer></script>

- app.ts

- ts.config
      "exclude": [
        "node_modules"
      ]
      -----
      "target": "ES6",
      - For debugging .ts files in the browser
        "sourceMap": true,
      - For setting input/output directory
        "outDir": "./dist",
        "rootDir": "./src",
      "removeComments": true,
      "noEmitOnError": true,


- For the entire project compilation and tsconfg.json file:
    tsc --init
        - will generate a "tsconfig.json" file.
    tsc -w  (or tsc -- watch)

    For single file: tsc app.ts or app.ts -w


- tsc -w
- npm start

-------------------------------------------------------------------------------------

Debugging:
    - Choose Run | Edit Configurations from the main menu,
    - click the Add button on the toolbar
    - select JavaScript Debug from the list.
    - in ts.config
         "sourceMap": true,


--------------------------------------------------------------------------------------

new branch 444
