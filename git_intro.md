
Git init khởi tạo lưu trữ
Git add . thêm các file vô staging area
Git commit -m “Ghi dòng muốn mô tả”
Muôn thay đổi đoạn mô tả git commit –amend -m “gi nội dung muốn thay đổi”
Git push origin main đẩy các file lên 
Git status : xem trạng thái xem có cái nào ở on brand thì đẩy lên 
Git diff: xem các thay đổi giữa các commit với nhau

…or create a new repository on the command line
echo "# NCKH-YSC" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DAVID-NGUYEN-S16/NCKH-YSC.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/DAVID-NGUYEN-S16/NCKH-YSC.git
git branch -M main
git push -u origin main

git fetch dùng để tải nội dubng từ remote repository xuống mà không cập nhật ngay lập tức vào Local reponsitory
còn git pull thì ngược lại
git log –oneline ->> xem những thay đổi, nhật kí
git reset là cho file trở về trạng thái ban đầu
