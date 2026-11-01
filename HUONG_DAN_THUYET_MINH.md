# SinhVideoNgan 1.13.0 — Thuyết minh tiếng Anh R2

**[Tải file EXE đầy đủ — Thuyết minh tiếng Anh R2, khoảng150 MiB](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/SinhVideoNgan_v1.13.0_ThuyetMinh_EN_R2.exe)**

Giọng nữ tiếng Anh Mỹ **Jenny** (`en-US-JennyNeural`). Tải file EXE rồi mở trực tiếp trên Windows64-bit; không cần ghép file, PowerShell hoặc Python.

1. Đóng bản tool cũ, mở `SinhVideoNgan_v1.13.0_ThuyetMinh_EN_R2.exe` vừa tải.
2. **Nhập lại file Excel** trong tool để lời thuyết minh được đọc lại. Bảng lưu từ lần trước có thể đang trống phần lời đọc.
3. Kiểm tra cột cuối **Lời thuyết minh** trong bảng của tool đã hiện đúng nội dung tiếng Anh.
4. Bấm tạo video. Với một dòng có lời đọc, nhật ký phải hiện **“Thuyết minh R2: 1/1 dòng có lời đọc”**, tiếp đến bước tạo giọng Jenny và ghép âm thanh. Cần Internet.

Nếu ghi`0/1 dòng có lời đọc`, nội dung chưa vào bảng của tool; không nên coi video không tiếng của lượt đó là đã tạo thuyết minh thành công. Dòng cố ý để trống vẫn giữ quy trình không tiếng của bản gốc.

## R2 sửa gì?

- Sửa trường hợp Excel có cột H lời thuyết minh trống và cột I cùng tên có nội dung: đọc đúng nội dung có chữ. Các cột trùng có cùng nội dung được chấp nhận; nội dung khác nhau báo lỗi rõ ràng.
- Nhận đúng tiêu đề lời thuyết minh có dấu Unicode tổ hợp, khoảng trắng đặc biệt hoặc ký tự ẩn.
- Chuyển giọng sang nữ tiếng Anh Mỹ Jenny theo yêu cầu.
- Thêm trạng thái R2 và số dòng nhận được lời đọc, kiểm tra giải mã âm thanh trước khi báo xuất video thuyết minh thành công.

Giữ nguyên6.135 mục gốc và các lựa chọn dựng hình. Phần hình ảnh được sao chép nguyên luồng khi ghép tiếng. Giữ thời lượng video; lời dài được tăng tốc như bản bổ sung trước. File EXE gốc và nhánh`main` giữ nguyên.

**64 kiểm thử tự động đã qua**, gồm Excel trùng cột→bảng→presenter→quy trình tạo video gốc với dịch vụ giọng đọc được mô phỏng, và FFmpeg ghép/kiểm tra âm thanh thật. Giọng đọc trực tuyến thực tế và giao diện Windows vẫn chưa được xác nhận trong môi trường này; đây là bản thử nghiệm cần kiểm tra trên máy Windows.

[Mã phần bổ sung R2, công cụ đóng gói và nguồn/giấy phép LGPL](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/MaNguonBoSung_ThuyetMinh_EN_R2.zip).

SHA-256 EXE R2:

```text
54dcd58468a24686e8cd457ad38fe47151958e2bdc4efe761a5eeeee48a2030b
```

Các file R1 và gói ZIP nhỏ cũ chỉ giữ để tham khảo. Dùng file EXE R2 ở đầu trang để thử sửa lỗi âm thanh và giọng tiếng Anh.
