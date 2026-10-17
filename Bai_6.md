# Bài 6 : Sự cố tài liệu dự án trên GitHub
## Phần 1. Phân tích

1. Sai lầm của Nam

-   Dùng Word để lưu tài liệu dự án: File `.docx` là Rich Text, chứa cả nội dung và định dạng nên Git khó so sánh từng dòng khi có thay đổi.
    
-   Không dùng Markdown: GitHub hiển thị trực tiếp file `.md` trên trình duyệt, giúp các thành viên đọc tài liệu dễ dàng mà không cần tải file về.
    
-   Hiểu sai về xung đột Git: File Word có cấu trúc nhị phân nên Git khó xác định chính xác phần nội dung thay đổi, dễ gây khó khăn khi xử lý Conflict.
    

2. Vì sao Markdown an toàn và nhẹ hơn?

-   Plain Text: Markdown lưu nội dung dưới dạng văn bản thuần, không chứa định dạng phức tạp như Word.
    
-   Dung lượng nhẹ: File `.md` thường nhỏ hơn file `.docx` có nhiều định dạng, hình ảnh.
    
-   Dễ so sánh: Git Diff có thể hiển thị chính xác dòng nào được thêm, sửa hoặc xóa.
    
-   Ít rủi ro khi truyền tải: Nếu mất một byte, file Markdown thường vẫn có thể đọc được phần nội dung còn lại; file Word có thể bị lỗi cấu trúc nếu dữ liệu quan trọng bị hỏng. Tuy nhiên, Markdown không đảm bảo miễn nhiễm với mất dữ liệu.
    

## Phần 2. Hoàn thiện bằng StackEdit

Bạn tạo nội dung giới thiệu dự án GreenTech trong StackEdit như sau, sau đó lưu thành `README.md`.

#  Dự án GreenTech

## 1. Giới thiệu

**GreenTech** là dự án hướng đến việc ứng dụng công nghệ để bảo vệ môi trường và phát triển nông nghiệp bền vững.

## 2. Mục tiêu

-   Tiết kiệm tài nguyên thiên nhiên.
    
-   Giảm tác động tiêu cực đến môi trường.
    
-   Ứng dụng công nghệ vào quản lý nông nghiệp.
    

## 3. Chức năng chính

Chức năng

Mô tả

Theo dõi môi trường

Thu thập dữ liệu từ cảm biến

Quản lý dữ liệu

Lưu trữ và theo dõi thông tin

Cảnh báo

Thông báo khi có chỉ số bất thường

## 4. Công nghệ sử dụng

-   IoT: Kết nối các thiết bị và cảm biến.
    
-   Markdown: Viết tài liệu dự án.
    
-   GitHub: Lưu trữ mã nguồn và cộng tác nhóm.
    

## 5. Thành viên và đóng góp

Các thành viên cùng phát triển dự án, cập nhật tài liệu và kiểm tra chức năng trước khi hoàn thành.

> GreenTech hướng đến việc kết hợp công nghệ với bảo vệ môi trường để xây dựng một nền nông nghiệp bền vững.
