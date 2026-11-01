# Gói bổ sung thuyết minh cho SinhVideoNgan 1.13.0

[Tải gói ZIP khoảng 293 KB](https://github.com/trantuananhhn1-pixel/Tuan-anh-0404/raw/refs/heads/codex/voiceover-download/BoSungThuyetMinh_Nho.zip).

Gói này dùng cùng file `SinhVideoNgan_v1.13.0.exe` gốc mà bạn đã có để tạo một file thử nghiệm mới. File gốc không bị ghi đè; không cần cài Python để ghép file.

1. Tải ZIP, giải nén toàn bộ vào một thư mục.
2. Chép `SinhVideoNgan_v1.13.0.exe` gốc vào thư mục vừa giải nén.
3. Mở thư mục đó, bấm thanh địa chỉ, nhập `powershell` rồi nhấn Enter.
4. Trong PowerShell, chạy:

   ```powershell
   .\TaoBanThuyetMinh.ps1
   ```

5. Khi báo thành công, mở `SinhVideoNgan_v1.13.0_ThuyetMinh_BanThu.exe` vừa tạo.
6. Trong bảng, kéo sang phải tới cột cuối **Lời thuyết minh**, nhập nội dung riêng cho từng dòng; hoặc nhập Excel mẫu đi kèm. Giọng đọc nữ tiếng Việt Hoài My cần Internet. Dòng trống dùng quy trình tạo video cũ.

Nếu Windows chặn chạy script theo chính sách PowerShell, hãy dừng và gửi lại nguyên thông báo lỗi. Gói không thay đổi chính sách hoặc cấu hình bảo mật của máy.

Lời đọc dài hơn video được tăng tốc để giữ nguyên thời lượng video. Nên nhập lời vừa với thời lượng để giọng giữ tốc độ tự nhiên.

Đây là **bản thử nghiệm**: 51 kiểm thử tự động đã qua, nhưng giao diện Windows, script PowerShell và giọng đọc trực tuyến thực tế chưa được xác nhận trên Windows. Việc ghép byte đã được kiểm tra độc lập, tạo đúng SHA-256 của bản thử nghiệm.

Trong gói có mã phần bổ sung và nguồn/giấy phép LGPL của phần giao thức tham khảo. File EXE gốc, các phụ thuộc gốc và nhánh `main` không được thay đổi bởi lần cung cấp này.

SHA-256 của `BoSungThuyetMinh_Nho.zip`:

```text
b408cde9c643843448395090313d29a19e6e787f2fe8ccb13b33561aa53ccd73
```
