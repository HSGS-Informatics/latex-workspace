# LaTeX Workspace

Template này sẽ giúp bạn thiết lập một môi trường để soạn thảo và biên dịch LaTeX tiện lợi và không phải lo nghĩ nhiều đến chuyện cài đặt.

## Lợi ích

- Soạn thảo và biên dịch LaTeX thông qua VSCode, có hỗ trợ LaTeX cực tốt.
  - Soạn thảo có Intellisense và highlight đẹp, dịch tự động LaTeX và xem ấn phẩm ở bên cạnh.
  - Có từ điển kí hiểu và biểu tượng Toán.
- Đảm bảo mỗi máy đều có cùng môi trường trình biên dịch và các tham số, không phải lo thiếu package hay sai lệch môi trường giữa các máy nữa, nhờ Docker và VSCode sharable settings.
- Làm cùng nhau trực tiếp, hỏi nhau trực tiếp thông qua Live Share.
- Kiểm soát phiên bản, quản lý dự án khoa học bằng Git, và host mã nguồn trên Github.
- Github Actions quản lý CI/CD, cho phép dịch và quản lý phiên bản ấn phẩm rất dễ dàng.

## Sử dụng

Dưới đây là nôm na về workflow này.

1. Tất cả thành viên của project cần cài đặt VS Code, Docker và Git, cũng như có tài khoản GitHub.
2. Chủ project sẽ tạo một repo bằng template này, sau đó phổ biến cho tất cả thành viên.
3. Các thành viên clone repo về, tạo branch của mình và làm việc của mình trên branch đó. (Ở lần đầu biên dịch, một image TeXLive với đầy đủ các package khoảng 6GB sẽ được cài trên máy của bạn thông qua Docker.)
4. Khi các thành viên xong phần của họ trên branch, hãy tạo pull request để chủ project xem xét, sau đó nếu thoả mãn các điều kiện thì chủ project sẽ merge branch đó vào main (là branch chứa ấn phẩm chính).
