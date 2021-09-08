# HW2

## 用到的技術

- 使用 Node.js 建立本機伺服器
- Babel : 轉譯 ES6 React -> ES5
- React : 主要前端架構
- Redux : App 內的 state 控制
- styled-components : CSS in JS
- math.js : 解決浮點數計算錯誤

### 建立本機伺服器

1. 初始化專案

   ```(Shell)
       yarn init -y
   ```

2. 建立 [Node.js Web Server](https://github.com/lp250isme/server.js/blob/master/sever.js)

3. 安裝 `babel` (轉譯 Javascript es6 -> es5)

   ```(Shell)
    yarn add @babel/cli @babel/core @babel/preset-env @babel/preset-react
   ```

4. 新增檔案 `.babelrc`

   ```(Json)
    {
      "presets": ["@babel/preset-react"]
    }
   ```

5. index.html 內加上 React, ReactDom , React-Redux, styled-components Script 標籤

   ```()HTML
    <script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js" crossorigin></script>
    <script crossorigin src="https://npmcdn.com/react-redux@7.2.4/dist/react-redux.min.js"></script>
    <script crossorigin src="https://unpkg.com/styled-components/dist/styled-components.min.js"></script>
    <script src="https://unpkg.com/mathjs/lib/browser/math.js"></script>
   ```
