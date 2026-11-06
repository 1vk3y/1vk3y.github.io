# 素材清单

所有图片请压到 300KB 以内，使用 `loading="lazy"` 懒加载。

## 賨记

- `congji-screenshot-1.jpg` - 小程序截图 1
- `congji-screenshot-2.jpg` - 小程序截图 2
- `congji-screenshot-3.jpg` - 小程序截图 3
- `congji-qr.jpg` - 小程序码

## Chelae

- `chelae-log-1.jpg` - 运行日志截图 1
- `chelae-log-2.jpg` - 运行日志截图 2

## 代码之外

- `music-163.jpg` - 网易云音乐歌手页截图
- `subway-game.jpg` - 微信小游戏截图
- `subway-game-qr.jpg` - 小游戏码（可选）
- `ai-video-cover.jpg` - AI 视频封面图

## 替换占位符

图片准备好后，在 `index.html` 中搜索对应的占位符文本，替换为：

```html
<img src="assets/文件名.jpg" alt="描述" loading="lazy">
```

## 图片压缩建议

- 使用 TinyPNG (https://tinypng.com/) 或 ImageOptim 压缩
- 手机截图建议宽度 800px 左右
- 架构图可以用 SVG 格式（不需要压缩）
