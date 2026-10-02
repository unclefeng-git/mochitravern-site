# Region background loops

Generated with Soundscape Mixer (`R8000_22_ACEStep_CIRCONS`) via
`micromamba run -n soundscape python -m soundscape render …` on 2026-10-02.
Each file is ~60s stereo MP3 @ 128 kbps, intended to loop.
Post-processed with ffmpeg `loudnorm` to integrated ~−16 LUFS, true peak ≤ −1.5 dBTP
so region crossfades share one `TARGET_VOL` (0.28) in `index.html`.

Mapped to the 13 looping video scenes under `media/region-XX.mp4`.

| File | Region | Source clip | Scene / layers |
|------|--------|-------------|----------------|
| region-00.mp3 | 巴陶暖岸 | seaside_batrau | `seaside_dusk` |
| region-01.mp3 | 彼岸棕影 | sea_other_side | blank: ocean/waves/leaves/wind/seagulls/crickets |
| region-02.mp3 | 风车汀泽 | riverside | `wind_farm` + ocean/stream/wind/turbine/birds |
| region-03.mp3 | 古木密林 | arbre | `forest_dawn` |
| region-04.mp3 | 金穗废墟 | champ | `wheat_dusk` + wheatfield/wind/leaves/crickets/birds |
| region-05.mp3 | 拱脊暗山 | montain | `mountain_stream` + wind/stream/leaves/birds/drip |
| region-06.mp3 | 卧佛森域 | buddha | `temple_night` + rain/thunder/leaves/woodenfish/bells/crickets/wind |
| region-07.mp3 | 残响圣堂 | cathédrale | `temple_garden` + bells/windchimes/leaves/birds/wind/stream/woodenfish |
| region-08.mp3 | 极光听台 | rada | blank: snow/wind/cosmos/leaves |
| region-09.mp3 | 沙洲巨树 | sable | blank: wind/leaves/birds/wheatfield/crickets |
| region-10.mp3 | 迷途雪墟 | lost | `winter_woods` + snow/wind/leaves/cosmos |
| region-11.mp3 | 极光雪原 | snow | `snow_day` + snow/wind/cosmos/leaves |
| region-12.mp3 | 纯白冰岸 | iceside | `blizzard` + snow/wind/cosmos |
