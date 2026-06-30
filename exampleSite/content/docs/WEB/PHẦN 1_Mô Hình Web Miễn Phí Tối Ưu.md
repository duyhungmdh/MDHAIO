---
weight: 330
title: "PHẦN 1_Mô Hình Web Miễn Phí Tối Ưu"
draft: false
toc: true
description:
---
```shell
- Nơi lưu trữ mã nguồn và bài viết (Miễn phí): Sử dụng GitHub.
- Công cụ tạo hình hài web (Miễn phí): Sử dụng Hugo hoặc Astro (tôi khuyên dùng Hugo vì nó cực kỳ nhẹ,
nhanh và có vô số giao diện blog đẹp).
- Nơi phát sóng web lên mạng (Miễn phí): Sử dụng Cloudflare Pages (Nơi cấp cho bạn đuôi .pages.dev).
```

# Hướng Dẫn Từng Bước (Dành Cho Người Mới)

## Bước 1: Chuẩn bị tài khoản nền tảng Bạn cần tạo tài khoản ở hai trang web sau (chỉ cần dùng email đăng ký bình thường):

+ GitHub.com: Nơi đây giống như một cái két sắt, dùng để chứa thư mục website của bạn.

+ Cloudflare.com: Nơi đây giống như cầu nối, lấy dữ liệu từ két sắt GitHub và phát lên internet.

## Bước 2: Chọn "Lớp áo" (Theme) cho web Thay vì phải tự code từ đầu, bạn có thể lấy sẵn mã nguồn đã được thiết kế sẵn.

+ Truy cập vào trang themes.gohugo.io. Ở đây có rất nhiều giao diện blog tối giản.

+ Khi chọn được theme ưng ý, họ thường sẽ có một nút link dẫn sang GitHub. Tìm nút có chữ "Fork". Nút này có tác dụng sao chép toàn bộ giao diện đó về tài khoản GitHub cá nhân của bạn.

Lưu ý: Kho chứa chuẩn bắt buộc phải nhìn thấy một tệp tin có tên là hugo.toml, hugo.yaml hoặc config.toml nằm ngay ở bên ngoài cùng

## Bước 3 Chi tiết: Kết nối GitHub và Phát sóng Website

1. Vào khu vực "Công xưởng" của Cloudflare

Đăng nhập vào trang chủ Cloudflare.

Nhìn sang cột menu màu đen bên tay trái, cuộn xuống và bấm vào mục `Workers & Pages`.

Nhìn sang màn hình rộng bên phải, tìm và bấm vào nút màu xanh dương có chữ `Create application` (Tạo ứng dụng).

![tai-xuong.png](https://i.postimg.cc/SNyd5p1J/tai-xuong.png)

2. Các bước tiếp theo

Hãy nhìn xuống dưới cùng của bảng trắng trong ảnh. Bạn sẽ thấy một dòng chữ nhỏ: `Looking to deploy Pages? Get started`.

![tai-xuong-(1).png](https://i.postimg.cc/Bv1BDZtf/tai-xuong-(1).png)

3: Bạn hãy click chuột thẳng vào chữ Get started (được in đậm và gạch chân màu đen) đó

Ngay khi bấm vào chữ Get started, màn hình sẽ chuyển sang giao diện chuẩn của Pages. Lúc này, bạn sẽ thấy một tab có chữ Pages và nút Connect to Git (Kết nối với Git) quen thuộc hiện ra.

4. Chọn nguồn nhập dữ liệu: Tại ô đầu tiên có dòng chữ Import an existing Git repository (Nhập một kho Git có sẵn), bạn hãy bấm vào nút `Get started` màu xanh ở bên phải của ô đó.

![tai-xuong-(2).png](https://i.postimg.cc/DwSrkfry/tai-xuong-(2).png)

5. Chọn kho GitHub: Màn hình tiếp theo sẽ hiện ra danh sách tài khoản GitHub của bạn. Bạn hãy tích chọn đúng kho duyhungmdh/lotusdocs và bấm nút Begin setup (Bắt đầu cài đặt).

![tai-xuong-(4).png](https://i.postimg.cc/MZmsDYbR/tai-xuong-(4).png)

6. Thiết lập thông số xây dựng web (Bước quyết định):

Project name: Đặt tên đường link web tùy ý bạn (viết liền không dấu, ví dụ: blog-lotusdocs).

Framework preset: Bấm vào và chọn đúng chữ `Hugo`.

Thêm biến môi trường: Mở rộng phần Root directory: Bạn hãy điền chính xác: `exampleSite`

![tai-xuong-(3).png](https://i.postimg.cc/B6BDcj0V/tai-xuong-(3).png)

Triển khai: Bấm nút `Save and Deploy` màu xanh ở dưới cùng.

![tai-xuong-(5).png](https://i.postimg.cc/ydLx8cBC/tai-xuong-(5).png)
