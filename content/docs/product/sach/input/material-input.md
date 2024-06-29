---
bookFlatSection: true
weight: 20
type: docs
title: Tham Số Nguyên Vật Liệu
url: /sach/material-input
---

# Tham Số Nguyên Vật Liệu Cho In Sách

Dưới đây là những tham số liên quan tới thiết lập nguyên vật liệu mà cần người dùng cần nhập để tạo đơn in Sách.

## Thông tin đầu vào chung
**Thông tin đầu vào được sử dụng bởi tất cả hình thức gia công**

- **Chiều dài khổ thành phẩm**
  * *Chiều dài của sách sau khi hoàn thiện, đo từ mép trên xuống mép dưới*
  * *Đơn vị*: cm
  * *Mã*: MATKTPL
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}

- **Chiều rộng khổ thành phẩm**
  * *Chiều rộng của sách sau khi hoàn thiện, đo từ mép trái sang mép phải.*
  * *Đơn vị*: cm
  * *Mã*: MATKTPW
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}

- **Số lượng sản phẩm**
  * *Số lượng sách cần được in ra*
  * *Đơn vị*: Bản
  * *Mã*: MATCC
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}

## Thông tin đầu vào bìa
**Thông tin đầu vào chỉ liên quan tới bìa**

- **Số trang bìa mỗi cuốn sách**
  * *Số lượng trang in bìa sách, như bìa trước, bìa sau và lót bìa*
  * *Đơn vị*: Trang
  * *Mã*: MATSPB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}

- **Định lượng giấy bìa**
  * *Trọng lượng của 1 mét vuông giấy in bìa, thể hiện độ dày mỏng của giấy.*
  * *Đơn vị*: g/m²
  * *Mã*: MATDLB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{cover}{{< /katex >}}

- **Số màu in bia**
  * *Số màu để in bìa sách*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATNCLB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}

- **Số mặt in bìa**
  * *Số mặt in bìa*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATNSDB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}
  * *Tập giá trị*: •  1  	•  2  	
## Thông tin đầu vào ruột
**Thông tin đầu vào liên quan tới ruột**

- **Số trang ruột mỗi cuốn sách**
  * *Số lượng trang in nội dung bên trong sách, không bao gồm bìa trước, bìa sau và các trang phụ như gáy sách, lăn tay, lót bìa*
  * *Đơn vị*: Trang
  * *Mã*: MATSPR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}

- **Định lượng giấy ruột**
  * *Trọng lượng của 1 mét vuông giấy in, thể hiện độ dày mỏng của giấy.*
  * *Đơn vị*: g/m²
  * *Mã*: MATDLR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{content}{{< /katex >}}

- **Số màu in ruột**
  * *Số màu để in ruột sách*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATNCLR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Ncl_{content}{{< /katex >}}

- **Số mặt in ruột**
  * *Số mặt in ruột*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATNSDR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}
  * *Tập giá trị*: •  1  	•  2  	
## Thông tin đầu vào thiết lập máy in
**Thông tin đầu vào liên quan tới thiết lập máy in**

- **Kiểu bình - Bìa**
  * *Số trang bìa được sắp xếp và in ấn trên một tờ giấy in lớn trước khi cắt thành các trang sách riêng lẻ*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATKBB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}}
  * *Tập giá trị*: •  2  	•  4  	•  8  	•  16  	•  32  	
- **Kiểu bình - Ruột**
  * *Số trang ruột được sắp xếp và in ấn trên một tờ giấy in lớn trước khi cắt thành các trang sách riêng lẻ*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATKBR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}
  * *Tập giá trị*: •  2  	•  4  	•  8  	•  16  	•  32  	
- **Khổ máy in bìa - dài**
  * *Chiều dài khổ máy in bìa hỗ trợ*
  * *Đơn vị*: cm
  * *Mã*: MATKMILCOV
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{length}{{< /katex >}}

- **Khổ máy in bia - rộng**
  * *Chiều rộng khổ máy in bìa hỗ trợ*
  * *Đơn vị*: cm
  * *Mã*: MATKMIWCOV
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{width}{{< /katex >}}

- **Khổ máy in ruột - dài**
  * *Chiều dài khổ máy in ruột hỗ trợ*
  * *Đơn vị*: cm
  * *Mã*: MATKMILCON
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{length}{{< /katex >}}

- **Khổ máy in ruột - rộng**
  * *Chiều rộng khổ máy in ruột hỗ trợ*
  * *Đơn vị*: cm
  * *Mã*: MATKMIWCON
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{width}{{< /katex >}}

## Thông tin đầu vào khác
**Thông tin đầu vào khác**

- **Tỉ lệ chữ/ảnh trong file in**
  * *Tỉ lệ số trang chữ / số trang ảnh. Ví dụ có 30 trang chữ và 3 trang ảnh thì tỉ lệ này sẽ là 10.*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATTLC
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}TI{{< /katex >}}



