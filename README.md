# htmlbox

基于 iframe 沙盒实现的 HTML 预览方案。

💡 灵感来源于 poe.com 的画布功能和 chatgpt.com 的预览功能。

用于将 LLM 生成的 html 代码在主应用预览，并做安全处理如下：

- CSP 内容安全策略处理
- console 拦截
- 新开标签页行为上报

使用时将此项目部署到主应用同源 CDN 上，并使用 postMessage 传输数据。
