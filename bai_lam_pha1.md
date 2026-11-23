# BÀI LÀM PHA 1 (ĐỀ LUYỆN TẬP CHỦ ĐỀ TÀI CHÍNH CÁ NHÂN)

- **Họ tên:**
- **Lớp:**
- **Link repository Pha1:**

> Pha 1 (70 phút đầu, KHÔNG dùng AI). Viết xong, kéo thả file này vào repository Pha1 trước mốc giờ giám thị công bố.

## 4.1. Bảo vệ dữ liệu và chống ảo giác

### a) Ghi chú đã ẩn danh hoá

**GHI CHU DA AN DANH**

```text
Khách hàng [TEN_KHACH_HANG] , số điện thoại [SDT_KHACH_HANG], số CCCD [SO_CCCD_KHACH_HANG], email [EMAIL_KHACH_HANG], đăng ký 3 vé gói CB buổi hội thảo Ngày hội Tài chính Gia đình ngày 20/12/2026 cho 2 người lớn và 1 trẻ em 10 tuổi. Khách hàng đã chuyển khoản đặt cọc 1.000.000 đồng. Khách hàng yêu cầu 3 ghế ngồi cạnh nhau ở dãy bàn đầu gần màn hình chiếu.

```

### b) Hai câu lệnh chống ảo giác

**CAU LENH**

```text
(Viết câu 1 và câu 2 vào đây – xoá dòng này)
```

## 4.2. Trích xuất tin nhắn đăng ký hội thảo ra JSON

**PROMPT**

```text
[Context] : bạn là một chuyên gia phân tích dữ liệu khách hàng 
```

## 4.3. Báo giá vé hội thảo bằng Chain-of-Thought

### a) Prompt

**PROMPT**

```text
(Viết prompt vào đây – xoá dòng này)
```

## 4.4. Dây chuyền xử lý khiếu nại (Prompt Chaining)

### a) Prompt Trạm 1

**PROMPT**

```text
(Viết prompt Trạm 1 vào đây – xoá dòng này)
```

### b) Hai điều cần kiểm tra ở JSON đầu ra của Trạm 1

1. 
2. 

### c) Câu lệnh viết tiếp

**CAU LENH**

```text
(Viết câu lệnh nối tiếp khi Trạm 3 bị ngắt ở đoạn "…Ban tổ chức Hội thảo Tài chính Thông minh xin hoàn lại Quý khách khoản" – xoá dòng này)
```

## 4.5. Prompt chấm bài theo Rubric

**PROMPT**

```text
(Viết prompt chấm bài vào đây – xoá dòng này)
```

## 4.6. Hoàn thiện System Prompt

> Phần Vai trò và Chuẩn đầu ra đã cho sẵn. Viết tiếp phần Quy tắc ràng buộc và Xử lý ngoại lệ.

```text
[Vai trò]
Bạn là "Trợ lý Tài Chính Thông Minh", nhân viên tư vấn vé và dịch vụ trên website của chuỗi Hội thảo Tài chính Thông minh, giúp khách hàng chọn và đăng ký một trong 3 gói: CB (Gói Cơ Bản – quản lý chi tiêu và tiết kiệm), DT (Gói Đầu Tư – đầu tư cho người mới), VIP (Gói VIP – bàn tròn tư vấn cùng chuyên gia).

[Quy tắc ràng buộc]
(Viết 3 quy tắc ràng buộc vào đây – xoá dòng này)

[Chuẩn đầu ra]
Trả lời bằng tiếng Việt, lịch sự, tối đa 120 từ. Giá vé trình bày dạng gạch đầu dòng. Kết thúc bằng một câu hỏi về nhu cầu tiếp theo của khách.

[Xử lý ngoại lệ]
(Viết cách xử lý 2 tình huống ngoại lệ vào đây – xoá dòng này)
```
