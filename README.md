# Sổ Nợ

Web app ghi nợ và chia tiền, cài lên màn hình chính iPhone như một app thật. Dữ liệu lưu ngay trên máy, không gửi đi đâu.

## Đưa lên GitHub Pages

1. Tạo repo mới trên GitHub, ví dụ `so-no`.
2. Tải tất cả file trong thư mục này lên repo (kéo thả vào trang repo > Add file > Upload files). Giữ nguyên thư mục `icons`.
3. Vào Settings > Pages. Ở mục Branch chọn `main`, thư mục `/ (root)`, bấm Save.
4. Chờ 1 đến 2 phút. Địa chỉ app sẽ là `https://TEN-GITHUB.github.io/so-no/`.

## Cài lên iPhone

1. Mở địa chỉ trên bằng **Safari** (không dùng Chrome).
2. Bấm nút Chia sẻ > **Thêm vào Màn hình chính** > Thêm.
3. Mở app từ biểu tượng "Sổ Nợ" ở màn hình chính.

## Sao lưu, khôi phục và Excel

Bấm nút **Sao lưu** ở góc trên bên phải app.
- **Lưu file sao lưu**: tạo file .json chứa toàn bộ sổ. Trên iPhone sẽ hiện bảng chia sẻ, chọn "Lưu vào Tệp" hoặc gửi cho chính mình qua Zalo/iCloud.
- **Khôi phục**: chọn lại file .json để đưa sổ về máy (thay sổ hiện tại).
- **Xuất Excel**: tạo file .xlsx gồm 4 trang (Sổ, Ai nợ, Theo tuần, Theo tháng) để xem và làm báo cáo.

## Lưu ý

- Dữ liệu trong Safari và dữ liệu trong app đã cài là **hai nơi riêng biệt**. Hãy cài app xong rồi mới bắt đầu ghi.
- Xóa dữ liệu trang web của Safari hoặc gỡ app sẽ mất sổ.
- Repo công khai thì ai cũng xem được mã nguồn, nhưng sổ của bạn nằm trên máy bạn nên không ai thấy. Phiên bản này không chứa tên hay số liệu nào.
- Khi cập nhật app, đổi `so-no-v2` trong `sw.js` thành `so-no-v3` để iPhone tải bản mới.
