# Đua Ngựa Định Mệnh 🏇

Game đua ngựa vui nhộn chạy trên trình duyệt điện thoại. Nhập tên cả nhóm, thả ngựa ra đường đua, rồi để số phận chọn ra người được chọn (về nhất hoặc về bét) để làm một nhiệm vụ cho cả nhóm.

## Cách chơi

1. Mở `index.html` bằng trình duyệt (hoặc link GitHub Pages khi đã bật).
2. Nhập 2–12 tên người chơi (dán nhiều tên cách nhau bằng dấu phẩy cũng được).
3. Chọn người được chọn là **người về nhất** hay **người về bét**, ghi nhiệm vụ nếu muốn.
4. Bấm **Vào chuồng xuất phát!** và hồi hộp theo dõi.

## Có gì trong cuộc đua

- Góc nhìn toàn cảnh: camera tự thu phóng để thấy cả đoàn ngựa, kèm bản đồ tiến độ phía trên.
- Sự kiện ngẫu nhiên: tăng tốc, cà rốt thần, vấp té lộn vòng, ngủ gật, mải đuổi bướm, chạy ngược chiều.
- Ngựa bị bỏ xa được tăng nhẹ tốc độ nên cuộc đua luôn sát nút tới cuối.
- Bình luận viên hài hước bằng tiếng Việt, quay chậm khi hai con ngựa kề vai nhau gần đích.
- Âm thanh tổng hợp bằng Web Audio (vó ngựa, còi xuất phát, khán giả hò reo, kèn chiến thắng), có nút tắt.
- Bục trao giải, bảng xếp hạng có thời gian và nút sao chép kết quả để gửi vào nhóm chat.

## Kỹ thuật

Toàn bộ game nằm trong một file `index.html` (HTML + CSS + JavaScript thuần, vẽ bằng Canvas), không cần build hay cài đặt gì. Tên người chơi chỉ lưu trong trình duyệt của bạn (localStorage) và được hiển thị bằng `textContent`, không chèn HTML.
