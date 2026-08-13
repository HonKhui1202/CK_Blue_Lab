##
- Sơ đồ mạng (network topology) thể hiện rõ ràng các vùng mạng: DMZ (chứa máy tấn công), CORP LAN (chứa AD và máy trạm), SOC ZONE (chứa SIEM và công cụ giám sát). Kèm theo đó là sơ đồ kết nối với pfSense (hoặc firewall ảo) làm bộ định tuyến trung tâm.

- Bảng kiểm kê tài sản (asset inventory) liệt kê từng máy với: tên, địa chỉ IP tĩnh, hệ điều hành, và vai trò cụ thể (DC, client, attacker, SIEM).

- Phân tích luồng mạng cơ bản: hướng dẫn các rule firewall cần thiết, ví dụ như chỉ cho phép CORP LAN gửi log đến SOC ZONE, cấm SOC ZONE truy cập ngược ra CORP LAN.

- Bảng phân bổ địa chỉ IP và subnet mask cho từng zone, gateway tương ứng.


