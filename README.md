# 微信公众号富文本复制工具

一个简单的网页工具，将HTML代码复制为富文本格式，可直接粘贴到微信公众号后台。

## 在线使用

**https://mingweichen.github.io/wechat-html-copier/**

## 功能

- 📋 将HTML代码复制为富文本（保留样式）
- 👁️ 实时预览效果
- 🎨 简洁美观的界面
- 📱 支持移动端

## 使用方法

1. 将生成的微信公众号HTML代码粘贴到文本框
2. 点击「复制富文本」按钮
3. 前往微信公众号后台编辑器
4. 直接 Ctrl+V / Cmd+V 粘贴
5. 富文本格式自动保留

## 技术原理

使用 `navigator.clipboard.write()` API 将HTML内容以 `text/html` MIME类型写入剪贴板，实现富文本复制。

## License

MIT
