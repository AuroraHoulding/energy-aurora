# Energy Aurora

**Aurora Holding** · Học đầu tư Buffett + săn ngọc thô ngành năng lượng Việt Nam.

Phiên bản: **v5.4.24** (single-file cockpit, 121 thẻ, Rank, Game Tycoon, Lab, BCTC).

## Chạy trên web (GitHub Pages)

1. Vào repo → **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` · Folder: `/ (root)`
4. Save

**URL công khai:**  
https://aurorahoulding.github.io/energy-aurora/

*(Sau khi push, GitHub Pages cập nhật trong 1–3 phút.)*

## Cài như App (PWA)

- Mở link trên Chrome / Safari / Edge
- Chọn **“Thêm vào màn hình chính”** / **Install**
- `manifest.webmanifest` + Service Worker (`sw.js`) đã cấu hình offline cơ bản

## Cấu trúc file

| File | Mô tả |
|------|--------|
| `index.html` | Toàn bộ app (thẻ, Rank, Lab, Game, cockpit 4 trang) |
| `manifest.webmanifest` | PWA manifest |
| `sw.js` | Service Worker cache offline |
| `assets/` | Icon 192/512 (thêm PNG nếu muốn icon đẹp khi cài) |

## Cập nhật

Chỉ cần ghi đè `index.html` rồi:

```bash
git add index.html
git commit -m "update: index.html"
git push
```

## Lưu ý

- Không phải khuyến nghị đầu tư.
- Dữ liệu BCTC / giá trên thẻ cần được cập nhật thủ công (viền đỏ = đã có BCTC).
- Game Energy Tycoon lưu trên `localStorage` của trình duyệt.
