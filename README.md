# ozon-assets

OZON 商品图公网托管（GitHub Pages）。

OZON 只接受公网直链，图片由 OZON 服务端抓取，所以这个仓库必须是 public。
图源来自 1688 供应商详情页，经 `ozon-work/tools/listing_images.py` 抠图重排：
俄语文案、900×1200（3:4）、无中文、无水印。

## 目录

- `oilcan/<offer_id>-01.jpg` 主图
- `oilcan/<offer_id>-02.jpg` 尺寸图
- `oilcan/<offer_id>-03.jpg` 结构细节图

## URL

```
https://zanyang77-netizen.github.io/ozon-assets/oilcan/<offer_id>-01.jpg
```

## 重新生成

```powershell
cd D:\ai-profile\projects\ozon-work
python tools/listing_images.py --out evidence/images/listing
# 然后拷到本仓库 oilcan/ 并提交
```
