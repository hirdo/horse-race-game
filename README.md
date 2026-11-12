# Đua Ngựa Định Mệnh 🏇

Game đua ngựa vui nhộn chạy trên trình duyệt điện thoại. Nhập tên cả nhóm, thả ngựa ra đường đua, rồi để số phận chọn ra người được chọn (về nhất hoặc về bét) để làm một nhiệm vụ cho cả nhóm.

## Cách chơi

1. Mở `index.html` bằng trình duyệt (hoặc link GitHub Pages khi đã bật).
2. Nhập 2–12 tên người chơi (dán nhiều tên cách nhau bằng dấu phẩy cũng được).
3. Chọn người được chọn là **người về nhất** hay **người về bét**, ghi nhiệm vụ hoặc chọn nhanh một gợi ý.
4. Bấm **Vào chuồng xuất phát!** và hồi hộp theo dõi.

## Có gì trong cuộc đua

- Góc nhìn toàn cảnh: camera tự thu phóng để luôn thấy cả đoàn ngựa. Nút **Toàn cảnh** (hoặc chạm vào đường đua) để xem cả đường đua từ vạch xuất phát tới đích.
- Xoay ngang điện thoại để xem rộng hơn; nút toàn màn hình hiện ra khi trình duyệt cho phép.
- Sự kiện ngẫu nhiên: tăng tốc, cà rốt thần, ngủ gật, mải đuổi bướm, chạy ngược chiều.
- Chướng ngại vật rơi xuống đường đua (hàng rào, tảng đá, vũng bùn, vỏ chuối), hay nhắm vào ngựa dẫn đầu. Hàng rào và tảng đá có thể nhảy qua, còn không thì té chúi về trước. Ngựa chỉ té khi trúng vật cản, và vật cản còn hiện thêm một lúc để thấy rõ nguyên nhân.
- Ngựa chạy sát nhau có thể lấn làn húc nhau: cả hai cùng khựng lại, con bị húc khựng lâu hơn.
- Ngựa bị bỏ xa được tăng nhẹ tốc độ nên cuộc đua luôn sát nút tới cuối.
- Bình luận viên hài hước bằng tiếng Việt, quay chậm khi hai con ngựa kề vai nhau gần đích.
- Nhạc nền điệu galop tự sáng tác. Cả trận là một bài: vào 200m cuối, giai điệu cũ được chồng thêm bass chạy, trống con, nhân đôi quãng tám, nhanh dần và dâng tông tới vạch đích. Khi quay chậm chỉ còn tiếng tim đập. Kèm hiệu ứng âm thanh và kèn chiến thắng, tất cả tổng hợp bằng Web Audio, có nút tắt.
- Bục trao giải, bảng xếp hạng có thời gian và nút sao chép kết quả để gửi vào nhóm chat.

## Kỹ thuật

Toàn bộ game nằm trong một file `index.html` (HTML + CSS + JavaScript thuần, vẽ bằng Canvas), không cần build hay cài đặt gì. Tên người chơi chỉ lưu trong trình duyệt của bạn (localStorage) và được hiển thị bằng `textContent`, không chèn HTML.
