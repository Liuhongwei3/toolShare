## 在线工具

- `MDN` 在线编辑、运行、演示代码：[MDN - PLAY](https://developer.mozilla.org/zh-CN/play)，支持 HTML/CSS/JS
- `vscode 在线版`查看 github 仓库源码：[vscode.dev](https://vscode.dev/github/facebook/react)，可登录账号同步相关插件

## 三方库

### json diff

#### 基础库

- `jsdiff`: 字符串级别的 diff，返回结果较为基础，下面的组件库大多数会在该包的基础上进行封装，链接：[https://www.npmjs.com/package/diff](https://www.npmjs.com/package/diff)
- `json-diff`: 一个命令行的 diff，如果需要在本地使用命令 diff，可使用，[https://www.npmjs.com/package/json-diff](https://www.npmjs.com/package/json-diff)

#### 组件库

- `react-diff-viewer`: 体积大小尚可且与 vscode diff 效果相似，适合需要将 diff 在 react 页面中展示，链接：[https://www.npmjs.com/package/react-diff-viewer](https://www.npmjs.com/package/react-diff-viewer)
  - 大小、样式、使用等方面均不错，如若只需要快速上手并应用推荐使用
  - 默认是传入字符串进行比对，不过可以根据该 [issues](https://github.com/praneshr/react-diff-viewer/issues/102) 的提示通过 `JSON.stringfy(obj, undefined, 2)` 来使用
  - 不过最新版也是在三年前的发布，若需要最新也可使用他的改版包：[react-diff-viewer-continued](https://www.npmjs.com/package/react-diff-viewer-continued)
- `jsondiffpatch`: 在线 demo 看上去还不错，不过只是单列展示 diff，链接：[https://www.npmjs.com/package/jsondiffpatch](https://www.npmjs.com/package/jsondiffpatch)
  - 体积较大，有 3.x M
- `json-diff-kit`: 各方面来说也还行，配置也比较丰富，demo 的样式较为普通，不过可以自行配置，链接：[json-diff-kit](https://www.npmjs.com/package/json-diff-kit)

### json preview

- `react-json-pretty`，体积较小，内置了一些样式，也可以自定义样式，这个比较方便，但上一次发布已是好几年前了，[link](https://www.npmjs.com/package/react-json-pretty)
- `react-json-view-lite`，体积也只有几十kb，内置样式，不过不太好看，也能自定义样式，不过只支持设置类名来自定义样式，可以尝试一下，[link](https://www.npmjs.com/package/react-json-view-lite)
- `jsoneditor`，样式最符合日常习惯，功能也比较丰富且支持编辑，唯一的缺点就是体积太大，如果不需要担心大小可以使用，[link](https://www.npmjs.com/package/jsoneditor)

