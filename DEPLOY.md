# Deploy / cập nhật index.html

`App1.b64` = bản **v5.4.24** mới nhất (Card Source of Truth, đơn vị giá nghìn đồng, TTH MOS, 4 trang cockpit).

`index.html` trên repo hiện có thể còn bản cũ hơn. Làm mới:

```bash
# Clone
git clone https://github.com/AuroraHoulding/energy-aurora.git
cd energy-aurora

# Giải mã App1.b64 → ghi đè index.html
base64 -d App1.b64 > index.html

git add index.html
git commit -m "release: index.html from App1.b64 v5.4.24"
git push
```

## GitHub Pages

**Settings → Pages →** Branch `main` / folder `/ (root)`  
URL: https://aurorahoulding.github.io/energy-aurora/

## PWA

`manifest.webmanifest` đã cấu hình:
- name: Energy Aurora
- display: standalone
- theme: #0a0c14

(Icon trong `assets/` nếu có.)

## Giữ lại

| Giữ | Xóa / thay |
|-----|------------|
| App1.b64 | index.html cũ (ghi đè bằng decode) |
| manifest.webmanifest | — |
| README.md | — |
| ảnh icon | — |
