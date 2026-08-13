# Hướng dẫn đóng góp

Cảm ơn bạn đã muốn đóng góp vào CyberKnight Lab! Để đảm bảo chất lượng và tính thống nhất, vui lòng tuân thủ các quy tắc sau:

## 1. Quy tắc đặt tên nhánh (Branch)
- `feature/xx-ten-ngan` (vd: `feature/04-add-sigma-rule`)
- `fix/xx-ten-loi` (vd: `fix/03-update-wazuh-config`)

## 2. Quy trình nộp bài (Pull Request)
- Mỗi PR phải gắn với ít nhất 1 Issue.
- Phải kèm **bằng chứng** trong thư mục `evidence/T-G0-XX/` (ảnh chụp màn hình, file log, pcap).
- Chỉ định ít nhất 1 người review (thường là Project Lead).

## 3. Tiêu chuẩn tài liệu
- File Markdown (.md) phải được định dạng rõ ràng, có tiêu đề, bảng biểu nếu cần.
- Rule phát hiện (Sigma/Wazuh) phải có comment giải thích và mapping MITRE.

## 4. Review
- Người review kiểm tra tính chính xác của rule/logic, không kiểm tra lỗi chính tả.
- Nếu rule sai, reviewer ghi comment giải thích và yêu cầu sửa.

## 5. Hỗ trợ
Nếu bị kẹt, tạo Issue với tag `help-wanted` và mô tả chi tiết vấn đề (kèm log).