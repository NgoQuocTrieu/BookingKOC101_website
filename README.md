# Booking KOC 101

Website tĩnh HTML5/CSS3 hướng dẫn quy trình booking KOC TikTok cho người mới. Bài tập lớn A3, học phần FIT4014 Thiết kế web và triển khai hệ thống phần mềm, Trường Đại học Đại Nam.

## Nội dung

| Trang | Tệp | Nội dung |
|---|---|---|
| Trang chủ | index.html | Giới thiệu, người dùng, 6 bước tóm tắt |
| Quy trình | quy-trinh.html | Chi tiết 6 bước, bảng tiêu chí chọn KOC |
| Mẫu tin nhắn | mau-tin-nhan.html | Mẫu Zalo, Gmail, TikTok và danh sách kiểm tra |
| Hỏi đáp | lien-he.html | Câu hỏi thường gặp, form gửi câu hỏi |
| Xác nhận | cam-on.html | Trang hiện ra sau khi form hợp lệ |

## Cấu trúc thư mục

```
booking-koc-101/
├── index.html
├── quy-trinh.html
├── mau-tin-nhan.html
├── lien-he.html
├── cam-on.html
├── css/style.css
├── assets/logo.svg
├── docs/AI_LOG.md
├── docs/RELEASE_NOTES.md
└── README.md
```

## Cách mở

1. Tải repository về (Code > Download ZIP) hoặc `git clone`.
2. Mở `index.html` bằng Chrome, Edge hoặc Firefox. Không cần cài thêm gì.
3. Bản công khai: xem link GitHub Pages ở phần About của repository.
4. Link web demo: https://ngoquoctrieu.github.io/BookingKOC101_website/index.html

## Công nghệ

HTML5 (thẻ ngữ nghĩa, form có kiểm tra dữ liệu bằng thuộc tính `required`, `type="email"`, `minlength`), CSS3 (biến CSS, Grid, Flexbox, media query 900px và 640px, `:focus-visible`, `:user-invalid`). Không dùng JavaScript và thư viện ngoài.

## Giới hạn đã biết

- Form không gửi dữ liệu lên máy chủ. Khi hợp lệ, form chuyển sang `cam-on.html` và nội dung câu hỏi nằm trên thanh địa chỉ (phương thức GET).
- Trình duyệt cũ không hỗ trợ `:user-invalid` sẽ không tô đỏ ô sai, nhưng vẫn chặn gửi form.
- Mới kiểm thử trên Chrome. Firefox, Safari và điện thoại thật chưa kiểm tra.

## Nguồn

Nội dung viết từ kinh nghiệm làm booking của sinh viên thực hiện. Logo và hình minh họa là SVG tự vẽ. Công cụ AI đã dùng: xem `docs/AI_LOG.md`.
