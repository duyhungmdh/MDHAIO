---
weight: 330
title: "[Zero Trust]"
draft: false
toc: true
description: "[Zero Trust] Hướng dẫn cách WARP+ miễn phí"
---

B1: Truy cập one.dash.cloudflare.com và tạo 1 tài khoản Cloudflare mới (nếu có tài khoản trước đó thì đăng nhập).

B2: Ở trang bắt đầu, nhấn "Set up Zero Trust" và nhấn lựa chọn đầu tiên.

B3: Ở mục "Team name", nhập bất cứ thứ gì bạn muốn và nhấn "Next" (BẮT BUỘC PHẢI NHỚ ĐỂ ĐĂNG NHẬP) 

B4: Chọn "Free Plan" và nhập thông tin cá nhân (fake hay real thì tùy, 0đ mà :D)

B5: Sau khi qua B4, vào mục 3 sọc góc trái, nhấn "Gateway". Ở trang "Overview", nhấn "Add Device" phần "Recommendation" để thiết lập.

B6: Nhấn "Download WARP" cho thiết bị đang sử dụng và trở lại trang trước (bỏ qua nếu đang sử dụng 1.1.1.1 trên iOS/Android).

B7: Ở "Define enrollment policies", nhập email để đăng nhập vào WARP (không nhất thiết là mail của tài khoản Cloudflare đang sử dụng) (nếu muốn thiết lập thêm có thể truy cập mục 3 gạch trái màn -> Access -> Policies)

B8: Ở "Set service mode", để mặc định là "Both traffic and DNS" (chỉ thay đổi nếu biết mình đang làm gì)

B9: Ở "Set default routing" chọn "Exclude mode" (cảnh báo như trên, chỉ thay đổi nếu biết mình đang làm gì)

B10: Đoạn này để loại trừ các domain đi qua Cloudflare, nếu không muốn có thể thêm các domain đó vào đây.

B11: Sau khi hoàn thành các bước, mở 1.1.1.1 trên thiết bị cần sử dụng WARP+, nhấn nút 3 sọc trên góc phải màn, chọn "Account" -> "Login to Cloudflare Zero Trust" và nhập các thông tin bạn đã thiết lập ở B3 và B7.

B12: Nếu tất cả mọi thứ suôn sẻ (không lỗi "Device not registered", không lỗi verify code,...) thì bạn đã hoàn tất rồi đó. Bạn có thể chia sẻ/sử dụng Zero Trust trên 50 thiết bị khác nhau (nếu bạn có tâm).

Tips: trong trang chủ Cloudflare Zero Trust, bạn có thể thiết lập rất nhiều thứ, nhưng không giới hạn ở:

- Chặn/cho phép truy cập domain/trang web bất kỳ theo firewall
- Chặn/cho phép đăng nhập Zero Trust qua Cloudflare Access với nhiều phương thức xác minh
- Xem lưu lượng truy cập của từng thiết bị trong vòng 24h (bắt buộc phải cài chứng chỉ CA)
