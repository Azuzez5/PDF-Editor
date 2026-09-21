# Paperbox

Ứng dụng web lưu trữ PDF và chú thích trực tiếp trong trình duyệt.

## Chạy

```bash
python3 -m http.server 5173 --bind 0.0.0.0
```

Mở `http://localhost:5173`.

## Có gì trong bản MVP

- Upload nhiều PDF và lưu cục bộ bằng IndexedDB.
- Tìm kiếm, sắp xếp, lọc tài liệu.
- Mở PDF bằng PDF.js.
- Công cụ bút tự do, tô sáng, thêm văn bản, màu sắc, zoom.
- Ghi chú được lưu riêng theo từng file; PDF gốc không bị thay đổi.

PDF.js được tải từ CDN ở lần đầu mở tài liệu, nên cần kết nối mạng. Dữ liệu PDF và ghi chú không rời khỏi trình duyệt.
