# Portfolio Nguyễn Linh Trang

Website một trang cho GitHub Pages. `index.html`, `style.css`, `script.js`, `content.js` và thư mục `assets/` phải nằm cùng cấp tại gốc repository.

## Chỉnh nội dung

Website đọc tab **CONTENT** trong [Google Sheet](https://docs.google.com/spreadsheets/d/1AV3PhrEyBjmQ2HLZyjVAnlF4Eun83CweX5uJhK0DisY/edit) khi mỗi người mở hoặc tải lại trang. Cột A là `key` cố định; sửa nội dung ở cột B `value`. Có thể di chuyển hàng nhưng không đổi `key`. Cột C là ghi chú. Nếu Sheet tạm không đọc được, trang hiển thị nội dung dự phòng từ `content.js`.

Để khách truy cập đọc được nội dung, tại **Chia sẻ → Quyền truy cập chung**, chọn **Bất kỳ ai có đường liên kết → Người xem**. Quyền chỉnh sửa Sheet có thể giữ riêng. Nếu muốn giấu nội dung trong Sheet thì trình duyệt công khai không thể tự đọc trực tiếp.

Các trường `image.*`, `case.*.image`, `case.*.evidence` nhận link ảnh công khai trên Drive, URL ảnh trực tiếp hoặc đường dẫn `assets/ten-file`. Ảnh Phở, Bún đậu, Pesto hiện lấy từ Drive và có bản trong `assets/` để dự phòng. Để thay ảnh mà giữ liên kết, cập nhật phiên bản của đúng file Drive. Nếu tải một file mới, dán link file mới vào cột `value`; trùng tên file không đồng nghĩa trùng liên kết.

Các trường `case.*.link` là link đến dự án hoặc tài liệu chi tiết; để trống thì nút không hiện. `contact.email_url` và `contact.phone_url` là đường dẫn của nút liên hệ.

## Đăng GitHub Pages

Tải tất cả file trong thư mục này lên gốc repository. Vào **Settings → Pages**, chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`. Sau khi Pages xuất bản, link có dạng `https://ten-tai-khoan.github.io/ten-repository/`.

`CONTENT.csv` là bản sao để nhập vào tab CONTENT nếu cần. Khi Sheet đã có tab CONTENT, file CSV chỉ phục vụ lưu trữ và có thể bỏ khỏi repository.

Ba ảnh món ăn đã tách nền và được gắn cố định trong thư mục assets. Các từ khóa quanh món ăn có thể sửa trong tab CONTENT.
`nChỉnh chữ chạy quanh ảnh ở các dòng case.joie.orbit, case.lep.orbit, case.olive.orbit trong tab CONTENT.

Ảnh mở đầu được cập nhật bằng cách dán link ảnh công khai vào dòng image.hero trong tab CONTENT. Ảnh ở phần About me dùng dòng image.child và image.adult.


Ảnh các chiến dịch được lưu trong assets/campaign và trình bày theo từng nhóm, có thể vuốt ngang để xem. Ảnh 2.1 và ảnh chiến dịch Joie sẽ bổ sung sau. Nội dung các chiến dịch và kết quả được chỉnh trong tab CONTENT, ở các dòng case.*.story.*. File ảnh 2.2 đã được tách nền bằng công cụ tạo ảnh và cần kiểm tra lại trước khi công bố.
