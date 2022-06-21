# .

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

## Tailwind Setup

```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Configure tailwind.config.js file

```sh
module.exports = {
  content: ["./index.html", "./src/**/*.{vue,js,ts,jsx,tsx}"],
  theme: {
    colors: {
      white: "hsl(0, 0%, 100%)",
      Lightgray: "hsl(212, 45%, 89%)",
      Grayishblue: "hsl(220, 15%, 55%)",
      Darkblue: "hsl(218, 44%, 22%)",
    },
  },
  plugins: [],
}
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
