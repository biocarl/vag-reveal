# VAG: Plugin für Reveal.js

## Installation
```bash
npm install reveal-md -g
```

## How to run locally
```bash
reveal-md slides.md -w --template reveal-template.html
```


## Before handing out 

`reveal-md.json`
- injectConfig should be living in main.js
- dependencies also (import with node modules)

- Do defer not with template but with onLoad event or so


## Todos
- Create a pipeline for publishing this as a npm package