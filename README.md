# MV_Assisant_Tools

MV_Assisant_Tools là công cụ chuyên dùng để **Flash Firmware (FW)** và **Update Firmware & dữ liệu** cho các dòng chip **MVsilicon**.  
Phần mềm hỗ trợ kỹ thuật viên và bộ phận sản xuất nâng cấp firmware nhanh chóng, ổn định và an toàn.

---

## 📌 Giới thiệu

MV_Assisant_Tools được phát triển nhằm:

- Flash firmware cho chip MVsilicon
- Cập nhật Firmware và Data riêng biệt
- Tối ưu quy trình nâng cấp trong sản xuất & bảo trì
- Giảm thiểu lỗi do thao tác thủ công

---

## 🚀 Tính năng chính

- 🔹 Flash Firmware (FW)
- 🔹 Update Firmware và dữ liệu
- 🔹 Hỗ trợ nhiều dòng chip MVsilicon
- 🔹 Hiển thị tiến trình cập nhật theo thời gian thực
- 🔹 Thông báo trạng thái thành công / lỗi

---

## 🛠 Phiên bản hiện tại

- **MV_Assisant_Tools_V3.0.8**

---

## 🖥 Yêu cầu hệ thống

| Thành phần | Yêu cầu |
|------------|----------|
| Hệ điều hành | Windows 10 / 11 (64-bit) |
| RAM | ≥ 4GB |
| Kết nối | USB 2.0 / 3.0 |
| Driver | Driver USB phù hợp cho chip MVsilicon |

---

# 📥 Tải xuống

Phiên bản mới nhất được phát hành tại GitHub Releases:

🔗 https://github.com/nvmaudio/MV_Assisant_Tools/releases/tag/MV_Assisant_Tools

## 📦 Gói phát hành

- `MV_Assisant_Tools_XX.zip` – Phiên bản Portable (không cần cài đặt)

## 📌 Hướng dẫn tải

1. Truy cập link Releases ở trên  
2. Chọn phiên bản mới nhất  
3. Tải file `MV_Assisant_Tools_XX.zip` trong mục **Assets**  
4. Giải nén file  
5. Chạy `MV_Assisant_Tools_XX.exe`

---

# 🔄 Hướng dẫn Flash / Update Firmware

## 🖥 Giao diện chính

![Main UI](docs/images/main_ui.png)


## 1️⃣ Chuẩn bị

- Cáp USB kết nối thiết bị với máy tính  
- File Firmware (.bin hoặc định dạng được hỗ trợ)  
- File Data (nếu cần cập nhật dữ liệu)  
- Thiết bị được đưa vào chế độ Boot / Update  

---

## 2️⃣ Kết nối thiết bị


::contentReference[oaicite:0]{index=0}


1. Kết nối thiết bị với máy tính qua cổng USB  
2. Mở phần mềm **MV_Assisant_Tools**  
3. Kiểm tra trạng thái hiển thị **Connected**

---

## 3️⃣ Chọn Firmware và Data


::contentReference[oaicite:1]{index=1}


1. Nhấn nút **Browse / Select FW**  
2. Chọn file Firmware phù hợp  
3. Nếu cần cập nhật dữ liệu, chọn thêm file Data  

---

## 4️⃣ Tiến hành Flash / Update


::contentReference[oaicite:2]{index=2}


1. Nhấn **Flash** hoặc **Update**  
2. Chờ quá trình hoàn tất (không rút cáp USB)  
3. Khi hiển thị thông báo **Success / Completed**  
4. Thiết bị sẽ tự khởi động lại (nếu được cấu hình)

---

## ⚠️ Lưu ý quan trọng

- Không ngắt kết nối USB trong quá trình cập nhật  
- Sử dụng đúng firmware cho đúng dòng chip  
- Sao lưu dữ liệu trước khi cập nhật (nếu cần)  
- Kiểm tra driver nếu phần mềm không nhận thiết bị  

---

## 🐞 Xử lý sự cố

| Lỗi | Nguyên nhân | Cách khắc phục |
|------|------------|----------------|
| Không nhận thiết bị | Chưa vào Boot mode | Kiểm tra lại chế độ Boot |
| Update thất bại | Sai Firmware | Chọn đúng file FW |
| Treo giữa chừng | Mất kết nối USB | Thay cáp / đổi cổng USB |

---



## 👨‍💻 Liên hệ hỗ trợ

Nếu gặp sự cố trong quá trình sử dụng:
- Liên hệ bộ phận kỹ thuật nội bộ
