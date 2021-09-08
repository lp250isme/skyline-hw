# 遇到的問題以及使用到的技術

## 遇到的問題

1. 一開始遇到 react 無法 import or export  
   解決方法：`<script>` 標籤中增加 `type="module"` -> `<script type="module" src="./lib/script.js"></script>`

## 用到的技術

1. `Babel` 轉譯 `ES6` 及 `React` 語法 -> `ES5`
2. `node js`  原生 `http` 及 `fs` 語法
3. `yarn` and `npm`
4. `styled-components`  
   CDN Link :  
   `<script crossorigin src="https://unpkg.com/react-is@17.0.2/umd/react-is.production.min.js"></script>`
   `<script crossorigin src="https://unpkg.com/styled-components/dist/styled-components.min.js"></script>`
