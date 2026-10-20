MÓN QUÀ 20-10 DÀNH TẶNG EMBES PHƯƠNG CUTE (3D INTERACTIVE)

CẤU TRÚC THƯ MỤC (tất cả nằm cùng một thư mục)
- index.html          : toàn bộ trang web (HTML + CSS + JS)
- photo1.jpg ... photo8.jpg : ảnh kỷ niệm
- music.mp3           : nhạc nền (tùy chọn, thêm sau; chưa có thì nút nhạc tự ẩn)
- bouquet.png         : ảnh bó hoa riêng (tùy chọn; chưa có thì dùng bó hoa SVG vẽ sẵn)

LUỒNG MÀN HÌNH
1. Màn 1: Bó hoa hồng phát sáng -> chạm vào bó hoa.
2. Màn 2: Bó hoa gắn 6 ảnh (photo1-6) -> chạm hoặc ấn giữ bó hoa để vào không gian 3D.
3. Màn 3: Không gian 3D với câu chúc và ảnh bay lơ lửng. Kéo chuột/vuốt để xoay.
   Chạm vào câu chúc, ảnh hoặc biểu tượng phong bì ở góc trên bên phải để mở phong bì.
4. Màn 4: Phong bì thư 20/10 (con dấu "LOVE") -> chạm phong bì để mở thư.
5. Màn 5: Thư tay lời chúc, có thể cuộn nếu nội dung dài. Ảnh Polaroid nhỏ (photo8) ở góc dưới.
   Chạm vào ảnh để phóng to.
6. Màn 6: Ảnh phóng to. Bấm nút (X), phím Esc hoặc chạm ảnh để quay lại Màn 3.
   Nút (X) ở Màn 4 và Màn 5 cũng quay lại Màn 3.

TÙY CHỈNH (đầu phần <script> trong index.html)
- PHOTO_COUNT  : số lượng ảnh (photo1.jpg ... photoN.jpg).
- LETTER_PHOTO : số thứ tự ảnh dùng trong thư (hiện là 8).
- ROSES        : vị trí các ảnh gắn trên bó hoa ở Màn 2.
- MESSAGES     : danh sách câu chúc bay trong Màn 3.
- Tiêu đề trang: thẻ <title>. Nội dung thư: khối .letter-header / .letter-body ở Màn 5.

CÁCH CHẠY
- Mở index.html trực tiếp bằng trình duyệt (cần Internet để tải font chữ Google Fonts,
  nếu offline trang vẫn chạy với font mặc định).
- Nhạc chỉ phát sau lần chạm đầu tiên (quy định của trình duyệt); nút tròn ở góc trên để bật/tắt.
