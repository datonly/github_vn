# Terms

Repository(Repo): thư mục của dự án vd: Github_vn
Branch: cành, dự án có thể có nhiều cành,cành mặc định của dự án là master

# Commands (lệnh)

- git init: làm dự án có thể sử dụng được git -> git respository
- git status: thấy được trạng thái, thấy được sự thay đổi của dự án
- git add: cho phép chuẩn bị lưu lại thời điểm hiện tại của dự án
  git add + tên file: chuẩn bị lưu lại file đó
  lưu lại toàn bộ file: git add .
- git reset: làm cho file không chuẩn bị lưu (trái với git add)
- git commit: chính thức lưu, đặc biệt cần ghi chú 1 chi tiết trước khi lưu.(cho biết quá trình dự án đang đến đâu hoặc cho biết đang làm feature gì)
  (git commit -m 'initial commit'): cam kết ban đầu hoặc thời điểm đầu tiên của dự án
- git log: xem thông tin, thời điểm các commit đã lưu
- git log --oneline (thông tin gọn hơn git log)
  Trình tự hiển thị kết quả:
  id commit+(HEAD->master)+ name commit
- git checkout + idcommit : trở lại thời điểm ban đầu của 1 commit
- git checkout + branchname: trở lại thời điểm hiện tại
- git branch: thấy được các cành hiện tại.
  Để thoát ra một câu lệnh git dùng phím: :q
  Phím tắt mở terminal: ctrl + ~
  Xóa các lệnh cũ: clear terminal
  - git checkout -b {branch name} : tạo ra một branch mới
    Áp dụng của branch khác nhau phụ thuộc vào tình huống:sẽ có TH công ty sẽ không động tới master brand mà trong lúc lập trình thì chỉ lập trình trên branch khác như dev,..
    Trên một dự án có nhiều chức năng khác nhau, mỗi chức năng sẽ chia ra cho một branch thì cần tổng hợp lại branch để hoàn thành dự án.
    VD: đã tạo branch là dev. Tạo trang liên hệ contact.html
