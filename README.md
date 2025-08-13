Quy trình tổng quát
Dán nhãn ô kệ: in nhãn “Aptamil Kid 110ml” (hoặc tốt hơn: QR chứa bin_id).


Chụp/Upload ảnh mỗi ô kệ → ảnh lưu Drive, ghi log vào Sheet (image_inbox).


OCR nhãn kệ → suy ra SKU (hoặc bin_id nếu dùng QR).


YOLO đếm thùng nhìn thấy (mặt trước).


Tính tổng dựa trên kích thước thùng + kích thước kệ (lưu trong Sheet).


Ghi kết quả về Sheet → Web 3D đọc API để hiển thị heatmap/chi tiết.


