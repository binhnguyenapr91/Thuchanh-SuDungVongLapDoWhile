# Thuchanh-SuDungVongLapDoWhile
Luyện tập sử dụng vòng lặp dowhile
Mô tả
Sử dụng vòng lặp do while để viết lại chương trình yêu cầu nhập các số từ 1 -> 10 ở ví dụ trong phần vòng lặp while.

Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX
Hướng dẫn
Bước 1: Tạo file dowhilesample.html. Tạo thẻ <script> và viết các mã lệnh thực thi trong đó.

Bước 2: Tạo biến value để lưu giá trị người dùng nhập vào

let value = null;
Bước 3: Viết mã thực thi

do {
    value = prompt("Nhập vào số từ 1 -> 10");
} while (value < 1 || value > 10);
Bước 4: Hiển thị ra màn hình giá trị vừa nhập

alert("Số bạn vừa nhập là " + value);
Bước 5: Thực thi chương trình. Quan sát kết quả.
