Giới thiệu <a name="intro"></a>

Boilerplate này được tạo ra để tạo ứng dụng NextJS dễ dàng và nhanh chóng hơn.

Bắt đầu: <a name="getting-started"></a>

Nếu bạn đang sử dụng Windows, chạy các lệnh sau:

git config --global core.eol lf

git config --global core.autocrlf input

Lệnh này sẽ chuyển đổi EOL (End of Line) giống như trên Linux/Mac. Nếu không làm điều này, bạn có thể gặp conflict với các đồng đội dùng hệ điều hành khác và các bash script của dự án sẽ không hoạt động đúng.

Clone repository này.

Cài đặt pnpm toàn cục:

npm install -g pnpm


(Đảm bảo Node version >= 18)

Cài đặt các package:

pnpm install

Chạy server phát triển
pnpm dev


Mở http://localhost:3000
 trên trình duyệt để xem kết quả.

Bạn có thể bắt đầu chỉnh sửa trang bằng cách sửa file app/page.tsx. Trang sẽ tự động cập nhật khi bạn chỉnh sửa.

Dự án này sử dụng next/font
 để tối ưu và tải font tự động với font Geist
, một font mới của Vercel.

Tìm hiểu thêm

Để tìm hiểu thêm về Next.js, tham khảo các tài nguyên sau:

Tài liệu Next.js
 - tìm hiểu các tính năng và API của Next.js.

Học Next.js
 - tutorial tương tác về Next.js.

Bạn cũng có thể xem repository Next.js trên GitHub
 - phản hồi và đóng góp đều được hoan nghênh!
