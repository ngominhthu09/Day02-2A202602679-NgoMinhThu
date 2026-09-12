# 03 — Individual Reflection

## Thông tin cá nhân

- Họ và tên: Ngô Minh Thu
- Mã học viên: 2A202602679
- Thành viên nhóm: Trần Thanh Thái, Cao Đức Hiếu, Dương Hữu Đạt, Trần Công Thiện, Lê Quang Ngọc và Ngô Minh Thu.
- Vai trò: UX Writer.
- Candidate problem nhóm chọn: Giáo viên mất khoảng 60–180 phút mỗi tuần để tổng hợp điểm, ô điểm trống và ghi chú của khoảng 60 học sinh.

---

## 1. Tôi đã tham gia vào phần nào?

Các dòng dùng “mình” ghi phần cá nhân; các dòng dùng “nhóm” tóm tắt kết quả chung trong báo cáo.

| Hoạt động                  | Phần cá nhân / nội dung nhóm ghi nhận                                                                      | Kết quả / ảnh hưởng tới nhóm                                                                             |
| -------------------------- | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Scan cá nhân               | Mình liệt kê 8 vấn đề về việc di chuyển và chọn tuyến đường.                                               | Chọn ra 3 vấn đề để làm Problem Cards.                                                                   |
| Pitch Problem Card         | Mình chuẩn bị 3 cards, ưu tiên bài cảnh báo đường thi công, cấm hoặc phân luồng.                           | Cả 3 candidate được ghi nhận trong bảng pitch của nhóm.                                                  |
| Chuẩn bị câu hỏi challenge | Mình chuẩn bị câu hỏi về việc app bản đồ đã giải quyết được bao nhiêu và độ mới của dữ liệu giao thông.    | Nêu rõ những điểm bài cá nhân cần kiểm chứng thêm.                                                       |
| Gom trùng / cluster        | Ba candidate của mình được xếp cùng Hiếu vào cụm hỗ trợ ra quyết định và tối ưu.                           | Các bài có điểm chung được đặt cạnh nhau để so sánh.                                                     |
| Chọn candidate problem     | Nhóm so sánh các candidate và chọn bài tổng hợp tình hình học tập của Thái.                                | Thống nhất tập trung vào bước đối chiếu dữ liệu và viết nhận xét của giáo viên.                          |
| Validation / research      | Báo cáo nhóm ghi nhận phỏng vấn 3 giáo viên và tìm hiểu Google Apps Script, ChatGPT/LLM.                   | Nhóm xác định giáo viên phải duyệt và chỉnh sửa nhận xét trước khi gửi.                                  |
| Workflow nhóm              | Nhóm xây dựng luồng gom dữ liệu → Rule kiểm tra → AI gợi ý → giáo viên duyệt → gửi báo cáo.                | Phân rõ việc hệ thống hỗ trợ và việc giáo viên quyết định.                                               |
| Problem Statement          | Nhóm hoàn thiện PS v0/v1 và bổ sung cách xử lý khi AI gợi ý sai.                                           | Giáo viên có thể bỏ bản nháp và viết lại từ dữ liệu gốc.                                                 |
| Rule / Workflow / Agent    | Bài cá nhân ưu tiên data + rule + notification. Với bài giáo viên, nhóm chọn Workflow kết hợp Rule và LLM. | Rule kiểm tra dữ liệu, LLM gợi ý nhận xét; giáo viên duyệt trước khi gửi và dùng dữ liệu gốc nếu AI sai. |
| Decision                   | Nhóm chọn Go, đề xuất thử với dữ liệu giả lập của 30 học sinh.                                             | Pilot dự kiến đo thời gian tạo nháp, số nhận xét bịa thông tin và thời gian giáo viên duyệt.             |

Dấu tay rõ nhất của tôi trong artifact cuối:

Mình đóng góp 3 candidate về giao thông, được ghi trong bảng pitch và cụm hỗ trợ ra quyết định. Bài cá nhân làm rõ hướng dùng data + rule + notification cho MVP và những dữ liệu cần kiểm chứng thêm.

---

## 2. Bảng dùng AI

Bảng dưới ghi hai phần dùng AI được mô tả trong bài cá nhân; góp ý về Rule / Workflow / Agent được gộp vào Problem Card.

| Phase        | Tôi dùng AI để làm gì?                                          | AI hữu ích ở đâu?                                                                   | AI sai / hời hợt ở đâu?                                                                  | Tôi sửa gì bằng nhận định của mình?                                                                                           |
| ------------ | --------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| Scan         | Gợi ý thêm vấn đề theo 4 lăng kính từ việc di chuyển hằng ngày. | Mở rộng các hướng như tìm tuyến thay thế, theo dõi thông báo và chọn giờ xuất phát. | Các ý bị loại có hướng quá rộng và những con số chưa đo thực tế.                         | Mình giữ phạm vi hành trình quen thuộc, bỏ hướng quản lý giao thông toàn thành phố, tự lái xe và số phút chưa có căn cứ.      |
| Problem Card | Phản biện điểm nghẽn, cách đo và mức cần thiết của AI.          | Chỉ ra việc thiếu baseline, phần trùng với app bản đồ và sự phụ thuộc vào dữ liệu.  | Góp ý mới giúp xác định điều cần kiểm chứng, chưa xác nhận được mức độ bất tiện thực tế. | Mình thu hẹp đối tượng, ưu tiên nguồn chính thức và chọn MVP dùng data + rule + notification; chỉ thử LLM nếu parser chưa đủ. |

---

## 3. Reflection câu hỏi mở

Mình chuẩn bị 8 vấn đề về giao thông và chọn 3 bài để làm Problem Cards. Ba candidate này được ghi trong bảng pitch và cụm hỗ trợ ra quyết định, là phần đóng góp rõ nhất của mình trong báo cáo nhóm. Mình ưu tiên bài cảnh báo đường thi công hoặc cấm trước khi xuất phát, với MVP dùng data + rule + notification. Nhóm chọn bài tổng hợp tình hình học tập của giáo viên để phân tích sâu hơn. Điểm nghẽn của bài nhóm là đối chiếu điểm, ô trống và ghi chú để viết nhận xét. Nhóm chọn Workflow gồm Rule kiểm tra dữ liệu, LLM gợi ý nhận xét và giáo viên duyệt trước khi gửi. Mục tiêu trong báo cáo là giảm thời gian xử lý xuống dưới 60 phút mỗi tuần, với kế hoạch thử trên dữ liệu giả lập của 30 học sinh. Phần còn khó trong bài cá nhân là xác định số đo ban đầu để so sánh trước và sau cải thiện. Số liệu giao thông chung chưa cho biết mình mất bao nhiêu thời gian mỗi chuyến hoặc gặp đường cấm bao nhiêu lần. Vì vậy, các mốc thời gian trong workflow cá nhân vẫn được ghi là giả định hoặc mục tiêu. Nếu làm lại, mình sẽ ưu tiên ghi lại 5-10 chuyến để đo thời gian chọn tuyến, thời gian di chuyển và số lần phải đổi đường.

---
