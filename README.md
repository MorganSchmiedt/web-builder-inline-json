## Web Builder Module - Inline JSON files

This module allows the [@deskeen/web-builder](https://github.com/deskeen/web-builder) engine to inline JSON files.

## Install

```
npm install @deskeen/web-builder
npm install @deskeen/web-builder-inline-json
```


### Usage

Add the module to the list of modules: 

```javascript
const builder = require('@deskeen/web-builder')
const builder.build([
  source: [
    // List of files or directories that include inlineSVG tags
    // {{inlineJSON:file.json}}
  ],
  modules: [
    [
      '@deskeen/web-builder-inline-json',
      {
        assets: [
          // List of directories that include the files
        ],
        minify: true, // Optional
      }
    ]
  ]
])
```


## Contact

You can reach me at {my_firstname}@{my_name}.fr


## Licence

MIT Licence - Copyright (c) Morgan Schmiedt