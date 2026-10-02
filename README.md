# mochitravern-site

摩奇大陆 · 气候长廊 — 虚构世界沉浸式导览静态站（zh-Hans）。

## 内容

单页滚动叙事。背景为 **13 段固定长镜头短片**（约 15s H.264，muted 缓慢循环，`playbackRate ≈ 0.8`），随地区切换；环境音按场景合成并 loudnorm 至约 −16 LUFS，可开关。

| # | 地区 | 源片关键词 | 环境音 |
|---|------|-----------|--------|
| 00 | 巴陶暖岸 | seaside_batrau | seaside_dusk |
| 01 | 彼岸棕影 | sea_other_side | ocean/waves/palms dusk |
| 02 | 风车汀泽 | riverside | wind_farm + water |
| 03 | 古木密林 | arbre | forest_dawn |
| 04 | 金穗废墟 | champ | wheat_dusk |
| 05 | 拱脊暗山 | montain | mountain_stream |
| 06 | 卧佛森域 | buddha | temple_night |
| 07 | 残响圣堂 | cathédrale | temple_garden |
| 08 | 极光听台 | rada | snow/wind/cosmos |
| 09 | 沙洲巨树 | sable | wind/leaves |
| 10 | 迷途雪墟 | lost | winter_woods |
| 11 | 极光雪原 | snow | snow_day |
| 12 | 纯白冰岸 | iceside | blizzard |

源片取自 `videos100mins/*.ogv` 中段稳定镜头（约 t=2992s，15s）。

## 技术

- 纯静态 `index.html`（内联 CSS/JS）
- `media/region-XX.mp4` + `media/region-XX.jpg`（poster）
- `audio/region-XX.mp3`（Soundscape Mixer / R8000_22_ACEStep_CIRCONS）
- 右侧导航点随滚动高亮；顶栏进度条；卡片入场；视频与 BGM 邻近预加载
- 可置于任意静态托管 / Cloudflare 反代之前

## 许可与署名

影像与环境音为摩奇酒馆自制素材；Soundscape 采样许可见生成工具 `CREDITS.md`（CC0 / Mixkit）。
