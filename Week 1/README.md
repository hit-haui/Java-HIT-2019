# Buổi 1: Git, GitHub và những câu lệnh của Git
## Định nghĩa
- GitHub có thể hiểu đơn giản là kho lưu trữ `chủ yếu là code`. Đây là những cái chủ yếu mà GitHub được sử dụng:
  - Lưu trữ `mốc thời gian` code của bạn, điều này giúp bạn có thể trở về quá khứ để lấy lại code cũ do những sai sót trong lúc code
  - Tạo một `bản giới thiệu` sơ qua những gì bạn muốn một cách vừa đẹp vừa dễ dàng với README.md
  - Các thao tác giúp bạn và mọi người `cùng làm dự án` một cách quy củ, hợp lí (phần này gồm rất nhiều chi tiết như branch, pull requests, ...)
  - .... Còn cả một kho tàng của GitHub nữa mà các bạn có thể đọc thêm ở [link này](https://en.wikipedia.org/wiki/GitHub)
- Git là một công cụ vận chuyển code bằng các câu lệnh máy tính thông qua một số phần mềm như GitBash, GitDesktop, ....
## Nội dung bài học
- Làm quen với cách vận chuyển của GitBash thông qua một số câu lệnh thường dùng
  - `git status` ( Kiểm tra các file bị thay đổi đã được git quản lí hay chưa )
    * Xanh là được quản lí, đỏ là chưa được quản lí
  - `git add` ( Cấp quyền quản lí cho git quản lí )
    * git add "Tenfile" => thêm một file cho git quản lí
    * git add . , git add * => thêm tất cả file cho git quản lí
  - `git commit` ( Xác nhận và đánh dấu thời điểm git quản lí giữ liệu )
    * git commit -m "Message" => Tạo tiêu đề cho 
  - `git push` ( Đưa giữ liệu lên trên GitHub )
    * git push => Sẽ tự tìm đến đúng nhánh đang dùng để tải lên nhánh đó trên GitHub
    * git push + origin(remote) + "tên nhánh" => tải lên nhánh đó
  - `git clone` ( Tải về máy repos )
    * git clone + "Đường dẫn đến repos" => Chỉ để tải repos
  - `git pull` ( Cập nhật những cái trên repos trên mạng có mà repos trên máy ko có )
    * git pull => Tự tìm đến nhánh trên máy để pull về
- Cách tạo một file txt trên GitHub: vào phần `create new file` ở repos để tạo
  - Hình minh họa 
![Untitled](https://user-images.githubusercontent.com/52252046/65958070-b4adac80-e478-11e9-86c1-04478665cbcc.png)
![Untitled2](https://user-images.githubusercontent.com/52252046/65958138-e888d200-e478-11e9-9a4e-058cca2f0257.png)
![Untitled3](https://user-images.githubusercontent.com/52252046/65958194-081ffa80-e479-11e9-9fb5-92673da254b0.png)
- Cách thêm một người cho repos của bạn
  - Ảnh minh họa
![Untitled4](https://user-images.githubusercontent.com/52252046/65958488-b166f080-e479-11e9-9ac5-644ab9d3e220.png)
![Untitled5](https://user-images.githubusercontent.com/52252046/65958494-b3c94a80-e479-11e9-96b9-e25ce7b20ead.png)
## Tổng kết
- Giới thiệu và làm quen các thành viên trong lớp
- Biết tổng quan về Git, GitHub và các câu lệnh của Git
- Sử dụng các câu lệnh để có thể lưu trữ
