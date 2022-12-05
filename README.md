# XrayR
[![](https://img.shields.io/badge/TgChat-@XrayR讨论-blue.svg)](https://t.me/XrayR_project)
[![](https://img.shields.io/badge/Channel-@XrayR通知-blue.svg)](https://t.me/XrayR_channel)
![](https://img.shields.io/github/stars/XrayR-project/XrayR)
![](https://img.shields.io/github/forks/XrayR-project/XrayR)
![](github.com/harryngne/XrayR-Hinet/actions/workflows/release.yml/badge.svg)
![](github.com/harryngne/XrayR-Hinet/actions/workflows/docker.yml/badge.svg)
[![Github All Releases](https://img.shields.io/github/downloads/XrayR-project/XrayR/total.svg)]()

A Xray backend framework that can easily support many panels.

Back-end dựa trên Xray, hỗ trợ các giao thức V2ay, Trojan, Shadowsocks, cực kỳ dễ dàng mở rộng và hỗ trợ kết nối nhiều bảng điều khiển.

Nếu bạn thích dự án này, bạn có thể bấm vào dấu sao + xem ở góc trên bên phải để tiếp tục theo dõi tiến độ của dự án này.

## Tuyên bố từ chối trách nhiệm

Dự án này chỉ mang tính chất học hỏi, phát triển và bảo trì của cá nhân tôi, tôi không đảm bảo tính khả dụng và tôi không chịu trách nhiệm về bất kỳ hậu quả nào do sử dụng phần mềm này.
## Đặc điểm
* Mã nguồn mở vĩnh viễn và miễn phí.
* Hỗ trợ nhiều giao thức V2ray, Trojan, Shadowsocks.
* Hỗ trợ các tính năng mới như Vless và XTLS.
* Hỗ trợ kết nối đơn lẻ với nhiều bảng và nút mà không cần khởi động lại.
* Hỗ trợ IP trực tuyến bị hạn chế
* Hỗ trợ mức cổng nút, giới hạn tốc độ mức người dùng.
* Cấu hình đơn giản và rõ ràng.
* Sửa đổi cấu hình để tự động khởi động lại phiên bản.
* Dễ dàng biên dịch và nâng cấp, có thể nhanh chóng cập nhật phiên bản lõi, hỗ trợ các tính năng mới của Xray-core.

## Đặc điểm hỗ trợ

| Chức năng           | v2ray | trojan | shadowsocks |
| --------------- | ----- | ------ | ----------- |
| Nhận thông tin về node    | √     | √      | √           |
| Báo người dùng online    | √     | √      | √           |
| Thống kê lưu lượng người dùng    | √     | √      | √           |
| Báo cáo thông tin máy chủ  | √     | √      | √           |
| Tự động đăng ký chứng chỉ TLS | √     | √      | √           |
| Tự động gia hạn chứng chỉ tls | √     | √      | √           |
| Số người dùng trực tuyến    | √     | √      | √           |
| Hạn chế Người dùng Trực tuyến    | √     | √      | √           |
| Quy tắc bộ lọc        | √     | √      | √           |
| Giới hạn tốc độ cổng node    | √     | √      | √           |
| Giới hạn tốc độ bởi người dùng    | √     | √      | √           |
| DNS tùy chỉnh       | √     | √      | √           |
## Hỗ trợ panel VPN

| Support                                                  | v2ray | trojan | shadowsocks                    |
| ------------------------------------------------------ | ----- | ------ | ------------------------------ |
| sspanel-uim                                            | √     | √      | √ (单端口多用户和V2ray-Plugin) |
| v2board                                                | √     | √      | √                              |
| [PMPanel](https://github.com/ByteInternetHK/PMPanel)   | √     | √      | √                              |
| [ProxyPanel](https://github.com/ProxyPanel/ProxyPanel) | √     | √      | √                              |
| [WHMCS (V2RaySocks)](https://v2raysocks.doxtex.com/)   | √     | √      | √                              |

## Cài đặt phần mềm
### Một cài đặt chính
```
wget -N https://raw.githubusercontent.com/harryngne/XrayR-script/master/install.sh && bash install.sh
```


## Cảm ơn

* [Project X](https://github.com/XTLS/)
* [V2Fly](https://github.com/v2fly)
* [VNet-V2ray](https://github.com/ProxyPanel/VNet-V2ray)
* [Air-Universe](https://github.com/crossfw/Air-Universe)

## Licence

[Mozilla Public License Version 2.0](github.com/harryngne/XrayR-Hinet/blob/master/LICENSE)



