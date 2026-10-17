# Little Atlas city packs (test set)

Static hosting for the Little Atlas app's downloadable city packs, served with GitHub Pages at
https://wzsgrmsz9g-png.github.io/littleatlas-cities/

- `manifest.json`: the city list (schema v2, per-file media). Paths in it are relative to the manifest.
- `cities/<slug>/v<N>/pack.json`: one city's places. Some versions also have `delta-from-v<N-1>.json`.
- `cities/<slug>/v<N>/attribution.json` and `CREDITS.md`: credits for every photo used by that city.
- `media/<xx>/<sha256>.webp`: one file per photo, named by its SHA-256.

## Photo licenses

Every photo comes from [Wikimedia Commons](https://commons.wikimedia.org/) and is licensed **CC BY, CC BY-SA, CC0 or public domain**. Photos were resized and converted to WebP; no other changes were made. Each photo is credited individually (author, license and a link to its Commons source page) in its city's `attribution.json` and `CREDITS.md`. Photos under CC BY-SA remain under their original share-alike license.

License counts across all 4048 image files:

- CC BY-SA 4.0: 2260
- CC BY-SA 3.0: 638
- CC0: 284
- CC BY 3.0: 276
- CC BY 2.0: 184
- CC BY 4.0: 184
- Public domain: 98
- CC BY-SA 2.5: 72
- CC BY-SA 2.0: 40
- CC BY 2.5: 10
- CC BY-SA 3.0 cn: 2

## Place data

Place data is © OpenStreetMap contributors (ODbL 1.0), plus Wikidata (CC0) and GeoNames (CC BY 4.0). Some cities include official open data; each `pack.json` lists its sources under `credits`.

## Cities

| City | Country | Places | Places with a photo | Image files | Credits |
|---|---|---|---|---|---|
| Calgary | CA | 343 | 49 | 244 | [attribution.json](cities/calgary-ca/v2/attribution.json) · [CREDITS.md](cities/calgary-ca/v2/CREDITS.md) |
| Chengtangcun | CN | 31 | 0 | 0 | [attribution.json](cities/chengtangcun-cn/v1/attribution.json) · [CREDITS.md](cities/chengtangcun-cn/v1/CREDITS.md) |
| Hefei | CN | 206 | 2 | 12 | [attribution.json](cities/hefei-cn/v1/attribution.json) · [CREDITS.md](cities/hefei-cn/v1/CREDITS.md) |
| Heze | CN | 24 | 0 | 0 | [attribution.json](cities/heze-cn/v1/attribution.json) · [CREDITS.md](cities/heze-cn/v1/CREDITS.md) |
| Hong Kong | HK | 1109 | 681 | 2894 | [attribution.json](cities/hong-kong-hk/v3/attribution.json) · [CREDITS.md](cities/hong-kong-hk/v3/CREDITS.md) |
| Jinan | CN | 201 | 10 | 44 | [attribution.json](cities/jinan-cn/v1/attribution.json) · [CREDITS.md](cities/jinan-cn/v1/CREDITS.md) |
| Jining | CN | 25 | 0 | 0 | [attribution.json](cities/jining-cn-25/v1/attribution.json) · [CREDITS.md](cities/jining-cn-25/v1/CREDITS.md) |
| Liaocheng | CN | 21 | 1 | 4 | [attribution.json](cities/liaocheng-cn/v1/attribution.json) · [CREDITS.md](cities/liaocheng-cn/v1/CREDITS.md) |
| Linyi | CN | 64 | 3 | 12 | [attribution.json](cities/linyi-cn/v1/attribution.json) · [CREDITS.md](cities/linyi-cn/v1/CREDITS.md) |
| Qingdao | CN | 199 | 13 | 62 | [attribution.json](cities/qingdao-cn/v1/attribution.json) · [CREDITS.md](cities/qingdao-cn/v1/CREDITS.md) |
| Shanghai | CN | 716 | 110 | 532 | [attribution.json](cities/shanghai-cn/v2/attribution.json) · [CREDITS.md](cities/shanghai-cn/v2/CREDITS.md) |
| Shenzhen | CN | 594 | 41 | 200 | [attribution.json](cities/shenzhen-cn/v2/attribution.json) · [CREDITS.md](cities/shenzhen-cn/v2/CREDITS.md) |
| Tai’an | CN | 47 | 0 | 0 | [attribution.json](cities/tai-an-cn-25/v1/attribution.json) · [CREDITS.md](cities/tai-an-cn-25/v1/CREDITS.md) |
| Weifang | CN | 109 | 4 | 18 | [attribution.json](cities/weifang-cn/v1/attribution.json) · [CREDITS.md](cities/weifang-cn/v1/CREDITS.md) |
| Yantai | CN | 101 | 3 | 12 | [attribution.json](cities/yantai-cn-25/v1/attribution.json) · [CREDITS.md](cities/yantai-cn-25/v1/CREDITS.md) |
| Yishui | CN | 8 | 0 | 0 | [attribution.json](cities/yishui-cn/v1/attribution.json) · [CREDITS.md](cities/yishui-cn/v1/CREDITS.md) |
| Zaozhuang | CN | 30 | 1 | 6 | [attribution.json](cities/zaozhuang-cn/v1/attribution.json) · [CREDITS.md](cities/zaozhuang-cn/v1/CREDITS.md) |
| Zhu Cheng City | CN | 17 | 1 | 2 | [attribution.json](cities/zhu-cheng-city-cn/v1/attribution.json) · [CREDITS.md](cities/zhu-cheng-city-cn/v1/CREDITS.md) |
| Zibo | CN | 43 | 0 | 0 | [attribution.json](cities/zibo-cn/v1/attribution.json) · [CREDITS.md](cities/zibo-cn/v1/CREDITS.md) |
| Zoucheng | CN | 24 | 1 | 6 | [attribution.json](cities/zoucheng-cn/v1/attribution.json) · [CREDITS.md](cities/zoucheng-cn/v1/CREDITS.md) |
