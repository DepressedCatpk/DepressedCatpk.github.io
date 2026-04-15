---
title: "Hệ thống Giám sát Nhiệt độ đa kênh (Arduino)"
excerpt: "Dự án thu thập và xử lý dữ liệu nhiệt độ từ 2 cảm biến LM35, giao tiếp qua Serial.<br/><img src='/images/profile.jpg' width='300'>"
collection: portfolio
---

# 🌡️ Giới thiệu dự án
Đây là dự án thực hành tập trung vào việc thu thập, xử lý dữ liệu nhiệt độ từ môi trường thực tế và quản lý mã nguồn chuyên nghiệp.

## 🛠 Tính năng nổi bật
* **Đọc dữ liệu song song:** Hỗ trợ đọc đồng thời từ 2 cảm biến nhiệt độ LM35 (kênh A0, A1).
* **Xử lý thời gian thực:** Chuyển đổi tín hiệu Analog (ADC) sang độ C với độ chính xác cao.
* **Truyền dữ liệu (Telemetry):** Đóng gói dữ liệu dưới dạng định dạng chuẩn CSV và gửi qua cổng Serial (baudrate 9600) để dễ dàng vẽ đồ thị trên máy tính.
* **Quy trình làm việc (Workflow):** Dự án được quản lý phiên bản bằng Git/GitHub, áp dụng triệt để quy trình rẽ nhánh (Branching) và hợp nhất (Merging).

## 💻 Mã nguồn dự án
Toàn bộ mã nguồn (Firmware) và tài liệu hướng dẫn (README) đã được công khai. Bạn có thể xem chi tiết và tải về tại kho lưu trữ GitHub của mình:

👉 **[Xem Repository Arduino_LM35_TempMonitor tại đây](https://github.com/DepressedCatpk/Arduino_LM35_TempMonitor)**