# mochitravern-site

摩奇大陆 · 气候长廊 — 虚构世界沉浸式导览静态站（zh-Hans）。

## 内容

单页滚动叙事，背景图随地区切换。气候经线自南向北，兼收奇境：

1. **暖潮珊瑚湾** — 热带海岸
2. **星环环礁** — 珊瑚环礁 / 潟湖
3. **红树潮汐湾** — 河口红树林
4. **荧潮夜岸** — 生物荧光海岸
5. **啼雨翡翠林** — 热带雨林
6. **雾吞裂谷** — 迷雾峡谷
7. **金穗风原** — 草原麦田
8. **镜盐白泽** — 盐湖镜面
9. **黑曜熔漠** — 火山玻璃荒漠
10. **断云脊脉** — 高山云海
11. **浮梦群屿** — 浮空群岛
12. **晶泪洞府** — 水晶洞窟
13. **极光冻原** — 苔原 · 极光
14. **永夜冰原** — 极境冰原

已替换原巴黎叙事地图内容；由七境扩充为十四境。

## 技术

- 纯静态 `index.html`（内联 CSS/JS）
- 图片热链 Unsplash CDN（`images.unsplash.com`），页脚与下文署名
- 右侧导航点随滚动高亮；顶栏进度条；卡片入场动画
- 可置于任意静态托管 / Cloudflare 反代之前

## 图片署名（Unsplash License）

| 地区 | 照片 | 作者页 |
|------|------|--------|
| 暖潮珊瑚湾 | photo-1507525428034-b723cf961d3e | [Sean Oulashin](https://unsplash.com/photos/1507525428034-b723cf961d3e) |
| 星环环礁 | photo-1559827260-dc66d52bef19 | [Unsplash](https://unsplash.com/photos/1559827260-dc66d52bef19) |
| 红树潮汐湾 | photo-1518509562904-e7ef99cdcc86 | [Unsplash](https://unsplash.com/photos/1518509562904-e7ef99cdcc86) |
| 荧潮夜岸 | photo-1505118380757-91f5f5632de0 | [Silas Baisch](https://unsplash.com/photos/1505118380757-91f5f5632de0) |
| 啼雨翡翠林 | photo-1448375240586-882707db888b | [Sebastian Unrau](https://unsplash.com/photos/1448375240586-882707db888b) |
| 雾吞裂谷 | photo-1470071459604-3b5ec3a7fe05 | [Unsplash](https://unsplash.com/photos/1470071459604-3b5ec3a7fe05) |
| 金穗风原 | photo-1500382017468-9049fed747ef | [Henrique Felix](https://unsplash.com/photos/1500382017468-9049fed747ef) |
| 镜盐白泽 | photo-1605649487212-47bdab064df7 | [Unsplash](https://unsplash.com/photos/1605649487212-47bdab064df7) |
| 黑曜熔漠 | photo-1611273426858-450d8e3c9fce | [Unsplash](https://unsplash.com/photos/1611273426858-450d8e3c9fce) |
| 断云脊脉 | photo-1464822759023-fed622ff2c3b | [Kalen Emsley](https://unsplash.com/photos/1464822759023-fed622ff2c3b) |
| 浮梦群屿 | photo-1506905925346-21bda4d32df4 | [Samuel Ferrara](https://unsplash.com/photos/1506905925346-21bda4d32df4) |
| 晶泪洞府 | photo-1547036967-23d11aacaee0 | [Unsplash](https://unsplash.com/photos/1547036967-23d11aacaee0) |
| 极光冻原 | photo-1531366936337-7c912a4589a7 | [Jonatan Pie](https://unsplash.com/photos/1531366936337-7c912a4589a7) |
| 永夜冰原 | photo-1491002052546-bf38f186af56 | [Adam Chang](https://unsplash.com/photos/1491002052546-bf38f186af56) |

许可：https://unsplash.com/license

## 本地预览

```bash
python3 -m http.server 8080 --directory .
# 打开 http://localhost:8080
```
