# BUSINESS REQUIREMENT DOCUMENT (BRD) - OTHELLO/REVERSI GAME

## 1. GIỚI THIỆU DỰ ÁN
Dự án nhằm phát triển trò chơi Othello (hay còn gọi là Reversi), một trò chơi chiến thuật trên bàn cờ 8x8 dành cho hai người chơi (Đen và Trắng).

## 2. YÊU CẦU NGHIỆP VỤ (BUSINESS REQUIREMENTS)
* **BR-01:** Hệ thống phải đảm bảo luật chơi Othello chuẩn quốc tế.
* **BR-02:** Cung cấp trải nghiệm người dùng mượt mà trên môi trường máy tính (Desktop application).
* **BR-03:** Hỗ trợ đa dạng chế độ chơi để thu hút người mới và người chơi chuyên nghiệp.

## 3. DANH SÁCH CÁC CHỨC NĂNG (FUNCTIONAL REQUIREMENTS)

### 3.1. Quản lý Trận đấu (Match Management)
* **FR-01: Chế độ 2 người chơi (Local Multiplayer):** Hai người chơi thực hiện nước đi luân phiên trên cùng một máy tính.
* **FR-02: Chế độ Đấu máy (AI Mode):** Người chơi đấu với máy với 3 cấp độ khó (Dễ, Bình thường, Khó).
* **FR-03: Gợi ý nước đi:** Hiển thị các ô hợp lệ mà người chơi có thể đặt quân (ô sáng xanh).
* **FR-04: Tính điểm:** Cập nhật thời gian thực số lượng quân Đen và Trắng trên bàn cờ.

### 3.2. Giao diện và Tương tác (UI/UX)
* **FR-05: Main Menu:** Giao diện bắt đầu với các tùy chọn: Chơi mới, Hướng dẫn, Thoát.
* **FR-06: Xem hướng dẫn (UC-07):** Hiển thị dialog HTML mô tả luật chơi và mẹo chiến thuật.
* **FR-07: Hiệu ứng hình ảnh:** Hiệu ứng lật quân cờ khi bị kẹp giữa.

### 3.3. Hệ thống Logic (Game Logic)
* **FR-08: Kiểm tra nước đi hợp lệ:** Tự động bỏ qua lượt nếu người chơi không còn nước đi hợp lệ.
* **FR-09: Xác định kết thúc:** Kết thúc khi bàn cờ đầy hoặc cả hai bên không còn nước đi. Thông báo người chiến thắng.
