# Energy Aurora

Aurora Holding · Học đầu tư Buffett + săn ngọc thô ngành năng lượng Việt Nam.

## GitHub Pages

1. **Settings → Pages** → Deploy from branch `main` / folder `/ (root)`
2. URL: https://aurorahoulding.github.io/energy-aurora/

## Files

| File | Mô tả |
|------|--------|
| `index.html` | App chính (v5.4.24 · Card = Source of Truth · 4 trang cockpit · đơn vị giá nghìn đồng) |
| `App1.b64` | Bản backup Base64 của HTML (giải mã khi cần) |
| `manifest.webmanifest` | PWA settings (standalone, theme dark) |
| `*.png` / `*.jpeg` | Icon / ảnh |

## Giải mã App1.b64 → HTML

```bash
base64 -d App1.b64 > index.html
```

## Chuẩn card (DPM)

- Trang 1 Snapshot · 2 Doanh nghiệp · 3 Tiền & BCTC · 4 Phán đoán
- Rank đọc Giá HT/NT từ thẻ (đơn vị **nghìn đồng**)
- Update BCTC → sửa card → Quét lại Rank

*Không phải khuyến nghị mua bán.*
