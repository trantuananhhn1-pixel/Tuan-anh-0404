# SinhVideoNgan 1.13.0 — R4, cắt Link Video theo mức mới

**[Tải EXE đầy đủ R4 — khoảng 150 MiB](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/SinhVideoNgan_v1.13.0_ThuyetMinh_EN_R4.exe)**

Tải về và mở trực tiếp trên Windows 64-bit. Đóng bản cũ trước khi mở file R4. Không cần ghép file, PowerShell hoặc Python.

## Thiết lập mới cho Link Video

| Nội dung | R4 |
| --- | --- |
| Tổng thời lượng kế hoạch | **20–30 giây/video** |
| Số đoạn ghép | **4 hoặc 5 đoạn/video** |
| Độ dài mỗi đoạn | **5–8 giây** |

Tool chia tổng thời gian cùng số đoạn để không để đoạn cuối dưới 5 giây. Với 4 đoạn, tổng 20–30 giây; với 5 đoạn, tổng 25–30 giây vì mỗi đoạn tối thiểu 5 giây. Điểm bắt đầu các đoạn vẫn lấy ngẫu nhiên từ video nguồn; cơ chế hạn chế trùng giữa nhiều video giữ nguyên.

Video nguồn phải dài ít nhất **5 giây**. Nguồn ngắn hơn được báo lỗi rõ theo từng dòng; những dòng hợp lệ sau vẫn tiếp tục. Thời lượng file mã hóa có thể lệch nhẹ so với kế hoạch do khung hình, chẳng hạn 20.000 giây thành 19.960 giây ở 25 fps.

Khi dùng Link Video, nhật ký có dòng **“Cắt video R4: 20–30 giây, 4–5 đoạn, mỗi đoạn 5–8 giây.”**

## Các phần giữ nguyên

- Tạo từ ảnh vẫn theo số ảnh và thời gian quét đã chọn. Nếu dòng có Thư mục ảnh thì vẫn ưu tiên ảnh và bỏ qua link; không áp giới hạn 20–30 giây cho chế độ ảnh.
- Giữ nguyên 10 giọng tiếng Anh nam/nữ và lựa chọn đã lưu từ R3. Vào **2. Cấu hình → Giọng đọc** để chọn, Jenny vẫn là mặc định.
- Giữ các sửa lỗi nhận cột lời thuyết minh từ R2, ghép tiếng và các thiết lập dựng hình cũ. Bốn module giọng đọc/giao diện/âm thanh giống hệt R3 nên phần nhật ký giọng vẫn ghi R3.

Dùng cột **Lời thuyết minh** trong bảng hoặc Excel như trước; cần Internet để tạo tiếng. Dòng trống giữ cách tạo video không tiếng.

## Kiểm tra

**89 kiểm thử tự động đã qua**, gồm các biên tổng thời lượng/số đoạn/độ dài từng đoạn, dựng bằng hàm FFmpeg gốc, xử lý nguồn ngắn, giữ nguồn tải dùng chung/tên file/giọng chọn, và luồng tạo từ ảnh không đổi. Giao diện R4 chưa chạy trực tiếp trên Windows trong môi trường này.

[Mã phần bổ sung R4, công cụ đóng gói, kiểm thử và nguồn/giấy phép LGPL](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/MaNguonBoSung_ThuyetMinh_EN_R4.zip).

Tất cả 6.135 mục gốc được giữ nguyên. File EXE gốc và nhánh main không bị ghi đè. Các bản cũ giữ lại để tham khảo; tải R4 ở đầu trang để dùng mức cắt mới.

SHA-256 EXE R4:

```text
4c6fe3574b0101cf4cd654d3ec0158ebd70dbc19bb7a4397351648a5b9f08a9c
```
