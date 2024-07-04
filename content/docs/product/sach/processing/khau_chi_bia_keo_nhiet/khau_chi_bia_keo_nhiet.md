---
weight: 1
type: docs
title: Công Thức
url: /sach/khau_chi_bia_keo_nhiet
---

# Khâu chỉ bìa keo nhiệt

1. Giới thiệu:

Khâu chỉ bìa keo nhiệt là phương pháp gia công sách phổ biến, sử dụng keo nhiệt để gắn bìa sách vào phần ruột đã được khâu chỉ. Phương pháp này mang đến độ bền cao, thẩm mỹ tốt và phù hợp cho nhiều loại sách khác nhau.

2. Quy trình gia công:

    In ấn: Bìa sách và ruột sách được in ấn riêng biệt theo yêu cầu.
    Khâu chỉ: Ruột sách được xếp chồng và khâu gáy bằng chỉ.
    Bôi keo: Keo nhiệt được bôi lên gáy sách đã được khâu.
    Đóng bìa: Bìa sách được gắn vào gáy sách bằng keo nhiệt.
    Cắt và hoàn thiện: Sách được cắt thành phẩm theo kích thước mong muốn và hoàn thiện các công đoạn sau cùng.

3. Ưu điểm:

    Độ bền cao: Khâu chỉ giúp tăng độ bền cho gáy sách, keo nhiệt bám dính tốt, tạo sự liên kết chắc chắn giữa bìa và ruột.
    Thẩm mỹ: Bìa sách được gắn phẳng phiu, đẹp mắt, mang lại sự chuyên nghiệp cho sản phẩm.
    Phù hợp nhiều loại sách: Phương pháp này có thể áp dụng cho nhiều loại sách khác nhau như sách giáo khoa, sách tham khảo, tiểu thuyết, v.v.
    Tiết kiệm chi phí: So với các phương pháp đóng sách khác, khâu chỉ bìa keo nhiệt có chi phí hợp lý hơn.

4. Nhược điểm:

    Thời gian gia công: Quá trình gia công có thể lâu hơn so với một số phương pháp khác.
    Khó chỉnh sửa: Sau khi hoàn thiện, việc chỉnh sửa nội dung sách là rất khó khăn.


# Thông Tin Tính Toán

## Tính Toán
### Tính Toán Nguyên Vật Liệu
- **Tổng số trang sách**
  * *Tổng số trang sách, gồm số trang bìa và số trang ruột*
  * *Đơn vị*: Trang
  * *Mã*: MATSNP
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover} + \mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}: Số trang bìa mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>

  {{< /details >}}
- **Độ dày gáy sách**
  * *Chiều dài của gáy sách*
  * *Đơn vị*: cm
  * *Mã*: MATGS
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Bk_{length}{{< /katex >}}
  * *Công thức* :{{< katex >}}(\mathcal{M}\mathscr{i}{\Sigma}pg_{content} * \mathcal{M}\mathscr{i}{\Rho}pp_{content} * 10^-4) / 2{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{content}{{< /katex >}}: Định lượng giấy ruột (g/m²)<br>

  {{< /details >}}
- **Khổ tờ in ruột - Chiều dài**
  * *Chiều dài của tờ gấy để in ruột sách*
  * *Đơn vị*: cm
  * *Mã*: MATKIRD
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}SR_{length}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}} thuộc [•  4  	•  16  	]: {{< katex >}}\lceil{ (\mathcal{M}\mathscr{i}Sz_{width} * \mathcal{M}\mathscr{i}Imp_{content}) / 4 + (\sqrt{\mathcal{M}\mathscr{i}Imp_{content}} * \mathcal{S}\mathscr{i}O_{trim}) }\rceil{{< /katex >}}
	* Ngoài ra: {{< katex >}}\lceil{\sqrt{\mathcal{M}\mathscr{i}Imp_{content}/2} * (\mathcal{M}\mathscr{i}Sz_{length} + 2 * \mathcal{S}\mathscr{i}O_{trim})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{trim}{{< /katex >}}: Khoảng cách chừa xén (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>

  {{< /details >}}
- **Khổ tờ in ruột - Chiều rộng**
  * *Chiều rộng của tờ gấy để in ruột sách*
  * *Đơn vị*: cm
  * *Mã*: MATKIRR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}SR_{width}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}} thuộc [•  4  	•  16  	]: {{< katex >}}\lceil{ \sqrt{\mathcal{M}\mathscr{i}Imp_{content}} * (\mathcal{M}\mathscr{i}Sz_{length}/2  + \mathcal{S}\mathscr{i}O_{trim}) + \mathcal{S}\mathscr{i}O_{gripper} + \mathcal{S}\mathscr{i}O_{colorbar} }\rceil{{< /katex >}}
	* Ngoài ra: {{< katex >}}\lceil{\sqrt{\mathcal{M}\mathscr{i}Imp_{content}/2} * (\mathcal{M}\mathscr{i}Sz_{width} + \mathcal{S}\mathscr{i}O_{trim}) + \mathcal{S}\mathscr{i}O_{gripper} + \mathcal{S}\mathscr{i}O_{colorbar}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{trim}{{< /katex >}}: Khoảng cách chừa xén (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{gripper}{{< /katex >}}: Khoảng cách chừa nhíp (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{colorbar}{{< /katex >}}: Khoảng cách thang màu (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>

  {{< /details >}}
- **Khổ tờ in bìa - Chiều dài**
  * *Chiều dài của tờ giấy để in bìa sách*
  * *Đơn vị*: cm
  * *Mã*: MATKIBD
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}SB_{length}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}} thuộc [•  4  	•  16  	]: {{< katex >}}\lceil{ \sqrt{\mathcal{M}\mathscr{i}Imp_{cover}} * (\mathcal{M}\mathscr{c}Bk_{length}/2 + \mathcal{S}\mathscr{i}O_{trim}) + (\mathcal{M}\mathscr{i}Sz_{width} * \mathcal{M}\mathscr{i}Imp_{cover}) / 4 }\rceil{{< /katex >}}
	* Ngoài ra: {{< katex >}}\lceil{\sqrt{\mathcal{M}\mathscr{i}Imp_{cover}/2} * (\mathcal{M}\mathscr{i}Sz_{length} + 2* \mathcal{S}\mathscr{i}O_{trim})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}}: Kiểu bình - Bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{trim}{{< /katex >}}: Khoảng cách chừa xén (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Bk_{length}{{< /katex >}}: Độ dày gáy sách (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>

  {{< /details >}}
- **Khổ tờ in bìa - Chiều rộng**
  * *Chiều rộng của tờ giấy để in bìa sách*
  * *Đơn vị*: cm
  * *Mã*: MATKIBR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}SB_{width}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}} thuộc [•  4  	•  16  	]: {{< katex >}}\lceil{ \sqrt{\mathcal{M}\mathscr{i}Imp_{cover}} * (\mathcal{M}\mathscr{i}Sz_{length}/2  + \mathcal{S}\mathscr{i}O_{trim}) + \mathcal{S}\mathscr{i}O_{gripper} + \mathcal{S}\mathscr{i}O_{colorbar} }\rceil{{< /katex >}}
	* Ngoài ra: {{< katex >}}\lceil{\sqrt{\mathcal{M}\mathscr{i}Imp_{cover}/2} * (\mathcal{M}\mathscr{i}Sz_{width} + \mathcal{M}\mathscr{c}Bk_{length}/2 * \mathcal{S}\mathscr{i}O_{trim}) + \mathcal{S}\mathscr{i}O_{gripper} + \mathcal{S}\mathscr{i}O_{colorbar}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}}: Kiểu bình - Bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Bk_{length}{{< /katex >}}: Độ dày gáy sách (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{trim}{{< /katex >}}: Khoảng cách chừa xén (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{gripper}{{< /katex >}}: Khoảng cách chừa nhíp (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{colorbar}{{< /katex >}}: Khoảng cách thang màu (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>

  {{< /details >}}
- **Số lượng bản in ruột**
  * *Số lượng bản in (print copy) thực tế cho phần nội dung bên trong của sản phẩm in, bao gồm tất cả các trang bên trong, không bao gồm bìa.*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATPCR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/\mathcal{M}\mathscr{i}Imp_{content} * \mathcal{M}\mathscr{i}Ncl_{content} * \mathcal{M}\mathscr{i}Nsd_{content}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{content}{{< /katex >}}: Số màu in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>

  {{< /details >}}
- **Số lượng bản in bìa**
  * *Số lượng bản in (print copy) thực tế cho phần bìa của sản phẩm in.*
  * *Đơn vị*: Đơn vị
  * *Mã*: MATPCB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover} * \mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}: Số màu in bia (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}: Số mặt in bìa (Đơn vị)<br>

  {{< /details >}}
- **Khối lượng giấy in bìa**
  * *Công thức tính khối lượng giấy in bìa*
  * *Đơn vị*: Tấn
  * *Mã*: MATPWB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PW{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover} * \mathcal{M}\mathscr{c}SB_{length} * \mathcal{M}\mathscr{c}SB_{width} *MATDLB * 0.0000000001{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}: Số trang bìa mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{c}SB_{length}{{< /katex >}}: Khổ tờ in bìa - Chiều dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}SB_{width}{{< /katex >}}: Khổ tờ in bìa - Chiều rộng (cm)<br>

  {{< /details >}}
- **Khối lượng giấy in ruột**
  * *Công thức tính khối lượng giấy in ruột*
  * *Đơn vị*: Tấn
  * *Mã*: MATPWR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PW{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content} * \mathcal{M}\mathscr{c}SR_{length} * \mathcal{M}\mathscr{c}SR_{width} *\mathcal{M}\mathscr{i}{\Rho}pp_{content} * 0.0000000001{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{c}SR_{length}{{< /katex >}}: Khổ tờ in ruột - Chiều dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}SR_{width}{{< /katex >}}: Khổ tờ in ruột - Chiều rộng (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{content}{{< /katex >}}: Định lượng giấy ruột (g/m²)<br>

  {{< /details >}}
- **Định lượng mực in ruột**
  * *Lượng mực in (tính bằng kg) cần thiết để in 1 triệu trang in với độ phủ mực tiêu chuẩn (thường là 5%)*
  * *Đơn vị*: kg/1 triệu trang
  * *Mã*: MATIQR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}IQ{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}round(-0.02 * (\mathcal{M}\mathscr{i}Ncl_{content} * \mathcal{M}\mathscr{i}Ncl_{content}) + 2.3 * \mathcal{M}\mathscr{i}Ncl_{content} +3){{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{content}{{< /katex >}}: Số màu in ruột (Đơn vị)<br>

  {{< /details >}}
- **Định lượng mực in bìa**
  * *Lượng mực in (tính bằng kg) cần thiết để in 1 triệu trang bìa in với độ phủ mực tiêu chuẩn (thường là 5%)*
  * *Đơn vị*: kg/1 triệu trang
  * *Mã*: MATIQB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}IQ{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}round(-0.02 * (\mathcal{M}\mathscr{i}Ncl_{cover} * \mathcal{M}\mathscr{i}Ncl_{cover}) + 2.3 * \mathcal{M}\mathscr{i}Ncl_{cover} +3){{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}: Số màu in bia (Đơn vị)<br>

  {{< /details >}}
- **Khối lượng mực in bìa**
  * *Khối lượng mực in trang bìa (tính bằng kg) tính theo trang in tiêu chuẩn (13 x 19 cm)*
  * *Đơn vị*: kg
  * *Mã*: MATIWB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}IW{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}{\Sigma}pg_{cover} * \mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * \mathcal{M}\mathscr{i}Sz_{length} * \mathcal{M}\mathscr{i}Sz_{width} * \mathcal{M}\mathscr{c}IQ{content} * \mathcal{M}\mathscr{i}Nsd_{cover}) / (13 * 19 * 2 * 10 ^ 6)}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}: Số trang bìa mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}IQ{content}{{< /katex >}}: Định lượng mực in bìa (kg/1 triệu trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}: Số mặt in bìa (Đơn vị)<br>

  {{< /details >}}
- **Khối lượng mực in ruột**
  * *Khối lượng mực in trang ruột (tính bằng kg) tính theo trang in tiêu chuẩn (13 x 19 cm)*
  * *Đơn vị*: kg
  * *Mã*: MATIWR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}IW{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}{\Sigma}pg_{content} * \mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * \mathcal{M}\mathscr{i}Sz_{length} * \mathcal{M}\mathscr{i}Sz_{width} * \mathcal{M}\mathscr{c}IQ{cover} * \mathcal{M}\mathscr{i}Nsd_{content}) / (13 * 19 * 2 * 10 ^ 6)}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{length}{{< /katex >}}: Chiều dài khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Sz_{width}{{< /katex >}}: Chiều rộng khổ thành phẩm (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}IQ{cover}{{< /katex >}}: Định lượng mực in ruột (kg/1 triệu trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>

  {{< /details >}}
- **Số lượng tờ in bìa**
  * *Công thức tính số lượng tờ in bìa*
  * *Đơn vị*: tờ
  * *Mã*: MATPNB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PN{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}C_{copies} * (\mathcal{M}\mathscr{i}{\Sigma}pg_{cover} / \mathcal{M}\mathscr{i}Imp_{cover}) * \mathcal{S}\mathscr{i}O_{wf} }\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}: Số trang bìa mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}}: Kiểu bình - Bìa (Đơn vị)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>

  {{< /details >}}
- **Số lượng tờ in ruột**
  * *Công thức tính số lượng tờ in ruột*
  * *Đơn vị*: tờ
  * *Mã*: MATPNR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}PN{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}C_{copies} * (\mathcal{M}\mathscr{i}{\Sigma}pg_{content} / \mathcal{M}\mathscr{i}Imp_{content}) * \mathcal{S}\mathscr{i}O_{wf} }\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>

  {{< /details >}}
- **Hệ số kiểu bình bìa**
  * *Hệ số kiểu bình bìa*
  * *Đơn vị*: đơn vị
  * *Mã*: MATHSKBB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}round((\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}/\mathcal{M}\mathscr{i}Imp_{cover} - floor(\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}/\mathcal{M}\mathscr{i}Imp_{cover})) * 1000){{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{cover}{{< /katex >}}: Số trang bìa mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{cover}{{< /katex >}}: Kiểu bình - Bìa (Đơn vị)<br>

  {{< /details >}}
- **Hệ số pha cắt bìa**
  * *Hệ số pha cắt bìa*
  * *Đơn vị*: đơn vị
  * *Mã*: MATHSPCB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}knife_phase_mod{cover}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  500  	]: {{< katex >}}1{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  250  	]: {{< katex >}}3{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  125  	]: {{< katex >}}7{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  750  	]: {{< katex >}}1 + 3{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  625  	]: {{< katex >}}1 + 7{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  375  	]: {{< katex >}}3 + 7{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}} bằng [•  875  	]: {{< katex >}}1 + 3 + 7{{< /katex >}}
	* Ngoài ra: {{< katex >}}5{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}imp_mod{cover}{{< /katex >}}: Hệ số kiểu bình bìa (đơn vị)<br>

  {{< /details >}}
- **Hệ số kiểu bình ruột**
  * *Hệ số kiểu bình bìa*
  * *Đơn vị*: đơn vị
  * *Mã*: MATHSKBR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}round((\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/\mathcal{M}\mathscr{i}Imp_{content} - floor(\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/\mathcal{M}\mathscr{i}Imp_{content})) * 1000){{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>

  {{< /details >}}
- **Hệ số pha cắt ruột**
  * *Hệ số pha cắt ruột*
  * *Đơn vị*: đơn vị
  * *Mã*: MATHSPCR
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}knife_phase_mod{content}{{< /katex >}}
  * *Công thức* :
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  500  	]: {{< katex >}}1 * 0.5{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  250  	]: {{< katex >}}3 * 0.25{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  125  	]: {{< katex >}}7 * 0.125{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  750  	]: {{< katex >}}1 * 0.5 + 3 * 0.25{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  625  	]: {{< katex >}}1 * 0.5 + 7 * 0.125{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  375  	]: {{< katex >}}3 * 0.25 + 7 * 0.125{{< /katex >}}
	* Nếu {{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}} bằng [•  875  	]: {{< katex >}}1 * 0.5 + 3 * 0.25 + 7 * 0.125{{< /katex >}}
	* Ngoài ra: {{< katex >}}0.5{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}imp_mod{content}{{< /katex >}}: Hệ số kiểu bình ruột (đơn vị)<br>

  {{< /details >}}
- **Khổ màng bìa**
  * *Công thức tính khổ màng bìa*
  * *Đơn vị*: cm
  * *Mã*: MATMBW
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Fl{width}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{c}SB_{width} - \mathcal{M}\mathscr{i}0_{hand} - \mathcal{S}\mathscr{i}O_{colorbar} + 0.4{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}SB_{width}{{< /katex >}}: Khổ tờ in bìa - Chiều rộng (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{hand}{{< /katex >}}: Khoảng cách chừa tay kê (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{colorbar}{{< /katex >}}: Khoảng cách thang màu (cm)<br>

  {{< /details >}}
- **Độ dài màng bìa**
  * *Công thức tính độ dài màng bìa*
  * *Đơn vị*: m
  * *Mã*: MATMBL
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Fl{length}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{c}SB_{length} * \mathcal{M}\mathscr{c}PN{cover} * 0.01{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}SB_{length}{{< /katex >}}: Khổ tờ in bìa - Chiều dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PN{cover}{{< /katex >}}: Số lượng tờ in bìa (tờ)<br>

  {{< /details >}}
- **Diện tích màng bìa**
  * *Công thức tính tổng diện tích sử dụng màng bìa*
  * *Đơn vị*: cm²
  * *Mã*: MATDTMB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Fl{length}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{c}Fl{width} * \mathcal{M}\mathscr{c}Fl{length} * 10 ^ 2{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Fl{width}{{< /katex >}}: Khổ màng bìa (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Fl{length}{{< /katex >}}: Độ dài màng bìa (m)<br>

  {{< /details >}}
- **Chi phí giấy**
  * *Công thức tính chi phí giấy*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCG
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{paper}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PW{cover} + \mathcal{M}\mathscr{c}PW{content}) * \mathcal{S}\mathscr{i}M_{paper} }\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PW{cover}{{< /katex >}}: Khối lượng giấy in bìa (Tấn)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PW{content}{{< /katex >}}: Khối lượng giấy in ruột (Tấn)<br>
{{< katex >}}\mathcal{S}\mathscr{i}M_{paper}{{< /katex >}}: Đơn giá giấy (VNĐ/Tấn)<br>

  {{< /details >}}
- **Chi phí bản in**
  * *Công thức tính chi phí bản in*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCBI
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{impression}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PC_{cover} * \mathcal{M}\mathscr{c}PrterCov_{length} * \mathcal{M}\mathscr{c}PrterCov_{width} + \mathcal{M}\mathscr{c}PC_{content} * \mathcal{M}\mathscr{c}PrterCon_{length} * \mathcal{M}\mathscr{c}PrterCon_{width}) * \mathcal{S}\mathscr{i}M_{imp} }\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}: Số lượng bản in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{length}{{< /katex >}}: Khổ máy in bìa - dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{width}{{< /katex >}}: Khổ máy in bia - rộng (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}: Số lượng bản in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{length}{{< /katex >}}: Khổ máy in ruột - dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{width}{{< /katex >}}: Khổ máy in ruột - rộng (cm)<br>
{{< katex >}}\mathcal{S}\mathscr{i}M_{imp}{{< /katex >}}: Đơn giá bản in (VNĐ/CM²)<br>

  {{< /details >}}
- **Chi phí mực in**
  * *Công thức tính chi phí mực in*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCMI
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{ink}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PC_{cover} * \mathcal{M}\mathscr{c}IW{cover} + \mathcal{M}\mathscr{c}PC_{content} * \mathcal{M}\mathscr{c}IW{content}) * \mathcal{S}\mathscr{i}M_{ink}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}: Số lượng bản in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}IW{cover}{{< /katex >}}: Khối lượng mực in bìa (kg)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}: Số lượng bản in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}IW{content}{{< /katex >}}: Khối lượng mực in ruột (kg)<br>
{{< katex >}}\mathcal{S}\mathscr{i}M_{ink}{{< /katex >}}: Đơn giá mực (VNĐ/KG)<br>

  {{< /details >}}
- **Chi phí màng bìa**
  * *Công thức tính chi phí màng bìa*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCMB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{film}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{c}Fl{length} * \mathcal{S}\mathscr{i}M_{film}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Fl{length}{{< /katex >}}: Diện tích màng bìa (cm²)<br>
{{< katex >}}\mathcal{S}\mathscr{i}M_{film}{{< /katex >}}: Đơn giá màng bìa (VNĐ/cm²)<br>

  {{< /details >}}
- **Chi phí nguyên vật liệu**
  * *Công thức tính chi phí nguyên vật liệu*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCVL
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{material}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{c}Prc{paper} + \mathcal{M}\mathscr{c}Prc{impression} + \mathcal{M}\mathscr{c}Prc{ink} + \mathcal{M}\mathscr{c}Prc{film} }\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Prc{paper}{{< /katex >}}: Chi phí giấy (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{impression}{{< /katex >}}: Chi phí bản in (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{ink}{{< /katex >}}: Chi phí mực in (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{film}{{< /katex >}}: Chi phí màng bìa (VNĐ)<br>

  {{< /details >}}
- **Chi phí chế bản**
  * *Công thức tính chi phí chế bản*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCCB
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{engraving}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}0_{engraving} * (\mathcal{M}\mathscr{c}PC_{cover} * \mathcal{M}\mathscr{c}PrterCov_{length} * \mathcal{M}\mathscr{c}PrterCov_{width} + \mathcal{M}\mathscr{c}PC_{content} * \mathcal{M}\mathscr{c}PrterCon_{length} * \mathcal{M}\mathscr{c}PrterCon_{width})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}0_{engraving}{{< /katex >}}: Đơn giá chế bản (VNĐ/trang)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}: Số lượng bản in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{length}{{< /katex >}}: Khổ máy in bìa - dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCov_{width}{{< /katex >}}: Khổ máy in bia - rộng (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}: Số lượng bản in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{length}{{< /katex >}}: Khổ máy in ruột - dài (cm)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PrterCon_{width}{{< /katex >}}: Khổ máy in ruột - rộng (cm)<br>

  {{< /details >}}
- **Chi phí in bìa sách**
  * *Công thức tính chi phí in bìa sách*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCBS
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover} * \mathcal{M}\mathscr{i}0_{in1000} + (\mathcal{M}\mathscr{c}PN{cover} - 1000) * \mathcal{M}\mathscr{i}0_{after1000} * \mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}: Số lượng bản in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{in1000}{{< /katex >}}: Đơn giá in - 1000 lượt đầu (VNĐ/1000 lượt)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PN{cover}{{< /katex >}}: Số lượng tờ in bìa (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{after1000}{{< /katex >}}: Đơn giá in - 1000 lượt sau (VNĐ/lượt)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}: Số màu in bia (Đơn vị)<br>

  {{< /details >}}
- **Chi phí in ruột sách**
  * *Công thức tính chi phí in ruột sách*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCRS
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{M}\mathscr{c}PC_{content} * \mathcal{M}\mathscr{i}0_{in1000} + (\mathcal{M}\mathscr{c}PN{content} - \mathcal{M}\mathscr{c}PC_{content} * 1000) * \mathcal{M}\mathscr{i}0_{after1000} * \mathcal{M}\mathscr{i}Ncl_{content} * \mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}: Số lượng bản in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{in1000}{{< /katex >}}: Đơn giá in - 1000 lượt đầu (VNĐ/1000 lượt)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PN{content}{{< /katex >}}: Số lượng tờ in ruột (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{after1000}{{< /katex >}}: Đơn giá in - 1000 lượt sau (VNĐ/lượt)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{content}{{< /katex >}}: Số màu in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>

  {{< /details >}}
- **Chi phí gia công**
  * *Công thức tính chi phí gia công*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCGC
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{manufacture}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}{\Sigma}pg_{content} * \mathcal{M}\mathscr{i}C_{copies} * \mathcal{M}\mathscr{i}0_{manufacture}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{M}\mathscr{i}0_{manufacture}{{< /katex >}}: Đơn giá gia công sách (VNĐ/trang)<br>

  {{< /details >}}
- **Chi phí sản xuất**
  * *Công thức tính tổng chi phí sản xuất*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCSX
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{production}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{c}Prc{engraving} + \mathcal{M}\mathscr{c}Prc{cover} + \mathcal{M}\mathscr{c}Prc{content} + \mathcal{M}\mathscr{c}Prc{manufacture}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Prc{engraving}{{< /katex >}}: Chi phí chế bản (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{cover}{{< /katex >}}: Chi phí in bìa sách (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{content}{{< /katex >}}: Chi phí in ruột sách (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{manufacture}{{< /katex >}}: Chi phí gia công (VNĐ)<br>

  {{< /details >}}
- **Chi phí đơn hàng**
  * *Công thức tính tổng chi phí đơn hàng*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRCDH
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{order}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{c}Prc{material} + \mathcal{M}\mathscr{c}Prc{production}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Prc{material}{{< /katex >}}: Chi phí nguyên vật liệu (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Prc{production}{{< /katex >}}: Chi phí sản xuất (VNĐ)<br>

  {{< /details >}}
- **Đơn giá một sản phẩm**
  * *Đơn giá trung bình cho một sản phẩm*
  * *Đơn vị*: VNĐ
  * *Mã*: MATPRSIN
  * *Kí hiệu*: {{< katex >}}\mathcal{M}\mathscr{c}Prc{single}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{c}Prc{order} / \mathcal{M}\mathscr{i}C_{copies}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}Prc{order}{{< /katex >}}: Chi phí đơn hàng (VNĐ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>

  {{< /details >}}
### Tính Toán Thời Gian
- **Thời gian soát lỗi, kiểm tra file chữ**
  * *Thời gian soát lỗi, kiểm tra file chữ*
  * *Đơn vị*: Phút
  * *Mã*: CHRKTT
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}Ktr_{txt}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}{\Sigma}pg * (\mathcal{M}\mathscr{i}TI/(\mathcal{M}\mathscr{i}TI + 1)) / \mathcal{C}\mathscr{i}Det_{txt} * \mathcal{C}\mathscr{i}No_{txt}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg{{< /katex >}}: Tổng số trang sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}TI{{< /katex >}}: Tỉ lệ chữ/ảnh trong file in (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{txt}{{< /katex >}}: Năng lực soát lỗi, kiểm tra file chữ (Trang/Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}No_{txt}{{< /katex >}}: Nhân lực soát lỗi, kiểm tra file chữ (Người|Thiết bị)<br>

  {{< /details >}}
- **Thời gian xử lý ảnh, kiểm tra file ảnh**
  * *Thời gian xử lý ảnh, kiểm tra file ảnh*
  * *Đơn vị*: Phút
  * *Mã*: CHRKTI
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}Ktr_{img}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}{\Sigma}pg * (1/(\mathcal{M}\mathscr{i}TI+1)) / \mathcal{C}\mathscr{i}Det_{img} * \mathcal{C}\mathscr{i}No_{img}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg{{< /katex >}}: Tổng số trang sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}TI{{< /katex >}}: Tỉ lệ chữ/ảnh trong file in (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{img}{{< /katex >}}: Năng lực xử lý ảnh, kiểm tra file ảnh (Trang/Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}No_{img}{{< /katex >}}: Nhân lực xử lý ảnh, kiểm tra file ảnh (Người|Thiết bị)<br>

  {{< /details >}}
- **Thời gian dàn trang**
  * *Thời gian dàn trang (layout)*
  * *Đơn vị*: Phút
  * *Mã*: CHRTDT
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}T_{layout}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{M}\mathscr{i}{\Sigma}pg * \mathcal{C}\mathscr{i}Det_{layout}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg{{< /katex >}}: Tổng số trang sách (Trang)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{layout}{{< /katex >}}: Năng lực xử lý dàn trang (Phút/Trang)<br>

  {{< /details >}}
- **Thời gian bình bản**
  * *Thời gian bình bản (Makeready)*
  * *Đơn vị*: Phút
  * *Mã*: CHRTBB
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}Makeready{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{i}Det_{makeready}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Det_{makeready}{{< /katex >}}: Định mức thời gian bình bản (Phút)<br>

  {{< /details >}}
- **Thời gian in thử**
  * *Thời gian in thử*
  * *Đơn vị*: Phút
  * *Mã*: CHRTIT
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}test_print{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(((\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/\mathcal{M}\mathscr{i}Imp_{content})*\mathcal{M}\mathscr{i}Nsd_{content} + \mathcal{M}\mathscr{i}Nsd_{cover}))/\mathcal{C}\mathscr{i}Det_{vtpr} + \mathcal{C}\mathscr{i}Det_{cbtpr}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}: Số mặt in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{vtpr}{{< /katex >}}: Tốc độ in thử (Tờ/Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{cbtpr}{{< /katex >}}: Thời gian chuẩn bị in thử (Phút)<br>

  {{< /details >}}
- **Thời gian RIP**
  * *Thời gian RIP (Raster Image Processor).*
  * *Đơn vị*: Phút
  * *Mã*: CHRTRIP
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}rip{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(((\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/\mathcal{M}\mathscr{i}Imp_{content})*\mathcal{M}\mathscr{i}Nsd_{content} + \mathcal{M}\mathscr{i}Nsd_{cover})) * \mathcal{C}\mathscr{i}Det_{rip}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}: Số mặt in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{rip}{{< /katex >}}: Tốc độ RIP (Mặt/Phút)<br>

  {{< /details >}}
- **Thời gian ghi hiện bản**
  * *Thời gian ghi hiện bản (Platemaking).*
  * *Đơn vị*: Phút
  * *Mã*: CHRTPLM
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pp}platemaking{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PC_{cover} + \mathcal{M}\mathscr{c}PC_{content}) * \mathcal{C}\mathscr{i}Det_{platemaking}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PC_{cover}{{< /katex >}}: Số lượng bản in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{c}PC_{content}{{< /katex >}}: Số lượng bản in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{platemaking}{{< /katex >}}: Tốc độ ghi hiện bản (Phút/Bản)<br>

  {{< /details >}}
- **Thời gian chế bản khác**
  * *Thời gian chế bản khác.*
  * *Đơn vị*: Phút
  * *Mã*: CHRDOTHR
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Other_{preprocessing}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{i}Other_{PreprocessingInput}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Other_{PreprocessingInput}{{< /katex >}}: Thời gian chế bản khác (Phút)<br>

  {{< /details >}}
- **Tổng thời gian chế bản**
  * *Toàn bộ thời gian chế bản*
  * *Đơn vị*: Phút
  * *Mã*: CHRSMPP
  * *Kí hiệu*: {{< katex >}}\mathcal{C}{\Sigma}PPR{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{pp}Ktr_{txt} + \mathcal{C}\mathscr{pp}Ktr_{img} + \mathcal{C}\mathscr{pp}T_{layout} + \mathcal{C}\mathscr{pp}Makeready + \mathcal{C}\mathscr{pp}test_print + \mathcal{C}\mathscr{pp}rip + \mathcal{C}\mathscr{pp}platemaking + \mathcal{C}\mathscr{i}Other_{preprocessing}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{pp}Ktr_{txt}{{< /katex >}}: Thời gian soát lỗi, kiểm tra file chữ (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}Ktr_{img}{{< /katex >}}: Thời gian xử lý ảnh, kiểm tra file ảnh (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}T_{layout}{{< /katex >}}: Thời gian dàn trang (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}Makeready{{< /katex >}}: Thời gian bình bản (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}test_print{{< /katex >}}: Thời gian in thử (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}rip{{< /katex >}}: Thời gian RIP (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pp}platemaking{{< /katex >}}: Thời gian ghi hiện bản (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Other_{preprocessing}{{< /katex >}}: Thời gian chế bản khác (Phút)<br>

  {{< /details >}}
- **Thời gian in bìa**
  * *Thời gian in bìa trong quá trình sản xuất*
  * *Đơn vị*: Phút
  * *Mã*: CHRPRCOV
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pr}P_{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PN{cover} * \lceil{ \mathcal{M}\mathscr{i}Ncl_{cover} / \mathcal{M}\mathscr{i}PrterCov_{unit}}\rceil * (\mathcal{M}\mathscr{i}Nsd_{cover} / \mathcal{M}\mathscr{i}PrterCov_{speed}) * 60/ \mathcal{M}\mathscr{i}PrterCov_{side})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PN{cover}{{< /katex >}}: Số lượng tờ in bìa (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{cover}{{< /katex >}}: Số màu in bia (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCov_{unit}{{< /katex >}}: Số màu máy in bìa hỗ trợ (Màu)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{cover}{{< /katex >}}: Số mặt in bìa (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCov_{speed}{{< /katex >}}: Tốc độ máy in bìa (Tờ/Giờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCov_{side}{{< /katex >}}: Số mặt máy in bìa hỗ trợ (Mặt)<br>

  {{< /details >}}
- **Thời gian in ruột**
  * *Thời gian in ruột trong quá trình sản xuất*
  * *Đơn vị*: Phút
  * *Mã*: CHRPRCON
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{pr}P_{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PN{content} * \lceil{ \mathcal{M}\mathscr{i}Ncl_{content} / \mathcal{M}\mathscr{i}PrterCon_{unit}}\rceil * (\mathcal{M}\mathscr{i}Nsd_{content} / \mathcal{M}\mathscr{i}PrterCon_{speed}) * 60/ \mathcal{M}\mathscr{i}PrterCon_{side})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PN{content}{{< /katex >}}: Số lượng tờ in ruột (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Ncl_{content}{{< /katex >}}: Số màu in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCon_{unit}{{< /katex >}}: Số màu máy in ruột hỗ trợ (Màu)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Nsd_{content}{{< /katex >}}: Số mặt in ruột (Đơn vị)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCon_{speed}{{< /katex >}}: Tốc độ máy in ruột (Tờ/Giờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}PrterCon_{side}{{< /katex >}}: Số mặt máy in ruột hỗ trợ (Mặt)<br>

  {{< /details >}}
- **Thời gian in khác**
  * *Thời gian in khác.*
  * *Đơn vị*: Phút
  * *Mã*: CHRPROTHR
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Other_{printing}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{i}Other_{PrintingInput}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Other_{PrintingInput}{{< /katex >}}: Thời gian in khác (Phút)<br>

  {{< /details >}}
- **Tổng thời gian in**
  * *Toàn bộ thời gian in*
  * *Đơn vị*: Phút
  * *Mã*: CHRSMPR
  * *Kí hiệu*: {{< katex >}}\mathcal{C}{\Sigma}PRT{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{pr}P_{cover} + \mathcal{C}\mathscr{pr}P_{content} + \mathcal{C}\mathscr{i}Other_{printing}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{pr}P_{cover}{{< /katex >}}: Thời gian in bìa (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{pr}P_{content}{{< /katex >}}: Thời gian in ruột (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Other_{printing}{{< /katex >}}: Thời gian in khác (Phút)<br>

  {{< /details >}}
- **Thời gian cán màng**
  * *Công thức tính thời gian cán màng*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGCM
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Lamination{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\mathcal{C}\mathscr{i}Det_{machinepreparation} + (\mathcal{M}\mathscr{c}Fl{length} / \mathcal{C}\mathscr{i}Det_{processing})}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Det_{machinepreparation}{{< /katex >}}: Thời gian chuẩn bị máy cán màng (Phút)<br>
{{< katex >}}\mathcal{M}\mathscr{c}Fl{length}{{< /katex >}}: Độ dài màng bìa (m)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{processing}{{< /katex >}}: Tốc độ cán màng (m/Phút)<br>

  {{< /details >}}
- **Thời gian pha cắt bìa**
  * *Công thức tính thời gian pha cắt bìa*
  * *Đơn vị*: Phút
  * *Mã*: CHRKFPB
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}KnifePhase_{cover}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\lceil{(\mathcal{M}\mathscr{c}PN{cover} * \mathcal{M}\mathscr{i}{\Rho}pp_{cover} * 10^-4)/\mathcal{C}\mathscr{i}DetPackHeight_{cover}}\rceil * \mathcal{C}\mathscr{i}DetKnifePhase_{cover} * \mathcal{M}\mathscr{c}knife_phase_mod{cover}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PN{cover}{{< /katex >}}: Số lượng tờ in bìa (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{cover}{{< /katex >}}: Định lượng giấy bìa (g/m²)<br>
{{< katex >}}\mathcal{C}\mathscr{i}DetPackHeight_{cover}{{< /katex >}}: Chiều cao tối đa của chồng cắt - bìa (CM)<br>
{{< katex >}}\mathcal{C}\mathscr{i}DetKnifePhase_{cover}{{< /katex >}}: Tốc độ chuẩn bị và cắt một nhát thực tế - bìa (Chồng/Phút)<br>
{{< katex >}}\mathcal{M}\mathscr{c}knife_phase_mod{cover}{{< /katex >}}: Hệ số pha cắt bìa (đơn vị)<br>

  {{< /details >}}
- **Thời gian pha cắt ruột**
  * *Công thức tính thời gian pha cắt ruột*
  * *Đơn vị*: Phút
  * *Mã*: CHRKFPR
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}KnifePhase_{content}{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{c}PN{content} * \mathcal{M}\mathscr{i}{\Rho}pp_{content}  * \mathcal{C}\mathscr{i}DetKnifePhase_{content} * \mathcal{M}\mathscr{c}knife_phase_mod{content} * 10^-4)/\mathcal{C}\mathscr{i}DetPackHeight_{content}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PN{content}{{< /katex >}}: Số lượng tờ in ruột (tờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Rho}pp_{content}{{< /katex >}}: Định lượng giấy ruột (g/m²)<br>
{{< katex >}}\mathcal{C}\mathscr{i}DetKnifePhase_{content}{{< /katex >}}: Tốc độ chuẩn bị và cắt một nhát thực tế - ruột (Chồng/Phút)<br>
{{< katex >}}\mathcal{M}\mathscr{c}knife_phase_mod{content}{{< /katex >}}: Hệ số pha cắt ruột (đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}DetPackHeight_{content}{{< /katex >}}: Chiều cao tối đa của chồng cắt - ruột (CM)<br>

  {{< /details >}}
- **Thời gian gấp sách**
  * *Công thức tính thời gian gấp sách*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGGS
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Folding{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{\lceil{(\mathcal{M}\mathscr{c}PN{content} * 60) / \mathcal{C}\mathscr{i}Det_{Foldingmachinefin}}\rceil + \lceil{\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/ \mathcal{M}\mathscr{i}Imp_{content}}\rceil * \mathcal{C}\mathscr{i}Det_{Foldingmachineprep}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{c}PN{content}{{< /katex >}}: Số lượng tờ in ruột (tờ)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Foldingmachinefin}{{< /katex >}}: Tốc độ máy gấp sách (Tay sách/Phút)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Foldingmachineprep}{{< /katex >}}: Thời gian chuẩn bị máy gấp sách (Phút)<br>

  {{< /details >}}
- **Thời gian bắt tay sách**
  * *Thời gian bắt tay sách, dùng máy kỵ mã liên hợp*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGKBTS
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Collating{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * 60) / \mathcal{C}\mathscr{i}Det_{Collating} + \mathcal{C}\mathscr{i}Prep_{Collating}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Collating}{{< /katex >}}: Tốc độ bắt tay sách (Cuốn/Giờ)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Prep_{Collating}{{< /katex >}}: Thời gian chuẩn bị bắt tay sách (Phút)<br>

  {{< /details >}}
- **Thời gian khâu chỉ**
  * *Công thức tính thời gian khâu chỉ*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGKC
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Sewing{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{((\mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf}) / \mathcal{C}\mathscr{i}Det_{SewingachineSpd}) * \lceil{\mathcal{M}\mathscr{i}{\Sigma}pg_{content}/ \mathcal{M}\mathscr{i}Imp_{content}}\rceil + \mathcal{C}\mathscr{i}Det_{SewingMachinePrep}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{SewingachineSpd}{{< /katex >}}: Tốc độ máy khâu chỉghim (Tờ/Giờ)<br>
{{< katex >}}\mathcal{M}\mathscr{i}{\Sigma}pg_{content}{{< /katex >}}: Số trang ruột mỗi cuốn sách (Trang)<br>
{{< katex >}}\mathcal{M}\mathscr{i}Imp_{content}{{< /katex >}}: Kiểu bình - Ruột (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{SewingMachinePrep}{{< /katex >}}: Thời gian chuẩn bị máy khâu chỉ (Phút)<br>

  {{< /details >}}
- **Thời gian vào keo**
  * *Thời gian vào keo*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGVK
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Glue{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * 60) / \mathcal{C}\mathscr{i}Det_{Glue} + \mathcal{C}\mathscr{i}Prep_{Glue}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Glue}{{< /katex >}}: Tốc độ vào keo (Cuốn/Giờ)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Prep_{Glue}{{< /katex >}}: Thời gian chuẩn bị vào keo (Phút)<br>

  {{< /details >}}
- **Thời gian vào bìa**
  * *Thời gian vào keo*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGV
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Covering{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * 60) / \mathcal{C}\mathscr{i}Det_{Covering} + \mathcal{C}\mathscr{i}Prep_{Covering}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Covering}{{< /katex >}}: Tốc độ vào bìa (Cuốn/Giờ)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Prep_{Covering}{{< /katex >}}: Thời gian chuẩn bị vào bìa (Phút)<br>

  {{< /details >}}
- **Thời gian xén 3 mặt**
  * *Thời gian xén 3 mặt*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGXEN
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Trim{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}C_{copies} * \mathcal{S}\mathscr{i}O_{wf} * 60) / \mathcal{C}\mathscr{i}Det_{Trim} + \mathcal{C}\mathscr{i}Prep_{Trim}}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{S}\mathscr{i}O_{wf}{{< /katex >}}: Hệ số bù hao (Đơn vị)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Trim}{{< /katex >}}: Tốc độ vào bìa, xén 3 mặt (Cuốn/Giờ)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Prep_{Trim}{{< /katex >}}: Thời gian chuẩn bị vào bìa, xén 3 mặt (Phút)<br>

  {{< /details >}}
- **Thời gian đóng gói**
  * *Thời gian đóng gói*
  * *Đơn vị*: Phút
  * *Mã*: CHRTGDG
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Packaging{{< /katex >}}
  * *Công thức* :{{< katex >}}\lceil{(\mathcal{M}\mathscr{i}C_{copies} * \mathcal{C}\mathscr{i}Det_{Packaging}) / (\mathcal{C}\mathscr{i}NoBookPerPack * \mathcal{C}\mathscr{i}NoBookPerPack)  * 1.618^((\mathcal{C}\mathscr{i}NoBookPerPack -1 )/\mathcal{C}\mathscr{i}NoBookPerPack)}\rceil{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{M}\mathscr{i}C_{copies}{{< /katex >}}: Số lượng sản phẩm (Bản)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Det_{Packaging}{{< /katex >}}: Tốc độ đóng gói trung bình (Phút/Gói)<br>
{{< katex >}}\mathcal{C}\mathscr{i}NoBookPerPack{{< /katex >}}: Số sách mỗi gói (Cuốn)<br>
{{< katex >}}\mathcal{C}\mathscr{i}NoBookPerPack{{< /katex >}}: Số nhân công đóng gói (Cuốn)<br>

  {{< /details >}}
- **Thời gian hoàn thiện khác**
  * *Thời gian hoàn thiện khác*
  * *Đơn vị*: Phút
  * *Mã*: CHRCMOTHR
  * *Kí hiệu*: {{< katex >}}\mathcal{C}\mathscr{i}Other_{completion}{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{i}Other_{CompletionInput}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Other_{CompletionInput}{{< /katex >}}: Thời gian hoàn thiện khác (Phút)<br>

  {{< /details >}}
- **Tổng thời gian hoàn thiện**
  * *Toàn bộ thời gian hoàn thiện*
  * *Đơn vị*: Phút
  * *Mã*: CHRSMCM
  * *Kí hiệu*: {{< katex >}}\mathcal{C}{\Sigma}COM{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}\mathscr{i}Lamination + \mathcal{C}\mathscr{i}KnifePhase_{cover} + \mathcal{C}\mathscr{i}KnifePhase_{content} + \mathcal{C}\mathscr{i}Folding + \mathcal{C}\mathscr{i}Collating + \mathcal{C}\mathscr{i}Sewing + \mathcal{C}\mathscr{i}Stapling + \mathcal{C}\mathscr{i}Glue + \mathcal{C}\mathscr{i}Covering + \mathcal{C}\mathscr{i}Trim + \mathcal{C}\mathscr{i}Packaging + \mathcal{C}\mathscr{i}Other_{completion}{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}\mathscr{i}Lamination{{< /katex >}}: Thời gian cán màng (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}KnifePhase_{cover}{{< /katex >}}: Thời gian pha cắt bìa (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}KnifePhase_{content}{{< /katex >}}: Thời gian pha cắt ruột (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Folding{{< /katex >}}: Thời gian gấp sách (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Collating{{< /katex >}}: Thời gian bắt tay sách (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Sewing{{< /katex >}}: Thời gian khâu chỉ (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Stapling{{< /katex >}}: Thời gian đóng ghim (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Glue{{< /katex >}}: Thời gian vào keo (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Covering{{< /katex >}}: Thời gian vào bìa (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Trim{{< /katex >}}: Thời gian xén 3 mặt (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Packaging{{< /katex >}}: Thời gian đóng gói (Phút)<br>
{{< katex >}}\mathcal{C}\mathscr{i}Other_{completion}{{< /katex >}}: Thời gian hoàn thiện khác (Phút)<br>

  {{< /details >}}
- **Tổng thời gian sản xuất**
  * *Toàn bộ thời gian sản xuất*
  * *Đơn vị*: Phút
  * *Mã*: CHRTTL
  * *Kí hiệu*: {{< katex >}}\mathcal{C}{\Sigma}TOTAL{{< /katex >}}
  * *Công thức* :{{< katex >}}\mathcal{C}{\Sigma}PPR + \mathcal{C}{\Sigma}PRT + \mathcal{C}{\Sigma}COM{{< /katex >}}

  {{< details "Thành Phần" >}}{{< katex >}}\mathcal{C}{\Sigma}PPR{{< /katex >}}: Tổng thời gian chế bản (Phút)<br>
{{< katex >}}\mathcal{C}{\Sigma}PRT{{< /katex >}}: Tổng thời gian in (Phút)<br>
{{< katex >}}\mathcal{C}{\Sigma}COM{{< /katex >}}: Tổng thời gian hoàn thiện (Phút)<br>

  {{< /details >}}



