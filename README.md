<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-7-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

VS Code API 是一系列你可以在 Visual Studio Code 扩展中调用的 JavaScript API。这个站点列出了扩展开发者可以使用的所有 VS Code API。原网站没有中文翻译且不方便阅读，所以有了该网站。

API 列表使用 Typedoc 从 [vscode.d.ts](https://github.com/youngjuning/vscode-api/blob/main/vscode.d.ts) 文件编译而来，如果 [vscode.d.ts 源文件](https://github.com/microsoft/vscode/blob/main/src/vs/vscode.d.ts) 有更新，我们会及时同步，当前对应 commit 为 [2974a01](https://github.com/microsoft/vscode/commit/2974a014fd33f4a109aad6ed0f3e46fe93bfc794#diff-f127724f8c5dbf0c8371ad0a100f8a9bc0a398b6b8ec29aa6cd7f265bd01a096)。

## 贡献指南

### 成为译者

- **外部译者**：对 *vscode.d.ts* 文件的注释进行翻译，然后提交 PR 即可。
- **内部译者**：需要负责某一具体模块，如果感兴趣可以添加管理员微信（`yang_jun_ning`）申请。

### 本地预览

1. **安装依赖**：`yarn install`
2. **开启调试**：`yarn dev`
3. **开启服务**：`yarn start`

## 专业术语

- extension：扩展
- namespace：命名空间
- active editor：活动编辑器
- active terminal：活动命令行

## 负责人

翻译负责人是按照 vscode api 的命名空间认领的，如果有兴趣认领请添加管理员微信（`yang_jun_ning`）申请成为内部译者。

- [ ] authentication
- [x] commands          @Imchenlong
- [x] comments          @youngjuning
- [ ] debug
- [x] evn               @Saber2pr
- [x] extensions        @pan463859
- [x] languages         @Tecvan-fe
- [x] notebooks         @sherry-zxy
- [x] scm               @sherry-zxy
- [ ] tasks
- [x] tests             @pan463859
- [x] window            @youngjuning
- [x] workspace         @gepingli

## 贡献者 ✨

感谢这些优秀的人 ([emoji key](https://allcontributors.org/docs/en/emoji-key))：

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/youngjuning"><img src="https://avatars.githubusercontent.com/u/13204332?v=4?s=100" width="100px;" alt=""/><br /><sub><b>youngjuning</b></sub></a><br /><a href="https://github.com/youngjuning/vscode-api-cn/commits?author=youngjuning" title="Code">💻</a> <a href="#maintenance-youngjuning" title="Maintenance">🚧</a> <a href="#translation-youngjuning" title="Translation">🌍</a> <a href="https://github.com/youngjuning/vscode-api-cn/commits?author=youngjuning" title="Documentation">📖</a> <a href="#ideas-youngjuning" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/gepingli"><img src="https://avatars.githubusercontent.com/u/29964332?v=4?s=100" width="100px;" alt=""/><br /><sub><b>gepingli</b></sub></a><br /><a href="#translation-gepingli" title="Translation">🌍</a> <a href="#ideas-gepingli" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://saber2pr.top"><img src="https://avatars.githubusercontent.com/u/40260564?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Konpaku Youmu</b></sub></a><br /><a href="#translation-Saber2pr" title="Translation">🌍</a> <a href="#ideas-Saber2pr" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-Saber2pr" title="Maintenance">🚧</a> <a href="https://github.com/youngjuning/vscode-api-cn/commits?author=Saber2pr" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Imchenlong"><img src="https://avatars.githubusercontent.com/u/13520451?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Lance Chen</b></sub></a><br /><a href="#translation-Imchenlong" title="Translation">🌍</a> <a href="#maintenance-Imchenlong" title="Maintenance">🚧</a> <a href="https://github.com/youngjuning/vscode-api-cn/commits?author=Imchenlong" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/pan463859"><img src="https://avatars.githubusercontent.com/u/32640880?v=4?s=100" width="100px;" alt=""/><br /><sub><b>潘小安</b></sub></a><br /><a href="#translation-pan463859" title="Translation">🌍</a> <a href="#maintenance-pan463859" title="Maintenance">🚧</a> <a href="#ideas-pan463859" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/youngjuning/vscode-api-cn/commits?author=pan463859" title="Code">💻</a></td>
    <td align="center"><a href="https://www.zhihu.com/people/tec-van"><img src="https://avatars.githubusercontent.com/u/84165678?v=4?s=100" width="100px;" alt=""/><br /><sub><b>tecvan</b></sub></a><br /><a href="#translation-Tecvan-fe" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/sherry-zxy"><img src="https://avatars.githubusercontent.com/u/36014195?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Xiyuan Zheng</b></sub></a><br /><a href="#translation-sherry-zxy" title="Translation">🌍</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

本项目遵循 [all-contributors](https://github.com/all-contributors/all-contributors) 规范。欢迎任何形式的贡献!
