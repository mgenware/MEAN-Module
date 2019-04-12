# MEAN Node.js Modules
MEAN Modules are Node.js modules with the following characteristics (see [node-mean-template](https://github.com/mgenware/node-mean-template) for a boilerplate project): 

|                             |                                                         |
|-----------------------------|---------------------------------------------------------|
| JavaScript files            | ✅ Required<br/>🚙 Should be minified                          |
| TypeScript definition files | ✅ Required                                              |
| Source map files            | 🚙 Should be included                                    |
| Common files                | 😀 OK, e.g. `package.json`, `README.md`, `.gitignore`... |
| Test files                  | ❌ Should not be included                                |
| Other files                 | ❌ Should not be included unless necessary               |

A typical MEAN module downloaded from npm registry is like:
```
node_modules/fx58-node
├── .gitignore              [Common files]
├── README.md               [Common files]
├── dist
│   ├── main.d.ts           [Type definition files]
│   ├── main.js             [Minified code files]
│   └── main.js.map         [Source map files]
└── package.json            [Common files]
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
