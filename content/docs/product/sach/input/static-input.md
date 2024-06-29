---
bookFlatSection: true
weight: 10
type: docs
title: Đơn Giá Và Hằng Số
url: /sach/static-input
---

# Đơn Giá Và Hằng Số In Sách

Những tham số dưới đây là các đơn giá hoặc hằng số. Khác với tham số bình thường, chúng có thể được thiết lập để sử dụng cho nhiều đơn khác nhau, giữa nhiều phương thức gia công khác nhau khi in Sách.

## Đơn giá nguyên vật liệu
**Giá thành nguyên vật liệu khác nhau**

- **Đơn giá giấy**
  * *Đơn giá giấy là giá bán của một tấn giấy in ấn. Giá này thay đổi tùy theo loại giấy, định lượng (khối lượng giấy trên một đơn vị diện tích), thương hiệu, nhà cung cấp và thời điểm mua.*
  * *Đơn vị*: VNĐ/Tấn
  * *Mã*: MAPPAP
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}M_{paper}{{< /katex >}}
- **Đơn giá bản in**
  * *Đơn giá bản in (impression)*
  * *Đơn vị*: VNĐ/CM²
  * *Mã*: MAPIMP
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}M_{imp}{{< /katex >}}
- **Đơn giá mực**
  * *Đơn giá mực (Tính theo VNĐ/KG)*
  * *Đơn vị*: VNĐ/KG
  * *Mã*: MAPINK
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}M_{ink}{{< /katex >}}
- **Đơn giá màng bìa**
  * *Đơn giá màng bìa (film)*
  * *Đơn vị*: VNĐ/cm²
  * *Mã*: MAPFLM
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}M_{film}{{< /katex >}}
## Đơn giá công sản xuất
**Giá thành cho từng hoạt động sản xuất**

- **Đơn giá in - 1000 lượt đầu**
  * *Đơn giá in ấn trong 1000 lượt đầu tiên*
  * *Đơn vị*: VNĐ/1000 lượt
  * *Mã*: SHRTMNLD
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}0_{in1000}{{< /katex >}}
- **Đơn giá in - 1000 lượt sau**
  * *Đơn giá in ấn sau 1000 lượt đầu tiên*
  * *Đơn vị*: VNĐ/lượt
  * *Mã*: SHRTMNLS
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}0_{after1000}{{< /katex >}}
- **Đơn giá gia công sách**
  * *Đơn giá gia công sách cho mỗi trang*
  * *Đơn vị*: VNĐ/trang
  * *Mã*: SHRGCS
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}0_{manufacture}{{< /katex >}}
- **Đơn giá chế bản**
  * *Đơn giá chế bản sách*
  * *Đơn vị*: VNĐ/trang
  * *Mã*: SHRCB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}0_{engraving}{{< /katex >}}
## Hằng số khác
**Những hằng số mặc định khác**

- **Hệ số bù hao**
  * *Hệ số bù hao (waste factor) trong in ấn, hay còn gọi là tỷ lệ hao hụt, là một con số được sử dụng để dự đoán lượng giấy in bị hao hụt trong quá trình sản xuất. Con số này thể hiện tỷ lệ phần trăm giấy in bị lãng phí do các yếu tố như sai sót in ấn, cắt xén, chỉnh sửa, hoặc do bản thân giấy in bị lỗi.*
  * *Đơn vị*: Đơn vị
  * *Mã*: SHRBH
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}
- **Khoảng cách chừa nhíp**
  * *Khoảng cách chừa nhíp (Gripper margin) là khoảng cách giữa mép ngoài của nội dung in ấn và mép cắt của tờ giấy. Khoảng cách này đảm bảo rằng nội dung in ấn không bị cắt mất khi xén thành phẩm.*
  * *Đơn vị*: cm
  * *Mã*: SHRKCN
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}O_{gripper}{{< /katex >}}
- **Khoảng cách chừa xén**
  * *Khoảng cách chừa xén (Trim margin) là khoảng cách giữa mép ngoài của nội dung in ấn và mép gấp của tờ giấy. Khoảng cách này đảm bảo rằng nội dung in ấn không bị che khuất khi gấp thành phẩm.*
  * *Đơn vị*: cm
  * *Mã*: SHRKCX
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}O_{trim}{{< /katex >}}
- **Khoảng cách thang màu**
  * *Khoảng cách thang màu (Color bar margin) là khoảng cách giữa các mảng màu trong một bản in. Khoảng cách này đảm bảo rằng các mảng màu không bị dính vào nhau khi in ấn.*
  * *Đơn vị*: cm
  * *Mã*: SHRKTM
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}O_{colorbar}{{< /katex >}}
- **Khoảng cách chừa tay kê**
  * *Khoảng cách chừa tay kê là khoảng cách tối thiểu giữa mép giấy và vị trí tay kê khi đặt giấy vào máy in*
  * *Đơn vị*: cm
  * *Mã*: SHRCTK
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}0_{hand}{{< /katex >}}


