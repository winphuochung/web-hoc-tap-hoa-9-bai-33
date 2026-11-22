# Web/app học tập — Hóa học 9, Bài 33

**Bài 33: Sơ lược về hoá học vỏ Trái Đất**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Bài này không có thí nghiệm hoá học trong SGK, nên phần Mô phỏng gồm 2 hoạt động tương tác trực quan:
1. Bảng 33.1 tương tác — bấm vào từng nguyên tố (O, Si, Al, Fe, Ca, Na, Mg, K) để xem hàm lượng (%) và vai trò, kèm biểu đồ cột.
2. Nhận biết các loại đá qua hình SVG — thạch anh (SiO2), dolomite (CaCO3·MgCO3), đá hoa cương, đá cẩm thạch — bấm vào từng mẫu đá để xem thành phần hoá học, dạng chất và ứng dụng.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm hiện tại chỉ lưu trên máy học sinh (localStorage, điểm cao nhất).

## Trạng thái gửi điểm về Google Sheets

- **/exec chưa có — sẽ patch sau.** Google Sheet kết quả của bài đã có: https://docs.google.com/spreadsheets/d/1ep1gpZx2rA7NyVXsXaWwswZrshf57ivbc2PQjjGpvSM/edit (tab KetQua). File `Code.gs` trong thư mục này là mã Apps Script sẽ deploy cho Sheet đó. Khi có link Web App /exec, file `index.html` sẽ được patch thêm fetch gửi điểm (không cần sửa gì khác).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai33.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — mã Apps Script ghi điểm về Google Sheets (chờ deploy lấy /exec).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo cá nhân của Thầy (PNG 500×500, trong suốt).
