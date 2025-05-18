# 🎮 Hướng Dẫn Cài Đặt & Chơi Game BreakOut

---

## ⚙️ Giới thiệu

Project được viết bằng **Python** và chạy trên **Visual Studio Code**.  
Game sử dụng thư viện **Pygame** để tạo giao diện và xử lý tương tác với người chơi.

---

## 🛠️ Cài đặt môi trường

### 1. Cài đặt Visual Studio Code  
Tải và cài đặt VS Code từ trang chính thức:  
[https://code.visualstudio.com/](https://code.visualstudio.com/)  
![VS Code](https://github.com/user-attachments/assets/d7af7cd8-2684-4bca-9747-6a6e0cb26119)

---

### 2. Cài đặt Python  
Tải Python tại:  
[https://www.python.org/downloads/](https://www.python.org/downloads/)  

**Lưu ý:** Trong quá trình cài đặt, nhớ tích chọn **Add Python to PATH** để thêm Python vào biến môi trường.  
![Add Python to PATH](https://github.com/user-attachments/assets/7cf4d649-d9ba-4d60-9a0e-3741503bcedf)

---

### 3. Cài đặt Python Extension trong VS Code  
Mở VS Code, tìm và cài đặt extension **Python** của Microsoft.  
![Python Extension](https://github.com/user-attachments/assets/d693a4a1-daca-4352-a9b5-486589eb9e07)

---

### 4. Cài đặt thư viện Pygame  
Mở terminal hoặc Command Prompt và chạy lệnh:  **pip install pygame**

---

### 5. Hướng dẫn thực hiện Project

### Bước 1: Tải và giải nén project

Tải project về máy và giải nén file ZIP.

![Giải nén project](https://github.com/user-attachments/assets/f4bcaeb4-dea1-49dd-9d50-aee5bcad5498)

---

### Bước 2: Mở project bằng Visual Studio Code

- Mở Visual Studio Code
- Chọn **File → Open Folder**
- Chọn thư mục `Breakout-main` rồi bấm **Select Folder**

![Mở folder trong VS Code](https://github.com/user-attachments/assets/14d0044d-0722-4c74-b144-d863e0fd74de)

---

### Bước 3: Chạy chương trình

- Tìm file `main.py` trong thư mục project.
- Chạy file này bằng cách nhấn **Run** hoặc mở terminal và chạy câu lệnh: **python main.py**

### Bước 4: Chạy project trên CMD

- Ví dụ Project được lưu ở ổ đĩa D, thư mục Python : `D:\Python\Breakout-main`
![image](https://github.com/user-attachments/assets/8d51568e-a23f-428b-8957-8483fdbabb29)

### 🎮 6. Mô tả cách chơi

![Gameplay BreakOut](https://github.com/user-attachments/assets/86e7a674-649f-49c7-94f1-1e181abfab3b)

BreakOut là trò chơi điện tử cổ điển thuộc thể loại **game đập gạch**.

- Người chơi bắt đầu bằng cách nhấn **Space** để quả bóng di chuyển.
- Quả bóng sẽ liên tục va đập vào các viên gạch phía trên màn hình.
- Người chơi điều khiển một thanh ngang (paddle) bằng 2 phím **Mũi tên trái** và **Mũi tên phải** để đỡ bóng, di chuyển ngang dưới màn hình.
- **Mục tiêu** là phá vỡ hết các viên gạch bằng quả bóng mà không để bóng rơi ra khỏi màn hình.

### Cơ chế chơi chi tiết:

- Mỗi khi bóng đập vào viên gạch, viên gạch sẽ bị gây sát thương, người chơi nhận điểm.
- Khi viên gạch nhận đủ sát thương, nó sẽ biến mất.
- Trong quá trình chơi, người chơi có thể nhận được **4 loại vật phẩm nâng cấp** rơi ra khi phá gạch, bao gồm:
  - Tăng tốc độ bóng
  - Tăng kích thước paddle
  - Tăng số mạng (tối đa 3 mạng)
  - Cho phép bắn đạn phá gạch (bắn bằng phím **Space**)

- Người chơi cần khéo léo điều khiển thanh paddle để không cho bóng rơi ra ngoài. Nếu để bóng rơi, người chơi sẽ mất một mạng.
- Mỗi 30 giây, tốc độ bóng sẽ tăng thêm 10%, làm tăng độ khó của trò chơi.
- Người chơi phải tích lũy đủ vật phẩm nâng cấp trước khi độ khó tăng lên.

### Kết thúc trò chơi:

- Trò chơi kết thúc khi:
  - Tất cả viên gạch bị phá hủy, hoặc
  - Người chơi mất hết mạng.
- Điểm cao nhất sẽ được lưu lại.
- Màn hình kết thúc sẽ cho phép người chơi chọn **chơi lại** hoặc **thoát**.

---

> 📚 Dự án cuối kỳ môn lập trình Python mang tính học thuật, tham khảo đối với sinh viên.
