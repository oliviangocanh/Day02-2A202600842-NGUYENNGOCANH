# 03 — Individual Reflection Plan cho nhóm 5 người

## Phân công tổng thể

| Thành viên | Vai trò chính | Nhiệm vụ chính | Output nên có |
|---|---|---|---|
| **Long** | Coordinator + Problem Statement Owner | Tổng hợp top 3 problems của cả nhóm, chấm điểm shortlist, viết Problem Statement v0/v1/final | Bảng cluster, bảng score, Problem Statement |
| **Ngọc Anh** | Workflow Owner | Vẽ current/future workflow cho bài toán deadline tracker, xác định bottleneck, before/after impact | Mermaid workflow, bảng before/after impact |
| **Việt Anh** | Research Owner | Tìm các tool/case có sẵn như Google Calendar, Todoist, Microsoft To Do, Zapier, Motion/Reclaim | Bảng research giải pháp, research takeaway |
| **Hoàng Anh** | Rule / Workflow / Agent Owner | Phân tích nên dùng Rule, Workflow hay Agent; lập luận vì sao chọn Workflow | Bảng Rule/Workflow/Agent, boundary, risk |
| **Ngô Anh** | Validation + Risk Owner | Làm quick validation, hỏi nhanh bạn bè/sinh viên, tổng hợp feedback, viết exit/rollback | Bảng validation, risk, fallback, final decision |



# Reflection cho Ngọc Anh

## Đóng góp của Ngọc Anh trong nhóm

| Hoạt động | Ngọc Anh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra problem về theo dõi deadline từ Discord, Outlook, Zalo, cổng thông tin và ghi chú cá nhân | Problem này được nhóm chọn làm hướng chính |
| Workflow | Mô tả current state gồm mở nhiều nguồn, đọc thông báo, lọc deadline, ghi note, nhập calendar | Nhóm thấy rõ bottleneck nằm ở việc lọc và nhập deadline thủ công |
| Future workflow | Đề xuất workflow mới: paste/import text → AI extract → user review → export calendar/todo | Nhóm có before/after rõ ràng |
| Impact | Ước lượng thời gian trước/sau và số bước thủ công | Nhóm có metric để đánh giá MVP |
| Human boundary | Nhấn mạnh user phải review trước khi lưu deadline | Giảm rủi ro AI nhập sai lịch |

## Bảng dùng AI trong reflection của Ngọc Anh

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Workflow | Nhờ AI chuyển mô tả thành Mermaid | Nhanh hơn khi vẽ current/future workflow | AI đôi lúc gộp bước lọc deadline và nhập calendar | Tách lại để thấy bottleneck rõ hơn |
| Impact | Nhờ AI tạo bảng before/after impact | Có format rõ, dễ đưa vào file markdown | Một số metric chưa sát với sinh viên | Chỉnh lại metric theo thời gian/tuần và số deadline sót |
| Boundary | Nhờ AI gợi ý human review point | Giúp xác định điểm kiểm soát chất lượng | AI đôi khi muốn tự động sync calendar quá sớm | Giữ bước review bắt buộc |
| Fallback | Nhờ AI nghĩ fallback khi extract sai | Có nhiều phương án rollback | Một số fallback quá kỹ thuật | Chọn fallback đơn giản: sửa tay hoặc không lưu |

## Bài học của Ngọc Anh

Vẽ workflow giúp nhóm nhìn rõ AI nên nằm ở đâu. Nếu chỉ nói “AI quản lý deadline” thì scope rất rộng, nhưng khi vẽ từng bước, nhóm thấy phần tốn công nhất là đọc, lọc và chuẩn hóa deadline từ nhiều nguồn. Future state không cần thay thế Google Calendar mà chỉ cần biến text rời rạc thành deadline có cấu trúc.

Nếu làm lại, tôi sẽ đo thử thời gian thật của một tuần học để bảng before/after có dữ liệu đáng tin hơn.

---

