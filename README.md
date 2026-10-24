# rain-rgb.github.io

个人主页：<https://rain-rgb.github.io/>

单文件静态页面，无第三方依赖、无外部字体、无统计脚本。内容以工作与项目为主，不包含证件、联系方式以外的个人信息。

## 本地预览

直接用浏览器打开 `index.html`，或：

```bash
python -m http.server 8000
```

## 结构

```text
index.html    # 全部内容与样式、脚本，单文件
.nojekyll     # 关闭 GitHub Pages 的 Jekyll 处理
```

## 修改

文案与项目条目都在 `index.html` 中，按 `<!-- -->` 分节；主题色在 `:root` 的 CSS 变量里。

页面支持深色 / 浅色切换（记忆在 localStorage），并带打印样式，可直接「打印 → 存为 PDF」作为简历附件。
