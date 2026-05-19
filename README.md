# SOURCE CODE - REVERSI / OTHELLO

## UC07 - Hướng dẫn chơi
File:
- `HowToPlayDialog.java`

Chức năng:
- Hiển thị hướng dẫn chơi Othello/Reversi
- Luật chơi
- Chế độ chơi
- Mẹo chơi

---

## UC09 - Chơi với AI và chơi lại game
Files:
- `ReversiController.java`
- `ReversiAI.java`

Các hàm chính:

### Trong `ReversiController.java`
- `aiMove()`  
  → Điều khiển AI thực hiện nước đi

- `GameOver()`  
  → Xử lý kết thúc game và chức năng:
  - Chơi lại
  - Về Menu
  - Thoát game

- `configure()`  
  → Thiết lập chế độ chơi với AI

### Trong `ReversiAI.java`
- `findBestMove()`  
  → Tìm nước đi tốt nhất cho AI

- `minimax()`  
  → Thuật toán Minimax + Alpha Beta Pruning

- `heuristic()`  
  → Đánh giá trạng thái bàn cờ
