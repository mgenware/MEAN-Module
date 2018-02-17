# MEAN Node.js Modules
MEAN Modules are Node.js modules with the following characteristics: 

* **Only necessary code files are uploaded to npm registry (with 2 exceptions: `package.json` and `README.md`)**.
* **All uploaded JavaScript files are minified**.
* **Must come with type definitions. (currently either TypeScript or FlowTyped)**.
* Some commonly used files are allowed, for example: `.gitignore`, `.npmignore`.
* Source map files are allowed but not required.

A typical MEAN module downloaded from npm registry is like:
```
node_modules/fx58-node
├── .gitignore              [commonly used file]
├── README.md               [README is required]
├── dist
│   └── lib
│       ├── main.d.ts       [type definition files are required]
│       ├── main.js         [minified code files]
│       └── main.js.map     [source map files](optional)
└── package.json            [package.json is required]
```

## Badges
You can add these badges to your `README.md` to indicate it's a MEAN Module.

MEAN Module (TypeScript):

[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-TypeScript-blue.svg)](https://github.com/mgenware/MEAN-Module)

```markdown
[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-TypeScript-blue.svg)](https://github.com/mgenware/MEAN-Module)
```

MEAN Module (FlowTyped):

[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-Flow-orange.svg)](https://github.com/mgenware/MEAN-Module)

```markdown
[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-Flow-orange.svg)](https://github.com/mgenware/MEAN-Module)
```

MEAN Module (TypeScript) (Flat style):

[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-TypeScript-blue.svg?style=flat-square)](https://github.com/mgenware/MEAN-Module)

```markdown
[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-TypeScript-blue.svg?style=flat-square)](https://github.com/mgenware/MEAN-Module)
```

MEAN Module (FlowTyped) (Flat style):

[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-Flow-orange.svg?style=flat-square)](https://github.com/mgenware/MEAN-Module)

```markdown
[![MEAN Module](https://img.shields.io/badge/MEAN%20Module-Flow-orange.svg?style=flat-square)](https://github.com/mgenware/MEAN-Module)
```
