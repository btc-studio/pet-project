# pet-project

## Rank SS

- App Menu trên IPAD dành cho các cửa hàng ăn uống, spa
  - Khách hàng order -> App quản lý sẽ nhận được order
  - Tối ưu cho marketing: khách hàng login bằng SĐT -> Liên lạc, trao đổi, xin feedback thông qua SĐT
  - Phiên bản no-IPAD: khách hàng sẽ dùng điện thoại để scan QA code dẫn đến trang web Menu
  - Cung cấp các trò chơi giải trí gacha, gắp thú... khi khách hàng tiêu tiền đến một mức độ nhất định

- Slack App lắng nghe message trên 1 channel -> parse nội dung -> gọi web hooks
  - Lắng nghe sự kiện members gửi Time off request -> thu thập nội dung gồm có employee_id, time_off... rồi gọi web hooks update vào Google sheet

## Rank F
- App tạo mã QR, khi ai đó quét mã QR thì mình sẽ nhận được thông báo qua Push Message, Slack, Messenger, Zalo, Web hook...
  - Sử dụng trong trường hợp user muốn nhận thông báo khi Hoàn thành việc Giặt là, Hoàn thành gửi Bưu phẩm
  - Người dùng nhận được thông báo mà không bị lộ thông tin liên lạc (SĐT), không mất phí gọi điện
