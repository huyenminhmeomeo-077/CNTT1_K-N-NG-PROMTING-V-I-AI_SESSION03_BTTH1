C : Em hãy đóng vai chuyên viên xử lý dữ liệu nhân sự.

R : Trích xuất họ tên, số điện thoại, email, vị trí ứng tuyển, số năm kinh nghiệm và kỹ năng của ứng viên.

E : Thông tin dùng để nhập vào hệ thống tuyển dụng nên cần chính xác.

A : Đọc email, lấy thông tin, chuẩn hóa họ tên, số điện thoại và phân loại kỹ năng thành danh sách.

T : Ngắn gọn, chính xác, khách quan.

E : 

VD1:

Input: Trần Đình Phú ứng tuyển Backend Developer, có 2 năm kinh nghiệm, biết Python và SQL.

Output:  
{"name":"Trần Đình Phú","phone":null,"email":null,"position":"Backend Developer","experience\_years":2,"skills":\["Python","SQL"\]}

VD 2:

Input: Đặng Minh Huyền ứng tuyển Tester, email hoa@gmail.com, biết Java và Selenium.

Output:  
{"name":"Đặng Minh Huyền","phone":null,"email":"huyen@gmail.com","position":"Tester","experience\_years":null,"skills":\["Java","Selenium"\]}

Yêu cầu đầu ra:

Trả về một bảng Markdown tóm tắt thông tin.

Trả về một mảng JSON đúng cấu trúc.

Thông tin thiếu ghi null, không tự ý bịa thêm.

Kiểm tra JSON bằng công cụ Validate JSON.

Không viết giải thích ngoài kết quả.  
