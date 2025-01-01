HƯỚNG DẪN CÀI ĐẶT PROJECT

Project được thực hiện bằng ngôn ngữ Python và được chạy trên Visual Studio Code. Để chạy được chương trình này cần phải có thêm thư viện hỗ trợ Pygame. Đây là thư viện hỗ trợ rất nhiều cho dự án và đặc biệt tạo giao diện cho người chơi tương tác với với Game.
1. Cài đặt Visual Studio Code: https://code.visualstudio.com/ 
 ![image](https://github.com/user-attachments/assets/d7af7cd8-2684-4bca-9747-6a6e0cb26119)

2. Cài đặt Python: https://www.python.org/downloads/

Trong quá trình cài đặt, hãy chọn tùy chọn “Add Python to PATH” để thêm Python vào biến môi trường.
![image](https://github.com/user-attachments/assets/7cf4d649-d9ba-4d60-9a0e-3741503bcedf)

3. Cài đặt Python Extension trong VS Code
![image](https://github.com/user-attachments/assets/d693a4a1-daca-4352-a9b5-486589eb9e07)

4. Cài đặt thư viện Pygame:

Pygame có thể được cài đặt dễ dàng bằng công cụ quản lý gói pip trong Python. Bạn chỉ cần mở terminal (hoặc Command Prompt trên Windows) và chạy lệnh “pip install pygame” 
 
5. Thực hiện Project: 

Khi tải project về, ta sẽ tiền hành giải nén project
![image](https://github.com/user-attachments/assets/f4bcaeb4-dea1-49dd-9d50-aee5bcad5498)

Sau đó mở Visual Studio Code, tại File -> Open Folder -> Chọn Folder Breakout-main -> Select Folder
 ![image](https://github.com/user-attachments/assets/14d0044d-0722-4c74-b144-d863e0fd74de)

Sau khi mở folder, ta tìm đến file main.py và tiến hành chạy chương trình
 ![image](https://github.com/user-attachments/assets/33521431-d75c-4d21-bfc8-2bccd765e4ab)

Chạy project trên CMD: Win + R -> CMD

Ví dụ: Project được lưu ở ổ đĩa D, thư mục Python
![image](https://github.com/user-attachments/assets/8d51568e-a23f-428b-8957-8483fdbabb29)

7. Mô tả cách chơi:

![image](https://github.com/user-attachments/assets/86e7a674-649f-49c7-94f1-1e181abfab3b)

  BreakOut là một trò chơi điện tử cổ điển thuộc thể loại game đập gạch. Người chơi bắt đầu game bằng cách nhấn Space để khiến quả bóng di chuyển. Quả bóng sẽ liên tục di chuyển và va đập vào các viên gạch nằm phía trên. Trong lúc đó, người chơi cần phải điều khiển một thanh ngang (paddle) bằng 2 phím mũi tên trái và phải di chuyển ngang dưới màn hình để đỡ bóng. Mục tiêu của trò chơi là dùng quả bóng để phá vỡ hết các viên gạch mà không để bóng rơi ra khỏi màn hình. Mỗi khi bóng đập vào viên gạch, sẽ gây ra sát thương lên các viên gạch đó và người chơi nhận thêm điểm, khi gây đủ sát thương thì viên gạch sẽ biến mất. Người chơi cũng có thể sử dụng các vật phẩm nâng cấp được rơi ra khi phá các khối, những vật phẩm này sẽ hỗ trợ người chơi có thể chơi game một cách nhanh hơn, thú vị hơn. Trong game có tổng cộng 4 vật phẩm nâng cấp, giúp tăng tốc độ, tăng kích thước, tăng sinh mạng(tối đa 3) và cung cấp khả năng bắn đạn vào các viên gạch (bắn đạn bằng cách nhấn Space).

  Người chơi phải khéo léo di chuyển thanh trượt để đỡ quả bóng, không để bóng rơi ra ngoài. Nếu người chơi để bóng rơi, họ sẽ mất một mạng. Cứ mỗi 30s trôi qua, tốc độ của quả bóng sẽ tăng lên 10% làm tăng độ khó của trò chơi, đòi hỏi người chơi cần phải tích lũy đủ vật phẩm nâng cấp trước khi độ khó tăng lên. Trò chơi tiếp tục cho đến khi tất cả các viên gạch bị phá hủy hoặc người chơi mất hết mạng. Khi kết thúc, trò chơi sẽ lưu lại điểm cao và hiện ra màn hình chơi lại hoặc thoát. BreakOut là trò chơi kết hợp giữa kỹ năng phản xạ và chiến lược trong việc lựa chọn góc đập bóng để phá vỡ nhiều gạch nhất có thể.
