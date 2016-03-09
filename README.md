# Font-For-Nukeviet

Tổng hợp các font chữ đẹp đã conver để dùng cho mã nguồn nukeviet

Hướng dẫn cài đặt:

Bước 1: Upload các file font chữ cần dùng lên thư mục ../theme-cua-ban/font/file.*

Bước 2: Mở File style.css trong themes/ themes-cua-ban thêm đoạn mã css sau:

@font-face {
    font-family:'ten-font';
    src:url('../../default/fonts/ten-file.eot?avyewf');
    src:url('../../default/fonts/ten-file.eot?#iefixavyewf') format('embedded-opentype'),url('../../default/fonts/ten-file.ttf?avyewf') format('truetype'),url('../../default/fonts/ten-file.woff?avyewf') format('woff'),url('../../default/fonts/ten-file.svg?avyewf#ten-file') format('svg');
    font-weight:normal;
    font-style:normal;
}

* Thay tên File = font chữ tương ứng file ví dụ Roboto-Bold
* 

Bước 3:

Thêm thuộc tính font-family: 'ten-font' ; vào class muốn áp dụng


Hỗ trợ http://tieplua.com | http://tieplua.net | http:// tieplua.org




