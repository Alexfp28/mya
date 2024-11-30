# mya

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration
### Acuerdate
Siempre que quieras hacer una nueva página, acuerdate de poner esto en tu ```vite.config.ts```

```
base: '/mya/',
  build: {
    outDir: 'dist',
  },
```

En el atributo base poner el nombre que tendrá esta página dentro de [https://alexfp28.github.io/](https://alexfp28.github.io/)