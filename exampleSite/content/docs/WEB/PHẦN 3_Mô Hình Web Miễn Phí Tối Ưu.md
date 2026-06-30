---
weight: 330
title: "PHẦN 3_Mô Hình Web Miễn Phí Tối Ưu"
draft: false
toc: true
description:
---


### Phần 1: Upload Ảnh lên file

B1: Up ảnh lên web [Postimages](https://postimages.org/) sau khi hoàn tất chọn `link Markdown`  như hình

![tai-xuong-(9).png](https://i.postimg.cc/9Q5vMB2n/tai-xuong-(9).png)

B2: Cú pháp `![mô tả ảnh](link ảnh bên trên)`



### Phần 2: Chữ IN ĐẬM và to như ảnh

![tai-xuong-(10).png](https://i.postimg.cc/Pqxss5Tt/tai-xuong-(10).png)

Cú pháp: ## thêm dấu vào trước nội dung      ##   Create New Content



### Phần 3: Hiển thị sẵn link nhấn vào như hình: 

![tai-xuong-(11).png](https://i.postimg.cc/7ZKdVr7R/tai-xuong-(11).png)

Cú pháp Markdown chuẩn : `[Nội dung hiển thị](URL_của_bạn)`

[Nội dung hiển thị]: Là đoạn văn bản mà người dùng sẽ nhìn thấy và có thể nhấp vào.

(URL_của_bạn): Là đường dẫn (link) trang web hoặc tài liệu bạn muốn trỏ tới.



Phần 4: Hiện thị ô code để COPY

![tai-xuong-(12).png](https://i.postimg.cc/L4jWW1LG/tai-xuong-(12).png)

Cú pháp: dòng đầu tiền điền ` ```shell` xuống dòng ghi nội dụng cần rồi xuống dòng kết thúc bằng 3 dấu ```

```shell
Nội dung đoạn code cần copy
```


### Phần 5: Nổi bật 1 dòng chữ 

![tai-xuong-(13).png](https://i.postimg.cc/vTXtsbQY/tai-xuong-(13).png)

Cú pháp:  ` hugo new `



### Phần 6: Ghi chú cảnh bảo in đậm

![tai-xuong-(14).png](https://i.postimg.cc/j54zHtn2/tai-xuong-(14).png)

Cú pháp: {{% alert context="info" text="**Note**: If your site already has a git repository, you can initialise your site using the path to your site's git repository e.g. `hugo mod init github.com/<user>/<my-docs-site>/`." /%}}


### Phần 7: Hiển thị Tab như hình

![tai-xuong-(15).png](https://i.postimg.cc/NF0rRTcg/tai-xuong-(15).png)

Cú pháp:

{{< tabs tabTotal="3">}}
{{% tab tabName="Tên Nội dung Tab" %}}


Your Linux distro’s package manager may include Hugo. If this is the case, install it directly using your distro’s package manager – for instance, in Ubuntu, run the following command. This will install the extended edition of Hugo:

```shell
sudo apt install hugo
```

{{% /tab %}}
{{% tab tabName="Homebrew (macOS)" %}}

If you use the package manager [Homebrew](https://brew.sh/), run the `brew install` command in your terminal to install Hugo:

```shell
brew install hugo
```

{{% /tab %}}
{{% tab tabName="Windows (Chocolatey)" %}}

If you use the package manager [Chocolatey](https://chocolatey.org/), run the `choco install` command in your terminal to install Hugo:

```shell
choco install hugo --confirm
```

{{% /tab %}}
{{< /tabs >}}



