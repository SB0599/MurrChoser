![MurrChoserLogo](https://github.com/Patsch36/MurrChoser/assets/74180467/3a3355f4-7c16-4888-953d-9398e0e6d136)
# MurrChooser

A Tool based based on VueJS and Typescript for checking present trainees at certain team meetings and check choose suitable presenters.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## TODO

- [ ] Advanced Generation Options for mods (Choose between amounts of moderations already)

- [ ] Refactor malchosen computed Property FilerPeople to watch

- [ ] Auswahl ändern

- [ ] Frischlinge bis Januar auslassen

- [ ] MIT Lizenzen in Footer einfügen

- [ ] CSS-Breiten und Höhen mit min-width/height: absoluten wert, width/height: relativen Wert darstellen
