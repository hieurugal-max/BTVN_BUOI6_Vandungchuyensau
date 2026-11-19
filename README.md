# BÀI TẬP: THIẾT KẾ GIẢI PHÁP PROMPTING ỨNG DỤNG THỰC TẾ CHO ỨNG DỤNG AI TRONG HỌC TẬP VÀ NGHIÊN CỨU

## Bước 1: Thiết kế giải pháp (I/O)

### 1. Input (Dữ liệu đầu vào)

- Nội dung bài học hoặc kiến thức sinh viên cần học.
- Câu trả lời của sinh viên.
- Rubric chấm điểm (các tiêu chí và thang điểm).
- Yêu cầu về mức độ kiến thức cần đạt.

### 2. Output (Kết quả đầu ra)

- Giải thích kiến thức theo phương pháp Feynman Prompt để sinh viên dễ hiểu.
- Đánh giá câu trả lời theo từng tiêu chí trong Rubric.
- Điểm số tổng và nhận xét cụ thể.
- Chỉ ra những phần sinh viên làm đúng, chưa đúng và hướng dẫn cách cải thiện.

## Bước 2: Viết prompt và chạy thử

### 1. Prompt thực thi

Bạn là trợ lý AI hỗ trợ học tập và chấm bài tự động cho sinh viên.

Nhiệm vụ:
1. Sử dụng phương pháp Feynman để giải thích kiến thức bằng ngôn ngữ đơn giản, dễ hiểu, có ví dụ minh họa.
2. Đọc câu trả lời của sinh viên và đối chiếu với Rubric được cung cấp.
3. Chấm điểm theo từng tiêu chí, nhận xét rõ ràng và chỉ ra lỗi sai.
4. Đưa ra gợi ý để sinh viên cải thiện câu trả lời.

Dữ liệu đầu vào:
- Nội dung bài học: [Nhập nội dung bài học]
- Câu trả lời của sinh viên: [Nhập câu trả lời]
- Rubric chấm điểm: [Nhập tiêu chí và thang điểm]

Quy tắc xử lý:
- Nếu thiếu nội dung bài học, yêu cầu người dùng bổ sung.
- Nếu câu trả lời bị trống, thông báo chưa có bài làm và không tự ý chấm điểm.
- Nếu thiếu Rubric, thông báo chưa đủ dữ liệu để chấm chính xác.
- Nếu dữ liệu không rõ ràng hoặc mâu thuẫn, yêu cầu xác nhận lại.
- Không tự ý thêm tiêu chí hoặc thay đổi thang điểm.
- Không đưa ra thông tin sai lệch hoặc điểm số không có căn cứ.

Định dạng kết quả:
1. Giải thích kiến thức theo phương pháp Feynman.
2. Bảng chấm điểm gồm: Tiêu chí, Điểm tối đa, Điểm đạt được, Nhận xét.
3. Tổng điểm.
4. Nhận xét chung và hướng cải thiện.

### 2. Kết quả chạy thử

**Dữ liệu đầu vào:**

- **Nội dung bài học:** Khái niệm trí tuệ nhân tạo (AI).
- **Câu trả lời của sinh viên:** AI là công nghệ giúp máy tính thực hiện một số công việc cần đến trí thông minh của con người như nhận diện hình ảnh, trả lời câu hỏi và phân tích dữ liệu.
- **Rubric chấm điểm:**
  - Đúng kiến thức: 4 điểm.
  - Đầy đủ nội dung: 3 điểm.
  - Ví dụ minh họa: 2 điểm.
  - Trình bày rõ ràng: 1 điểm.

**Kết quả AI phản hồi:**

**1. Giải thích theo phương pháp Feynman**

AI có thể hiểu đơn giản là công nghệ giúp máy tính học hỏi từ dữ liệu và thực hiện những công việc thường cần đến trí thông minh của con người. Ví dụ, AI có thể nhận diện khuôn mặt, trả lời câu hỏi hoặc gợi ý nội dung phù hợp.

**2. Bảng chấm điểm**

| Tiêu chí | Điểm tối đa | Điểm đạt |
|---|---:|---:|
| Đúng kiến thức | 4 | 4 |
| Đầy đủ nội dung | 3 | 2 |
| Ví dụ minh họa | 2 | 1 |
| Trình bày rõ ràng | 1 | 1 |
| **Tổng điểm** | **10** | **8** |

**3. Nhận xét chung**

Câu trả lời đúng kiến thức cơ bản, diễn đạt rõ ràng và có nêu một số ứng dụng của AI. Tuy nhiên, phần ví dụ chưa được giải thích cụ thể và nội dung còn hơi ngắn.

**4. Hướng cải thiện**

Bổ sung ví dụ thực tế như AI nhận diện khuôn mặt khi mở khóa điện thoại và giải thích cách ứng dụng này hoạt động.
