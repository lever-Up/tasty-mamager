# 小鲜味管理后台

一套优秀的中后台前端解决方案

[![antd](https://img.shields.io/badge/antd-^3.10.0-blue.svg?style=flat-square)](https://github.com/ant-design/ant-design)
[![umi](https://img.shields.io/badge/umi-^2.2.1-orange.svg?style=flat-square)](https://github.com/umijs/umi)
[![GitHub issues](https://img.shields.io/github/issues/zuiidea/antd-admin.svg?style=flat-square)](https://github.com/zuiidea/antd-admin/issues)
[![MIT](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](http://opensource.org/licenses/MIT)
![Travis (.org)](https://img.shields.io/travis/zuiidea/antd-admin.svg)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/zuiidea/antd-admin/pulls)
[![Gitter](https://img.shields.io/gitter/room/antd-admin/antd-admin.svg)](https://gitter.im/antd-admin/antd-admin)

- 使用文档 - [https://doc.antd-admin.zuiidea.com/#/zh-cn/](https://doc.antd-admin.zuiidea.com/#/zh-cn/)
- 常见问题 - [https://doc.antd-admin.zuiidea.com/#/zh-cn/faq](https://doc.antd-admin.zuiidea.com/#/zh-cn/faq)
- 更新日志 - [https://doc.antd-admin.zuiidea.com/#/zh-cn/change-log](https://doc.antd-admin.zuiidea.com/#/zh-cn/change-log)

## 目录结构

````

├── dist/               # 默认build输出目录
├── mock/               # Mock文件目录
├── public/             # 静态资源文件目录
├── src/                # 源码目录
│ ├── components/       # 组件目录
│ ├── e2e/              # e2e目录
│ ├── layouts/          # 布局目录
│ ├── locales/          # 国际化文件目录
│ ├── models/           # 数据模型目录
│ ├── pages/            # 页面组件目录
│ ├── services/         # 数据接口目录
│ │ ├── api.js          # 接口配置
│ │ └── index.js        # 接口输出
│ ├── themes/           # 项目样式目录
│ │ ├── default.less    # 样式变量
│ │ ├── index.less      # 全局样式
│ │ ├── mixin.less      # 样式函数
│ │ └── vars.less       # 样式变量及函数
│ ├── utils/            # 工具函数目录
│ │ ├── config.js       # 项目配置
│ │ ├── constant.js     # 静态常量
│ │ ├── index.js        # 工具函数
│ │ ├── request.js      # 异步请求函数(axios)
│ │ └── theme.js        # 项目需要在js中使用到样式变量
├── .editorconfig       # 编辑器配置
├── .env                # 环境变量
├── .eslintrc           # ESlint配置
├── .gitignore          # Git忽略文件配置
├── .prettierignore     # Prettier忽略文件配置
├── .prettierrc         # Prettier配置
├── .stylelintrc.json   # Stylelint配置
├── .travis.yml         # Travis配置
└── .umirc.js           # Umi配置
└──  package.json       # 项目信息

````

## 特性

- 国际化，源码中抽离翻译字段，按需加载语言包
- 动态权限，不同权限对应不同菜单
- 优雅美观，Ant Design 设计体系
- Mock 数据，本地数据调试


## 使用

```bash
yarn install

yarn start
```

4. 启动完成后打开浏览器访问 [http://localhost:7000](http://localhost:7000)，如果需要更改启动端口，可在 `.env` 文件中配置。


> 更多信息请参考 [使用文档](https://doc.antd-admin.zuiidea.com/#/zh-cn/)。


## 支持环境

现代浏览器。

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --------- | --------- | --------- | --------- | --------- | 
|IE11, Edge| last 2 versions| last 2 versions| last 2 versions| last 2 versions
