# Tải xuống và nén hình ảnh từ URL

## Giới thiệu

Đây là một script Python đơn giản để tải xuống hình ảnh từ danh sách URL và nén chúng thành file zip.

## Chức năng

- Tải xuống hình ảnh từ danh sách URL.
- Hiển thị tiến trình tải xuống cho mỗi hình ảnh.
- Nén tất cả hình ảnh đã tải xuống thành file zip.
- Xóa các file ảnh sau khi nén (tương đương Shift + Delete).

## Yêu cầu

- Python 3.6 trở lên
- Thư viện `requests`, `zipfile`, `shutil`, `pathlib`

## Cách sử dụng

1. **Cài đặt các thư viện cần thiết:**

```bash
pip install requests zipfile shutil pathlib
```
1.  **Paste danh sách URL:**
    

*   Mở file download\_images.py (hoặc tên file bạn đã đặt).
    
*   Paste danh sách URL của hình ảnh vào giữa hai dấu """ trong biến urls\_string. Mỗi URL trên một dòng.
    

2.  **Chạy script:**
    

  Script sẽ tải xuống hình ảnh, nén chúng thành file anh.zip trong thư mục Anh (tạo tự động nếu chưa tồn tại), và xóa các file ảnh sau khi nén.

Lưu ý
-----

*   Script sẽ xóa vĩnh viễn các file ảnh sau khi nén (tương đương Shift + Delete). Hãy chắc chắn rằng bạn đã sao lưu các file ảnh nếu cần thiết.
    
*   Đường dẫn đến thư mục lưu trữ được đặt trong biến download\_path. Bạn có thể thay đổi đường dẫn này nếu muốn.
    
