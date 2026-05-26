# PressLite

浏览器端智能图片压缩工具。基于 Canvas API + WebP/AVIF 自适应编码，文件不离开设备。

## 功能

- **拖拽上传** — 支持拖拽或点击上传，批量处理
- **质量可调** — 10%-100% 滑块控制压缩强度
- **格式切换** — WebP / JPEG / PNG / AVIF / 自动
- **尺寸限制** — 可按最大宽度等比缩放
- **实时对比** — 原图与压缩图并排预览
- **本地处理** — 所有压缩在浏览器完成，不上传服务器

## 使用

直接浏览器打开 `index.html`，或部署到任意静态服务：

```bash
python -m http.server 8080
# 访问 http://localhost:8080
```

## 技术栈

- 纯 HTML/CSS/JS，零依赖
- Canvas API 图片压缩
- 支持 JPG / PNG / WebP / AVIF / BMP 输入
- WebP 输出兼容所有现代浏览器

## License

MIT
