**Bài 1 : Khởi tạo cấu trúc dự án bằng Terminal** 

**Phần 1: Phân tích lỗi** Chỉ ra ít nhất 3 lỗi sai trong chuỗi lệnh của Nam và giải thích thông báo lỗi của Terminal dựa trên kiến thức đã học.

\+Lỗi 1: Do đặt tên thư mục có khoảng trắng nhưng không đặt trong dấu ngoặc kép  
\+Lỗi 2: bạn muốn thêm 1 cấp thư mục mới thì dùng lệnh cd nhưng bạn lại không để trong dấu ngoặc kép phải đặt tên thư mục trong dấu ngoặc kép để PowerShell hiểu đúng đường dẫn.  
\+Lỗi 3: Tạo thư mục nhưng src chưa tồn tại

**Phần 2: Hoàn thiện** Viết lại chuỗi câu lệnh PowerShell chuẩn để Nam có thể hoàn thành cấu trúc thư mục trên trong đúng 3 dòng lệnh.

PS C:\\Users\\Student\> mkdir Shoppe\_Projects  
PS C:\\Users\\Student\> cd “Shoppe\_Projects”  
PS C:\\Users\\Student\\Shoppe\_Projects\> mkdir src  
