# SinhVideoNgan 1.13.0 — R3, chọn 10 giọng tiếng Anh

**[Tải EXE đầy đủ R3 — khoảng 150 MiB](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/SinhVideoNgan_v1.13.0_ThuyetMinh_EN_R3.exe)**

Tải về rồi mở trực tiếp trên Windows 64-bit. Không cần ghép file, chạy PowerShell hoặc cài Python.

1. Đóng bản tool cũ, mở `SinhVideoNgan_v1.13.0_ThuyetMinh_EN_R3.exe` vừa tải.
2. Trong **2. Cấu hình → Giọng đọc**, chọn giọng tiếng Anh trước khi bấm tạo video. Mỗi lựa chọn ghi rõ tên, nam/nữ và vùng giọng.
3. Nhập nội dung riêng cho từng dòng ở cột **Lời thuyết minh** trong bảng hoặc Excel; chọn giọng áp dụng cho toàn bộ lượt chạy.
4. Tạo video như trước. Cần Internet để tạo âm thanh. Tool nhớ giọng đã chọn cho lần mở sau.

| Giọng nữ | Giọng nam |
| --- | --- |
| Jenny — Mỹ | Guy — Mỹ |
| Aria — Mỹ | Christopher — Mỹ |
| Ana — Mỹ | Eric — Mỹ |
| Sonia — Anh | Ryan — Anh |
| Natasha — Úc | William — Úc |

**Jenny vẫn là mặc định** để giữ cách đọc từ R2. Các thiết lập chất lượng, dựng hình, tốc độ quét ảnh và lựa chọn cũ giữ nguyên. Vẫn hỗ trợ Excel cũ và sửa lỗi cột lời thuyết minh trùng tên từ R2.

Giọng được chốt lúc bấm bắt đầu. Đổi giọng trong khi tác vụ đang chạy chỉ có hiệu lực cho lượt chạy sau. Âm thanh được lưu tạm riêng theo cả nội dung và giọng để không dùng nhầm giọng.

Dòng cố ý để trống lời đọc dùng quy trình không tiếng như bản gốc. Với dòng có lời, nhật ký R3 ghi giọng đang dùng và kiểm tra âm thanh trước khi báo thành công. Giữ nguyên thời lượng video; lời quá dài được tăng tốc như các bản bổ sung trước.

**81 kiểm thử tự động đã qua**, gồm cả 10 lựa chọn tạo SSML đúng giọng/vùng, lưu và khôi phục lựa chọn, mặc định Jenny, chọn giọng nam qua presenter/quy trình tạo video gốc, giữ cấu hình cũ, ghép và kiểm tra âm thanh bằng FFmpeg thật. Người dùng đã xác nhận R2 Jenny có âm thanh trên Windows. Giao diện R3 và cả 10 giọng trực tuyến chưa được kiểm tra trực tiếp trong môi trường này.

[Mã phần bổ sung R3, công cụ đóng gói, kiểm thử và nguồn/giấy phép LGPL](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/MaNguonBoSung_ThuyetMinh_EN_R3.zip).

Tất cả 6.135 mục gốc được giữ nguyên. File EXE gốc và nhánh `main` không bị ghi đè. Các file R1/R2 giữ lại để tham khảo; dùng R3 để chọn giọng.

SHA-256 EXE R3:

```text
7dac115ce7304912cd1aa8e7506e5119abcf695695ed9bfc5140a3db29f38e57
```
