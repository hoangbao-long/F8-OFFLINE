# Cấu trúc URL

Scheme + domain + ext:port/path?querystring#fargment

## Thảo luận: Phân biệt đường dẫn tương đối và tuyệt đối

1. Khái niệm đường dẫn tương đối (Relative Path) - tuyệt đối (Absolute Path)
   Tuyệt đối: Không phụ thuộc vào vị trí nó đang đứng ( Có nghĩa là nó sẽ trả về cùng một kết quả)
   Tương đối: Phụ thuộc vào vị trí nó đang đứng
2. Phân biệt các loại đường dẫn sau
   a. /duong-dan (tuyệt đối)
   b. duong-dan (tương đối)
   c. ../duong-dan (tương đối)
   d. http://tenmien/duong-dan (tương đối)
   e. //tenmien/duong-dan (tuyệt đối)
   f. tenmien/duong-dan (tương đối)
