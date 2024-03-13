---
bookFlatSection: true
weight: 1
type: docs
title: Tham Số Tĩnh
---

# Tham Số Tĩnh Cho In Sách

Những tham số dưới đây có thể được thiết lập để sử dụng cho nhiều đơn khác nhau, giữa nhiều phương thức gia công khác nhau khi in Sách.

## Đơn giá nguyên vật liệu
**Giá thành nguyên vật liệu khác nhau**

- **Đơn giá giấy**
  * *Đơn giá giấy là giá bán của một tấn giấy in ấn. Giá này thay đổi tùy theo loại giấy, định lượng (khối lượng giấy trên một đơn vị diện tích), thương hiệu, nhà cung cấp và thời điểm mua.*
  * *Đơn vị*: VNĐ/Tấn
  * *Mã*: MAPPAP
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}M_{paper}{{< /katex >}}

## Đơn giá công sản xuất
**Giá thành cho từng hoạt động sản xuất**

- **Chế bản**
  * *Chế bản là công đoạn tạo ra khuôn in từ bản thiết kế. Khuôn in này được sử dụng để in ấn số lượng lớn. Đơn giá công chế bản là giá tiền cho mỗi cm² diện tích khuôn in*
  * *Đơn vị*: VNĐ/cm²
  * *Mã*: PRPCB
  * *Kí hiệu*: {{< katex >}}\mathcal{S}\mathscr{i}P_{prepress}{{< /katex >}}

## Thông số khác
**Những thông số mặc định khác**

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



