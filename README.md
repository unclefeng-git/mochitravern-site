# mochitravern-site

摩奇大陆 · 气候长廊 — 虚构世界沉浸式导览静态站（zh-Hans）。

## 内容

单页滚动叙事，背景图随地区切换。气候经线自南向北：

1. **暖潮珊瑚湾** — 热带海岸
2. **红树潮汐湾** — 河口红树林 / 潟湖
3. **啼雨翡翠林** — 热带雨林
4. **金穗风原** — 草原麦田
5. **断云脊脉** — 高山云海
6. **霜晶苔原** — 寒带苔原
7. **永夜冰原** — 极境冰原

已替换原巴黎叙事地图内容。

## 技术

- 纯静态 `index.html`（内联 CSS/JS）
- 图片热链 Unsplash CDN（`images.unsplash.com`），页脚与下文署名
- 可置于任意静态托管 / Cloudflare 反代之前

## 图片署名（Unsplash License）

| 地区 | 照片 | 作者页 |
|------|------|--------|
| 暖潮珊瑚湾 | photo-1507525428034-b723cf961d3e | [Sean Oulashin](https://unsplash.com/photos/1507525428034-b723cf961d3e) |
| 红树潮汐湾 | photo-1518509562904-e7ef99cdcc86 | [Unsplash](https://unsplash.com/photos/1518509562904-e7ef99cdcc86) |
| 啼雨翡翠林 | photo-1448375240586-882707db888b | [Sebastian Unrau](https://unsplash.com/photos/1448375240586-882707db888b) |
| 金穗风原 | photo-1500382017468-9049fed747ef | [Henrique Felix](https://unsplash.com/photos/1500382017468-9049fed747ef) |
| 断云脊脉 | photo-1464822759023-fed622ff2c3b | [Kalen Emsley](https://unsplash.com/photos/1464822759023-fed622ff2c3b) |
| 霜晶苔原 | photo-1565073182887-6bcefbe225b1 | [Hans-Jurgen Mager](https://unsplash.com/photos/1565073182887-6bcefbe225b1) |
| 永夜冰原 | photo-1491002052546-bf38f186af56 | [Adam Chang](https://unsplash.com/photos/1491002052546-bf38f186af56) |

许可：https://unsplash.com/license

## 本地预览

```bash
python3 -m http.server 8080 --directory .
# 打开 http://localhost:8080
```
