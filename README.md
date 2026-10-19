# Jade Cards Lab / 玉石卡牌实验室 · 金箔典藏

中文：玉石浮雕卡牌馆金箔典藏版：收录四大主题 108 张精雕玉石扑克牌，Neo Kinpaku 黑漆金箔风格艺术展陈，支持 3D 翻转、沉浸大图品鉴、分类花色检索与今日灵感抽牌。

English: Kinpaku Art Edition of the Jade Relief Playing Card Gallery: featuring 108 cards across four themes with Neo Kinpaku black lacquer and gold foil aesthetics, 3D card flipping, full-screen inspection, and celestial oracle draw.

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

源码与部署配置使用同一个主分支；在本地手动发布，不创建 Cloudflare 专用分支或 GitHub Action。
