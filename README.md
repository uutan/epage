# MS-Epage

一款基于 schema 的可视化页面配置工具。可基于流行的前端组件库配置表单、页面等。
基于 epage 开发扩展：[http://epage.didichuxing.com](http://epage.didichuxing.com)

```sh
# 全局安装
npm i msepage
```

## 设计器及渲染器示例

```js
import widgets, { Render, Epage } from "msepage";
import "msepage/src/style/main.less";

const el = document.getElementById("root");
new Epage({ el, widgets, Render });
```

## 感谢

Chengzi <ttghost@126.com>

## License

[MIT](http://opensource.org/licenses/MIT)
