# UTH Xanh 🌱

Prototype ứng dụng di động minh họa cho đề tài:

> **"Áp dụng tư duy thiết kế để giảm rác thải nhựa và thúc đẩy tái chế trong khuôn viên các cơ sở đào tạo của trường UTH"**

Ứng dụng mô phỏng một hệ thống thu gom – phân loại – tái chế rác thải trong khuôn viên trường, khuyến khích sinh viên tham gia thông qua cơ chế tích điểm và đổi quà.

## Chức năng chính

| # | Chức năng | Mô tả |
|---|-----------|-------|
| 0 | **Trang chủ** | Tổng quan điểm tích lũy, hạng thành viên, lịch hẹn sắp tới, hoạt động gần đây |
| 1 | **Đặt lịch hẹn** | Đặt lịch hẹn thợ đến tận nơi thu gom rác tái chế |
| 2 | **Cân rác & tích điểm** | Thợ nhập cân nặng thực tế → tự động quy đổi thành điểm |
| 3 | **Đổi quà tặng** | Dùng điểm tích lũy đổi các phần quà thân thiện môi trường |
| 4 | **Hồ sơ & lịch sử** | Xem thông tin cá nhân, hạng thành viên, lịch sử hoạt động |
| 5 | **Thùng rác thông minh** | Tìm thùng rác gần nhất để tự nộp rác nếu không đặt lịch |

## Công nghệ sử dụng

- HTML / CSS / JavaScript thuần (không cần framework, không cần cài đặt gì thêm)
- Toàn bộ dữ liệu lưu tạm trong bộ nhớ trình duyệt khi đang mở trang (không dùng backend/database — đây là bản mô phỏng/prototype)

## Cách chạy chương trình

### Cách 1 — Chạy trực tiếp trên máy
1. Tải file `index.html` về máy
2. Nhấp đúp vào file → trình duyệt sẽ tự mở và chạy ứng dụng

### Cách 2 — Chạy online qua GitHub Pages
Nếu repo đã bật GitHub Pages, truy cập:
```
https://<ten-tai-khoan-github>.github.io/<ten-repo>/
```

## Cấu trúc thư mục

```
uth-xanh-app/
├── index.html     # Toàn bộ giao diện + logic ứng dụng (1 file duy nhất)
└── README.md      # Tài liệu mô tả dự án
```

## Ghi chú

Đây là bản **prototype minh họa** cho quy trình tư duy thiết kế (Design Thinking), phục vụ mục đích trình bày ý tưởng / báo cáo học phần. Chưa kết nối hệ thống backend, cơ sở dữ liệu, hay tài khoản người dùng thật.
