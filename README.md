# 邓凯纳 · 个人主页

以 FDE（Forward Deployed Engineer）为核心定位的中英文个人主页。纯静态 HTML / CSS，无第三方脚本、字体请求或构建依赖。

- 中文版：`index.html`（默认入口）
- 英文版：`en.html`
- 两版顶部均有语言切换链接，内容同步维护，共用 `styles.css`。
- AI 审计项目使用用户提供的 AuditFlow 界面截图（`assets/auditflow-workflow.png`），两版均可点击查看原图。

## 本地预览

直接打开 `index.html`，或在仓库根目录使用已安装的 Python：

```sh
python -m http.server 8000
```

浏览器访问 `http://localhost:8000`。

## 内容依据与维护

- 文案依据用户提供的《邓凯纳 简历v3 - 算法.pdf》与当前项目说明编写；原仓库克隆时为空，没有可沿用的页面设计。
- AI 审计工作流为自行设计开发的智能体桌面应用；酒店私域分销按用户说明列为当前开发项目。没有宣称客户、上线状态或商业成果。
- Anchoring Contextual Knowledge 的投稿状态沿用简历记载；Endpoint-Guided 的 AAAI 在投状态及新增 BCMoE 的 ICASSP 在投状态依据用户后续补充。未将投稿写成录用，未补写 BCMoE 的作者排序或实验成果；后续可按实际进展更新。
- 硕士教育结束时间为预计毕业时间。Toolkit 按用户要求使用具体技术名称，不标注“课程项目”“基础”等字样，也未新增熟练程度或项目成果声明。
- 主页仅公开简历中的联系邮箱，没有复制电话号码、详细住址或完整简历附件。
- 未执行或解析 `AuditWorkflow.lnk`；桌面应用的描述来自简历。

## GitHub Pages 部署（尚未执行）

用户确认内容并明确授权推送后，再提交和推送本地文件到 `main` 分支。

在 GitHub 仓库的 **Settings → Pages → Build and deployment** 中，选择 **Deploy from a branch**，分支选择 **main**，目录选择 **/(root)** 并保存。

当前仓库所属账号为 `Hoilap`，仓库名为 `dengkn.github.io`。它不是与账号同名的 `Hoilap.github.io` 用户站点仓库；按项目站点路径配置时，地址通常为 `https://hoilap.github.io/dengkn.github.io/`。以 Pages 设置中实际显示的地址为准。所有站内资源使用相对路径，支持项目子路径。

如需使用账号根站点地址 `https://hoilap.github.io/`，需要另行确认是否改用 `Hoilap.github.io` 仓库；此处没有重命名仓库或更改远程配置。

官方部署说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
