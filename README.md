# XrayR

Một khung phụ trợ Xray có thể dễ dàng hỗ trợ nhiều bảng.

Một khung công tác back-end dựa trên Xray, hỗ trợ các giao thức V2ay, Trojan, Shadowsocks, cực kỳ dễ mở rộng và hỗ trợ kết nối nhiều bảng điều khiển.

Nếu bạn thích dự án này, bạn có thể nhấn vào dấu sao + xem ở góc trên bên phải để theo dõi tiến độ của dự án này.

Hướng dẫn: [hướng dẫn chi tiết] (https://crackair.gitbook.io/xrayr-project/)
## Tuyên bố từ chối trách nhiệm

Dự án này chỉ mang tính chất học hỏi, phát triển và bảo trì của cá nhân tôi, tôi không đảm bảo tính khả dụng và tôi không chịu trách nhiệm về bất kỳ hậu quả nào do sử dụng phần mềm này.

## Đặc trưng
* Mã nguồn mở vĩnh viễn và miễn phí.
* Hỗ trợ nhiều giao thức V2ray, Trojan, Shadowsocks.
* Hỗ trợ các tính năng mới như Vless và XTLS.
* Hỗ trợ kết nối đơn lẻ với nhiều bảng và nút mà không cần khởi động lại.
* Hỗ trợ IP trực tuyến bị hạn chế
* Hỗ trợ mức cổng nút, giới hạn tốc độ mức người dùng.
* Cấu hình đơn giản và rõ ràng.
* Sửa đổi cấu hình để tự động khởi động lại phiên bản.
* Dễ dàng biên dịch và nâng cấp, có thể nhanh chóng cập nhật phiên bản lõi, hỗ trợ các tính năng mới của Xray-core.

## Đặc trưng

| Tính năng | v2ray | trojan | shadowsocks |
| --------------- | ----- | ------ | ------------- |
| Nhận thông tin về nút | √ | √ | √ |
| Nhận thông tin người dùng | √ | √ | √ |
| Thống kê Lưu lượng Người dùng | √ | √ | √ |
| Báo cáo Thông tin Máy chủ | √ | √ | √ |
| Tự động đăng ký chứng chỉ TLS | √ | √ | √ |
| Tự động gia hạn chứng chỉ tls | √ | √ | √ |
| Đếm người trực tuyến | √ | √ | √ |
| Giới hạn người dùng trực tuyến | √ | √ | √ |
| Quy tắc kiểm toán | √ | √ | √ |
| Giới hạn tốc độ cổng nút | √ | √ | √ |
| Giới hạn tốc độ của người dùng | √ | √ | √ |
| DNS tùy chỉnh | √ | √ | √ |

## Cài đặt phần mềm
### Một cài đặt chính
`` '
bash <(curl -Ls https://raw.githubusercontent.com/CatPort/XrayR-script/master/install.sh)
`` '