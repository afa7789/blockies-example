# test

This template should help get you started developing with Vue 3 in Vite.


## USED in my website.

I build this as production with `yarn build` and copied the built js and css , renamed them and am serving on my website.
Check it up here:

https://github.com/afa7789/gofiber-website/blob/master/web/static/css/vue.css

https://github.com/afa7789/gofiber-website/blob/master/web/static/js/vue.js

and added to the html with:
```
    <div id="app"></div>
    <noscript>
        <p class="text-center text-red-600">
            Please enable JavaScript to see the demo.
        </p>
    </noscript>
    <script src="/public/js/vue.js"></script>
    <link rel="stylesheet" href="/public/css/vue.css">
```


## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

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

### Compile and Minify for Production

```sh
npm run build
```
