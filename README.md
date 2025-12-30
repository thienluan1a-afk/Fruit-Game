🍎 FRUIT CATCH AI - HỨNG TRÁI CÂY BẰNG MŨI (AI CONTROL)
Một trò chơi arcade sáng tạo kết hợp giữa lập trình game truyền thống và trí tuệ nhân tạo. Thay vì sử dụng phím bấm, bạn sẽ sử dụng chính cử động mũi của mình trước Webcam để điều khiển rổ hứng trái cây. Dự án này minh chứng cho sức mạnh của công nghệ nhận diện khuôn mặt trong giải trí tương tác.

✨ Các tính năng chính
Điều khiển không chạm (Nose Tracking): Sử dụng thư viện MediaPipe Face Mesh để xác định tọa độ mũi theo thời gian thực, chuyển hóa chuyển động của cơ thể thành hành động trong game.

Hệ thống cấp độ (Stages) thử thách:

Màn 1 & 2 (Safe Area): Làm quen với cơ chế điều khiển, tốc độ rơi tăng dần.

Màn 3 (Foggy Area): Hiệu ứng sương mù bao phủ, chỉ một vùng nhỏ quanh rổ được hiển thị, đòi hỏi sự tập trung cao độ.

Màn 4 (Alien Fire Zone): Đối đầu với người ngoài hành tinh. Bạn phải vừa hứng trái cây, vừa né tránh những quả cầu lửa bay chéo từ các vị trí ngẫu nhiên.

Vật phẩm hỗ trợ độc đáo: ❄️ Slow Motion: Khi bắt được vật phẩm Power-up, thời gian sẽ chậm lại, giúp bạn dễ dàng xử lý các tình huống khó khăn.

Bảng xếp hạng (Leaderboard): Hệ thống tự động lưu trữ và hiển thị Top 5 điểm cao nhất mọi thời đại, giúp tăng tính cạnh tranh mỗi lần chơi.

Giao diện hiện đại: Tích hợp màn hình webcam ngay trong khung hình game với viền bo góc thẩm mỹ.

🎮 Hướng dẫn chơi
Điều khiển
Di chuyển: Di chuyển đầu sang trái/phải để mũi của bạn dẫn dắt rổ hứng trên màn hình.

Bắt đầu lại: Nhấn phím ENTER tại màn hình Game Over để bắt đầu ván mới.

Quy tắc
Hứng trái cây: Nhận điểm và tăng cấp khi đạt đủ mốc yêu cầu.

Tránh vật cản: Né tránh Bom (mất 1 mạng + trừ điểm) và Cầu lửa (mất điểm).

Kết thúc: Game kết thúc khi bạn hết 5 mạng (LIFE: 0).

📦 Cài đặt & Thiết lập
Điều kiện tiên quyết
Python 3.10 trở lên.

Thiết bị có Webcam.

Các bước cài đặt
Tải mã nguồn:

Bash

git clone https://github.com/DUTVcore/Fruit-Catch-AI.git
Cài đặt thư viện phụ thuộc:

Bash

pip install pygame opencv-python mediapipe numpy
Chạy trò chơi:

Bash

python Fruit_Game.py
🛠️ Cấu trúc dự án
Plaintext

```text Fruit-Catch-AI/ ├── Fruit_Game.py # Mã nguồn chính của trò chơi ├── highscores.txt # Tệp lưu trữ Top 5 điểm cao (tự động tạo) ├── basket.png # Rổ hứng trái cây ├── dautay.png # Trái dâu tây ├── cachua.png # Trái cà chua ├── chuoi.png # Trái chuối ├── duahau.png # Trái dưa hấu ├── khe.png # Trái khế ├── apple.png # Trái táo ├── bomb.png # Quả bom (vật cản) ├── powerup.png # Vật phẩm hỗ trợ (Slow Motion) ├── heart.png # Biểu tượng mạng sống (Life) ├── alien.png # Quái vật Alien (Màn 4) ├── alien_charge.png # Alien trong trạng thái tụ chiêu ├── fireball.png # Cầu lửa Alien bắn ra ├── background.png # Nền màn 1 (Safe Area) ├── background_dark.png # Nền màn 2 (Opportunity & Dangerous) ├── background_extreme.png # Nền màn 3 (Foggy Area) └── background_ultimate.png # Nền màn 4 (Alien Fire Zone) ```

👥 Tác giả
Dự án được phát triển với niềm đam mê công nghệ bởi:

Bùi Quang Thiên Luân (DUTVcore)
