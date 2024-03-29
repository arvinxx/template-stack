# 空谷的技术栈与脚手架模板

我所掌握的技术栈和自用脚手架模板。

相关知识库 ➡️ [空谷的大前端](https://www.yuque.com/arvinxx-fe)

**TOC**

- [前端](https://github.com/arvinxx/template-stack#前端)
- [后端](https://github.com/arvinxx/template-stack#后端)
- [模块开发](https://github.com/arvinxx/template-stack#模块开发)
- [其他](https://github.com/arvinxx/template-stack#其他)

## 前端

| 端技术       | 技术栈                                                                           | 脚手架地址                                                                                           |
| ------------ |-------------------------------------------------------------------------------| ---------------------------------------------------------------------------------------------------- |
| Web App      | React + Umi + antd + antd-style + zustand                                     | ➡️ [传送门](https://github.com/arvinxx/template-stack#web-app)                                       |
| 浏览器插件   | [umi-plugin-extensions][umi-plugin-extensions] + WebApp                       | ➡️ [传送门](https://github.com/arvinxx/template-stack#%E6%B5%8F%E8%A7%88%E5%99%A8%E6%8F%92%E4%BB%B6) |
| 桌面端       | Electron + Web App                                                            | ➡️ [传送门](https://github.com/arvinxx/template-stack#%E6%A1%8C%E9%9D%A2%E7%AB%AF)                   |
| 小程序       | React + Taro + zustand                                                        | ➡️ [传送门](https://github.com/arvinxx/template-stack#%E5%B0%8F%E7%A8%8B%E5%BA%8F)                   |
| 移动端       | TODO                                                                          | TODO                                                                                                 |
| Sketch 插件  | skpm + WebApp                                                                 | ➡️ [传送门](https://github.com/arvinxx/template-stack#sketch-%E6%8F%92%E4%BB%B6)                     |
| Figma 插件   | [umi-plugin-figma](https://github.com/arvinxx/umi-plugin-figma) + WebApp      | TODO                                                                                                 |
| AirTable App | [block-sdk](https://github.com/Airtable/blocks)（AirTable 出品） + antd + zustand | ➡️ [传送门](https://github.com/arvinxx/template-stack#airtable-app)                                  |

### Web App

使用 Ant Design Pro 的脚手架, 可以使用 `create-umi` 直接创建

```shell
$ yarn create umi

? Select the boilerplate type (Use arrow keys)
❯ ant-design-pro  - Create project with a layout-only ant-design-pro boilerplate, use together with umi block.
  app             - Create project with a simple boilerplate, support typescript.
  plugin          - Create a umi plugin.

? Do you want to use typescript? (y/N) y

? What functionality do you want to enable? (Press <space> to select, <a> to toggle all, <i> to invert selection)
 ● antd
 ◯ dva
 ● code splitting
 ● dll

create abc/package.json
create abc/.gitignore
create abc/.editorconfig
...
...

📋  Copied to clipboard, just use Ctrl+V
✨  File Generate Done
```

相关链接:

- [Create Umi](https://github.com/umijs/create-umi)
- [Ant Design Pro](https://github.com/ant-design/ant-design-pro)

➡️ 传送门: [Umi Web Template](https://github.com/arvinxx/umi-web-template)

使用案例：[My RChain Wallet](https://github.com/arvinxx/my-rchain-wallet)、[多译](https://duoyiapp.com/)

### 小程序

#### Taro

➡️ 传送门: [基于 Taro 的小程序模板](https://github.com/arvinxx/miniapp-taro-template)

使用案例：课否

### 桌面端

桌面端开发主要使用 [Electron](https://www.electronjs.org/) ，一个稳定安全的航天级 GUI 基础框架。

[个人笔记: Electron](https://www.yuque.com/arvinxx-fe/electron)

➡️ 传送门: [基于 Umi 的 Electron 开发模板](https://github.com/arvinxx/electron-umi-template)

使用案例：[多译][duoyi]

### 浏览器插件

[Chrome 插件开发基础教程](https://arvinxx.github.io/umi-plugin-extensions/#/tutorial) | [个人笔记: Extensions 浏览器插件](https://www.yuque.com/arvinxx-fe/extensions)

➡️ 传送门: [基于 Umi 的 Chrome 插件开发模板](https://github.com/arvinxx/umi-chrome-extension-template)

使用案例：[Power Yuque][power-yuque]

### Sketch 插件

➡️ 传送门: [Sketch Plugin Template](https://github.com/arvinxx/sketch-plugin-template)

使用案例：[Pan](https://github.com/arvinxx/pan)、[Microwave](https://www.yuque.com/design-engineering/microwave)、[Sketch JSON](https://github.com/arvinxx/sketch-json)

### Figma 插件

TODO

### Airtable App

➡️ 传送门: [AirTable App Template](https://github.com/arvinxx/airtable-app-template)

使用案例：[airtable-app-mind-flow](https://github.com/arvinxx/airtable-app-mind-flow)、[airtable-app-user-journal-map](https://github.com/arvinxx/airtable-app-user-journal-map)

## 后端

| 端技术     | 技术栈              | 脚手架地址                                                   |
| ---------- | ------------------- | ------------------------------------------------------------ |
| Serverless | Vercel + Typescript | ➡️ [传送门](https://github.com/arvinxx/template-stack#serverless) |
| NodeJS     | EggJS + Typescript  | ➡️ [传送门](https://github.com/arvinxx/template-stack#eggjs) |
| Python     | Flask               | ➡️ [传送门](https://github.com/arvinxx/template-stack#flask) |

### Serverless

➡️ 传送门: [Vercel Serverless Api Template](https://github.com/arvinxx/vercel-serverless-api-template)

使用案例：[空谷的 api](https://github.com/arvinxx/api)

### EggJS

TODO

### Flask

TODO

## 模块开发

|                              | 技术栈                                                             | 脚手架地址                                                                                             |
| ---------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------ |
| 单模块模板                   | Typescript + Dumi + Father + Jest + Typedoc                        | ➡️ [传送门](https://github.com/arvinxx/template-stack#单模块开发)                                      |
| 多模块模板                   | 单模块 + lerna                                                     | ➡️ [传送门](https://github.com/arvinxx/template-stack#多模块模板)                                      |
| Umi Plugin 开发模板          | 单模块                                                             | ➡️ [传送门](https://github.com/arvinxx/template-stack#umi-plugin-%E5%BC%80%E5%8F%91%E6%A8%A1%E6%9D%BF) |
| Gitmoji Commit Workflow 模板 | commitlint + contenonal-changelog + semantic-release + GCW-Presets | ➡️ [传送门](https://github.com/arvinxx/template-stack#Gitmoji-Commit-Workflow-模板)                    |

### 单模块开发

➡️ 传送门: [模块开发模板](https://github.com/arvinxx/module-develop-template)

使用案例：[html2sketch](https://github.com/ant-design/html2sketch)

### 多模块模板

➡️ 传送门: [Monorepo 开发模板](https://github.com/arvinxx/monorepo-template)

使用案例：[uxdm](https://github.com/uxdm/uxdm)、[gitmoji-commit-workflow][gitmoji-commit-workflow]

### Umi Plugin 开发模板

➡️ 传送门: [Umi Plugin Develop Template](https://github.com/arvinxx/umi-plugin-develop-template)

使用案例：[umi-plugin-extensions][umi-plugin-extensions]、[umi-plugin-figma](https://github.com/arvinxx/umi-plugin-figma)

### Gitmoji Commit Workflow 模板

符合 [Gitmoji Commit Workflow](https://www.yuque.com/arvinxx-fe/workflow/gitmoji-commit-workflow) 规范的开发模板

➡️ 传送门: [Gitmoji Commit Workflow Template](https://github.com/arvinxx/gitmoji-commit-workflow-template/)

使用案例： 本人的大部分模板均已经集成了 Gitmoji Commit Workflow 例如: [gitmoji-commit-workflow][gitmoji-commit-workflow]、[power-yuque][power-yuque]、[umi-plugin-extensions][umi-plugin-extensions] 等

## 其他

### puppeteer 自动化脚本

➡️ 传送门: [Puppeteer Typescript Template](https://github.com/arvinxx/puppeteer-typescript-template)

### processing/P5.js

➡️ 传送门: [processing/P5.js Typescript Template](https://github.com/arvinxx/p5-typescript-template)

## License

[MIT](./LICENSE) ® Arvin Xu

[duoyi]: https://duoyiapp.com/
[power-yuque]: https://github.com/arvinxx/power-yuque
[gitmoji-commit-workflow]: https://github.com/arvinxx/gitmoji-commit-workflow
[umi-plugin-extensions]: https://github.com/arvinxx/umi-plugin-extensions
