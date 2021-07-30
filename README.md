# app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Project Infos

- [Vue Cli](https://cli.vuejs.org/guide/installation.html)
- [NPM Pack](https://www.npmjs.com/)
- [Tailwindcss|Install|Compatibility](https://tailwindcss.com/docs/installation#post-css-7-compatibility-build)

### Plugins installed
```
npm i eslint-import-resolver-webpack eslint-plugin-import node-sass css-loader sass-loader --save-dev
```

### Plugin tailwindcss
```
npm add tailwindcss
```
* Error:
  * Error: PostCSS plugin tailwindcss requires PostCSS 8.
    * ```npm uninstall tailwindcss postcss autoprefixer```
    * ```npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9```
    
### Apply eslint
```
npm run lint --fix  
```

### Add packages default
```
vue add router
```
** Em caso de erro troca o valor do sass-loader conforme abaixo
`"sass-loader": "^10"`

```
vue add vuex
```