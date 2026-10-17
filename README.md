# Jade Cards Lab / 玉石卡牌实验室

中文：玉石浮雕卡牌馆的实验室重做版本：收录四大主题 108 张精选卡片，Neo Kinpaku 黑漆金箔风格排版、侧边竖排导航、分类横滑与点击翻面互动。

English: Laboratory edition of the Jade Relief Card Gallery featuring 108 cards across four themes with Neo Kinpaku black lacquer and gold foil styling, vertical navigation, and 3D card flip interactions.

![Project screenshot](./assets/screenshot.png)

## 在线体验 / Live Demo

- [Cloudflare Demo](https://xiaosang.cc/jade-cards-lab/)
- [GitHub Repo](https://github.com/holynova/jade-cards-lab)

<img src="./assets/qr.png" width="180" alt="扫码访问 Cloudflare 在线体验">

## 本地运行 / Run locally

```bash
python3 -m http.server 8000
```

## 发布 / Deploy

```bash
npx wrangler deploy --config wrangler.jsonc
```

Cloudflare Workers · Domain: `xiaosang.cc` · Route: `/jade-cards-lab/`

源码与部署配置使用同一个主分支（main）；在本地手动发布，不创建 Cloudflare 专用分支或 GitHub Action。
