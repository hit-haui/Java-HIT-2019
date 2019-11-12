Bài tập lớn:
Cho game gồm chi tiết như sau:
========================================================
- Trò chơi: chia làm 2 phe. Một bên là người chơi (Player) một bên là quái thú (Monster). Quái thú và người chơi được đưa vào sân đấu (BattleField) để chiến đấu cho đến khi 1 trong 2 phải tử trận.
======================Player============================
- Player gồm: cung thủ (archers), hiệp sĩ (knight).
  
  (1) Cung thủ
  - Thuộc tính:
    - Máu: 200
    - MP: 150
    - Giáp: 10
  - Phương thức:
    - Bắn chay (hit): gây 30 sát thương lên mục tiêu
    - Bắn tên (aim): Mất 30 MP để sự dụng, gây 100 sát thương và giảm giáp đối phương đi 10
    - Nhận sát thương (get_dame): Nhận sát thương của đối thủ
    - Chết (dead): Máu nhỏ hơn bằng 0
    - Hiển thị thông số (show_info): Hiển thị thuộc tính

  (2) Hiệp sĩ
  - Thuộc tính:
    - Máu: 150
    - MP:100
    - Giáp: 20
  - Phương thức:
    - Chém chay (hit): gây 40 sát thương lên mục tiêu
    - Bật lá chắn (shield): Mất 50 MP để sự dụng, gây 100 sát thương và giảm giáp đối phương đi 30
    - Nhận sát thương (get_dame): Nhận sát thương của đối thủ
    - Chết (dead): Máu nhỏ hơn bằng 0
    - Hiển thị thông số (show_info): Hiển thị thuộc tính

======================Monsters============================
- Monsters gồm: Hổ

  (1) Hổ
  - Thuộc tính:
    - Máu: 500
    - Giáp: 20
  - Phương thức:
    - Thổi lửa (fire blowwing): gây 30 sát thương lên tướng 
    - Nhận sát thương (get_dame): Nhận sát thương của đối thủ
    - Chết (death): Máu nhỏ hơn bằng 0
    - Hiển thị thông số (show_info): Hiển thị thuộc tính

  ==================Thể thức=========================
  - Tạo sân đấu cho 2 đối thủ (1 Player, 1 Monster). Player sẽ lựa chọn một trong các nghề như trên. Monster thì mặc định là Hổ.
  - Chọn xem ai đánh trước.
  - Cho 2 nhân vật đánh nhau theo từng lượt với yêu cầu:
   
   (1) Hiển thị ra lượt đánh của ai
   
   (2) Lượt của kẻ nào thì sẽ hiển thị danh sách kĩ năng của kẻ đó
   
  - Nếu 1 trong 2 kẻ chết trước. Kẻ còn lại dành chiến thắng

=====================Lưu ý==========================
- Không thể sử dụng quá mana hiện có
- Lượng giáp sẽ được trừ đi khi nhận sát thương: Ví dụ như gây 20 sát thương với địch có 10 giáp => Địch bị trừ 10 máu
Một số hình ảnh minh họa trò chơi.
![image](https://user-images.githubusercontent.com/52252046/68590059-348b5580-04c0-11ea-872e-fdfc2981ac50.png)
![image](https://user-images.githubusercontent.com/52252046/68590203-8a5ffd80-04c0-11ea-91cb-74d1e3d8b081.png)
