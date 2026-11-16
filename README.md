# Echo of Thanks — Trạm Tri Ân Kỹ Thuật Số

**Đội thực hiện:** BYTE TRI ÂN · 5 thành viên  
**Cuộc thi:** CODE THE THANKS 2026  
**Loại hình:** Website tương tác

> Một lời cảm ơn, một tấm thiệp, một kỷ niệm được lưu giữ.

Echo of Thanks là website giúp sinh viên tạo lời tri ân và thiệp điện tử gửi đến thầy cô. Sản phẩm sử dụng HTML, CSS và JavaScript, có thể chạy ở chế độ tĩnh mà không cần cấu hình dịch vụ bên ngoài.

## 1. Tính năng

- **Tạo lời tri ân theo mẫu:** Chọn người nhận, bộ môn, kiểu nội dung (thư, thơ, lời chúc phong cách code hoặc ẩn dụ chuyên ngành) và sắc thái lời chúc. Website tạo nội dung bằng các mẫu JavaScript có sẵn để người dùng chỉnh sửa.
- **Thiệp điện tử cá nhân hóa:** Xem trước nội dung thiệp, mở phong bì tương tác và tạo thiệp theo thông tin đã nhập.
- **Tải thiệp PNG:** Xuất thiệp thành ảnh để lưu về máy hoặc chia sẻ.
- **Chia sẻ thiệp bằng đường link:** Mã hóa nội dung thiệp vào URL để người nhận mở lại thiệp.
- **Bức tường tri ân ở chế độ demo:** Hiển thị lời chúc mẫu và những lời chúc được lưu trên trình duyệt hiện tại.
- **Hiệu ứng trang trí và âm thanh:** Hoa rơi, hiệu ứng tương tác và giai điệu điện tử được tạo ngay trong trình duyệt; người dùng có thể bật/tắt âm thanh.
- **Thiết kế responsive:** Hỗ trợ màn hình máy tính và điện thoại.

## 2. Công nghệ sử dụng

- **HTML5:** Xây dựng cấu trúc và nội dung website.
- **CSS3:** Thiết kế giao diện, bố cục responsive, hiệu ứng và chuyển động.
- **JavaScript:** Xử lý biểu mẫu, tạo lời chúc theo mẫu, mở phong bì, tạo link chia sẻ và tương tác trên trang.
- **Browser localStorage:** Lưu lời chúc trên trình duyệt của thiết bị đang sử dụng.
- **Canvas API:** Kết xuất thiệp thành ảnh PNG.
- **Web Audio API:** Tạo giai điệu điện tử ngay trong trình duyệt.

## 3. Chạy website trên máy tính

### Cách nhanh nhất

1. Tải mã nguồn về máy và giải nén.
2. Mở thư mục dự án.
3. Nhấp đúp vào file `index.html` hoặc nhấn chuột phải → **Open with → Google Chrome**.
4. Chọn bộ môn, nhập tên thầy/cô và tên người gửi.
5. Chọn kiểu nội dung, sắc thái và nhấn **Tạo lời tri ân**.
6. Thử mở phong bì, tải thiệp PNG, sao chép link chia sẻ và gửi lời chúc lên bức tường.

Không cần cài Node.js, không cần chạy lệnh Terminal và không cần điền API key để sử dụng chế độ demo.

### Chạy bằng VS Code (tùy chọn)

1. Mở Visual Studio Code.
2. Chọn **File → Open Folder** và chọn thư mục dự án.
3. Mở file `index.html` để xem hoặc chỉnh sửa mã nguồn.
4. Lưu thay đổi bằng `Ctrl + S`, sau đó tải lại trang trên trình duyệt.

## 4. Đưa website lên GitHub Pages

Website là dự án tĩnh, có thể xuất bản trực tiếp bằng GitHub Pages.

1. Đăng nhập GitHub và tạo repository mới, ví dụ `echo-of-thanks`.
2. Đưa toàn bộ file và thư mục của dự án lên repository, giữ nguyên cấu trúc thư mục. Đặc biệt, `index.html` phải nằm ở thư mục gốc của repository.
3. Mở repository → **Settings → Pages**.
4. Trong **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn branch `main`, thư mục `/(root)`, sau đó nhấn **Save**.
6. Đợi GitHub Pages hoàn tất triển khai rồi mở địa chỉ website được hiển thị trong mục Pages.
7. Mở link bằng cửa sổ ẩn danh hoặc trên điện thoại để kiểm tra trước khi gửi ban tổ chức.

Sau mỗi lần cập nhật mã nguồn, commit thay đổi lên branch `main`; GitHub Pages sẽ triển khai lại website.

## 5. Hướng dẫn kiểm thử

- Thử tạo lời chúc cho các bộ môn Lập trình, Mạng máy tính, Toán rời rạc và Cơ sở dữ liệu.
- Thử các kiểu nội dung: thư, thơ, lời chúc phong cách code và ẩn dụ chuyên ngành.
- Thay đổi sắc thái lời chúc và kiểm tra nội dung thiệp.
- Mở và đóng phong bì 3D.
- Bật/tắt giai điệu.
- Tải ảnh PNG và mở file vừa tải để kiểm tra.
- Sao chép link thiệp, mở link trong tab hoặc cửa sổ khác.
- Gửi một lời chúc vào bức tường, tải lại trang và kiểm tra dữ liệu trên cùng trình duyệt.
- Kiểm tra bố cục trên cả máy tính và điện thoại.

## 6. Giới hạn của phiên bản hiện tại

- Nội dung lời tri ân được tạo bằng **mẫu JavaScript có sẵn**, không phải nội dung do mô hình AI trực tuyến sinh ra.
- Bức tường tri ân hoạt động ở chế độ demo: lời chúc mới được lưu trong `localStorage` của trình duyệt hiện tại. Dữ liệu không tự đồng bộ giữa các thiết bị hoặc giữa những người truy cập khác nhau.
- Bức tường có một số lời chúc mẫu để minh họa giao diện.
- Link chia sẻ thiệp mang nội dung thiệp trong URL; người chia sẻ nên tránh đưa thông tin riêng tư vào lời nhắn.
- Nếu xóa dữ liệu website trong trình duyệt hoặc đổi thiết bị/trình duyệt, các lời chúc lưu cục bộ có thể không còn.

Các giới hạn trên được nêu rõ để người trải nghiệm và ban giám khảo hiểu đúng những gì bản demo đang thực hiện.

## 7. Nhóm thực hiện

| Thành viên | Vai trò dự kiến |
|---|---|
| Đinh Thị Minh Quyên | Trưởng nhóm · Điều phối và tích hợp |
| Nguyễn Quân | Thiết kế UI/UX · Mỹ thuật |
| Trịnh Văn Quốc Nguyên | HTML · CSS · Responsive |
| Nguyễn Phúc Hàn Nguyên | JavaScript · Chức năng tương tác |
|  | Kiểm thử · Nội dung và truyền thông |
Nhóm cần xác nhận họ tên và vai trò theo đúng phần việc thực tế trước khi nộp hồ sơ.

## 8. Cấu trúc thư mục

```text
 echo-of-thanks/
 ├── index.html          # Trang chính
 ├── styles.css          # Giao diện và hiệu ứng
 ├── app.js              # Tương tác và chức năng website
 ├── config.js           # Cấu hình tùy chọn (để trống ở bản demo)
 ├── assets/
 │   └── favicon.svg     # Biểu tượng website
 ├── api/                 # Mã nguồn mở rộng, không cần cho bản demo tĩnh
 └── supabase/            # Tài liệu SQL mở rộng, không cần cho bản demo tĩnh
```

**Phiên bản nộp hiện tại:** chạy ở chế độ website tĩnh/demo. Chỉ cần xuất bản các file giao diện và mã JavaScript cùng thư mục `assets` là có thể trải nghiệm các tính năng demo.
