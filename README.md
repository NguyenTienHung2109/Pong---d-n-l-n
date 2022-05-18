I. Hướng dẫn cài đặt:
- Cài các file cpp, header và folder assets chứa các file wav, mp3 vào trong cùng 1 folder lớn.
- Tải và cài đặt thêm các phần sdl sau để chương trình hoạt động:
+ SDL2.dll
+ SDL2_mixer.dll
+ SDL2_ttf.dll
+ SDL2_image.dll

II. Mô tả trò chơi
- Link youtube mô tả trò chơi:
- Trò chơi tên là PONG, là trò chơi bóng bàn 2D dùng thanh chắn để không cho bóng lọt qua nền trái hoặc phải của màn hình. Nếu để bóng lọt qua, đối phương sẽ ghi được điểm.
- Người dành được 5 điểm trước sẽ là người chiến thắng
- Khi đối phương dành được 4 điểm, thanh chắn của người chơi sẽ chuyển sang màu vàng và gia tăng kích thước để dễ dàng che chắn quả bóng hơn, đồng thời màu quả bóng sẽ được chuyển sang màu đỏ. Khi người chơi dành được 4 điểm thì điều tương tự sẽ xảy ra.
- Game được cài chế độ chơi 1 người và 2 người, thêm vào đó là 1 màn hình menu và chức năng pause game.
- Các kĩ thuật được sử dụng trong phần code: con trỏ, đồ hoạ và âm thanh SDL, string,...
- Kết luận: Theo em, Pong có thể được coi là một trò chơi hoàn chỉnh, tuy còn sơ sài và có thể cải thiện ở một số mặt như cài đặt thêm phông nền hay hiệu ứng animation khi dành chiến thắng. Nếu có thể phát triển thêm, em muốn thêm 1 vài tính năng như nhặt item để điều chỉnh tốc độ di chuyển của quả bóng hay khả năng di chuyển của thanh chắn. 
- Điều tâm đắc nhất với em sau khi hoàn thành dự án lớn lần này là cách quản lý code/file trong 1 project sao cho ngăn nắp, hợp lý và khoa học. Tuy lúc khởi đầu em có những sự bối rối nhất định, em dần học được cách tạo khung cho trò chơi rồi thêm vào những tính năng mới, qua đó cải thiện nhiều về tư duy lẫn khả năng viết code của bản thân. 
