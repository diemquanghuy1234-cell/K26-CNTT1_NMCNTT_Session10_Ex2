# Báo cáo phân tích (I/O)
**Input**: Các câu lệnh cấu hình hệ thống,các tài liệu hướng dẫn cài đặt hệ thống cảm biến độ ẩm cho trang trại Lan,văn bản giải thích và câu lệnh gõ vào terminal
**Output**:File Markdown,ứng dụng chính xác inline code,block code hỗ trợ màu sắc,code python điều khiển máy bơm,bảng so sánh 2 loại cảm biến
# Source code
```python 
import time

def kiem_tra(do am):
       if do_am < 70:
          print(" bật máy bơm")
          return True
          Return False 

kiem_tra(65)
```
## So sánh cảm biến
| Tiêu chí | Cũ | Mới | 
| :--- | :--- | :--- |
| **Sai số** | +-5% RH | +-2% RH |
|**Độ bền** | Thấp | Cao |


