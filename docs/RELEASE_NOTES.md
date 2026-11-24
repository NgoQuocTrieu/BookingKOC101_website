# Release notes

## v1.0 (bản nộp A3)

- 5 trang: trang chủ, quy trình, mẫu tin nhắn, hỏi đáp, xác nhận.
- Bố cục responsive ở 3 mức: trên 900px, 641–900px, từ 640px trở xuống.
- Form hỏi đáp kiểm tra họ tên, email, câu hỏi tối thiểu 10 ký tự, ô đồng ý.

Lỗi đã sửa trước khi phát hành:

- Hình minh họa trang chủ: mũi tên Brief → Booking thiếu đầu mũi tên. Nguyên nhân: một thẻ `<path>` vẽ hai đoạn nên `marker-end` chỉ gắn vào đoạn cuối. Cách sửa: tách thành hai thẻ `<path>` (index.html).
- Form ở màn hình 375px: dấu * của ô đồng ý bị đẩy ra mép phải. Nguyên nhân: label dùng flex nên dấu * thành một phần tử riêng. Cách sửa: bọc chữ và dấu * trong một `<span>` (lien-he.html).
- Màu số bước và nút cam: chữ trắng trên nền #e0663a chỉ đạt tương phản 3,43:1, dưới mức 4,5:1 của WCAG AA cho chữ thường. Cách sửa: đổi biến `--mau-nhan` sang #b84d26 (5,09:1) trong css/style.css; đổi cùng màu trong index.html và assets/logo.svg.
