CÁC LỆNH GIT CƠ BẢN

"git được chia thành nhiều nhánh. Nhánh master được đăt làm mặc định, các thành viên trong
team làm việc trên các nhánh khác nhau sau đó được kiểm tra lại và duyệt vào nhánh master."

*CÁCH CÀI ĐẶT CẤU HÌNH CHO GIT
git config --list (kiểm tra cấu hình cài đặt git) 
git config --global user.name manh (thêm tên đăng nhập)
git config --global user.email manhthenguyen113@gmail.com (thêm email)
git config --global user.password 0987739823asD (thêm mật khẩu)
git config --global --unset-all (đăng xuất git)

*CÁCH ĐẨY CODE TỪ MÁY LÊN GITHUB
Bước 1: khởi tạo: git init
Bước 2: thêm file: + git add . (thêm toàn bộ file vừa được tạo mới)
Bước 3: kiểm tra: git status (kiểm tra trạng thái hoạt động của các file)
Bước 4: git commit -m 'Nội dung commit'
Bước 5: git remote add origin https://github.com/manhz2003/Learn_js.git
(user link của project cần tạo, chỉ cần thêm bước này khi lần đầu tạo project)
Bước 6: git push -u origin master (có thể thay master thành tên của nhánh khác)

*CÁCH CLONE CODE TỪ GITHUB VỀ MÁY
Bước 1: Chọn vị trí cần clone
Bước 2: git colone https://github.com/manhz2003/Learn_js.git
(sử dụng link clone tương ứng)
Bước 3: dịch chuyển vị trí: cd tên thư mục clone (ví dụ: cd WEB) 
(lệnh cd để dịch chuyển vị trí, cần cd đến folder chứa file clone)
Bước 4: tạo nhánh: git checkout -b tên nhánh (ví dụ: git checkout -b manh1)
Bước 5: git add .
Bước 6: git commit -m 'nội dung commit'
Bước 7: git push origin tên nhánh (ví dụ: git push origin manh1)

*LƯU Ý: + PHẢI CD ĐẾN ĐÚNG VỊ TRÍ CLONE
        + CHỈ ĐƯỢC TẠO FILE MỚI NẰM BÊN TRONG THƯ MỤC CLONE, K SẼ BỊ LỖI
        + git pull (để cập nhật thay đổi từ nhánh chính về máy)

*TÓM TẮT LỆNH CƠ BẢN

git init
git add .
git status
git commit -m 'change new'
git push
git checkout -b branchNew
git push origin branchNew
git pull
git config --global --unset-all
git config --global user.email
git config --global user.name
git config --global user.password
git config --list
git remote add origin



test pull


