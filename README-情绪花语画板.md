本地预览说明

文件: 情绪花语画板 —— p5.js 屏幕端交互视觉系统index.html

快速预览（推荐）:
1. 在项目文件夹打开终端。
2. 使用 Python 简易静态服务器（推荐，可避免部分浏览器本地文件限制）：

```powershell
# 在 Windows PowerShell 或 cmd 中运行
python -m http.server 8000
```
3. 打开浏览器访问 `http://localhost:8000/`，然后点击或导航到 `情绪花语画板 —— p5.js 屏幕端交互视觉系统index.html`。

直接打开（大多数功能可用）:
- 你也可以直接在文件管理器中双击 `index.html` 用浏览器打开（file://），页面依赖 CDN 加载 p5.js，若浏览器阻止文件访问某些 API，请使用上面的本地服务器。

功能说明:
- 选择情绪按钮会实时生成对应的数字花朵与粒子效果。
- 右侧“心情日记”支持保存到浏览器 `localStorage`、删除、按情绪筛选、按文本搜索、按时间排序（最新/最旧）、导出为 JSON、导入 JSON。

导入 JSON 注意:
- 导入的 JSON 应为数组，每个元素形如 { id, mood, moodName, text, ts }。
- 若导入对象缺少 `id` 字段，系统会为其分配临时 id。

如需我将此页面部署到 GitHub Pages 或打包为简单 Electron 应用，我可以继续帮你。