# Problem backlog

Những chỗ gặp trong lúc gán nhãn mà **guideline chưa trả lời được**, cộng các pain point về công cụ.

Ghi ngay khi gặp, kể cả lúc chưa biết xử lý thế nào. Một edge case không được ghi lại thì
mỗi người sẽ tự xử lý theo một kiểu — và đó là nguồn lớn nhất của nhãn không nhất quán.

## Danh sách

| Mã | Tóm tắt | Loại | Mục guideline | Trạng thái | Kết quả |
|---|---|---|---|---|---|
| [P-001](#p-001) | Không phân biệt được area/drivable và area/alternative | Guideline chưa nói tới | §2 | ↗️ Hỏi BTC | — |
| [P-002](#p-002) | Xe dạng bánh xích dùng cho dây dựng, sửa chữa chưa biết chọn class nào | Guideline chưa nói tới | §2 | ↗️ Hỏi BTC | — |

**Loại**

| Loại | Nghĩa là |
|---|---|
| Guideline chưa nói tới | Tình huống không có trong guideline |
| Guideline mơ hồ | Đọc guideline ra được hai cách hiểu trở lên |
| Guideline mâu thuẫn | Hai mục trong guideline nói ngược nhau |
| Pain point công cụ | Guideline rõ, nhưng làm trên CVAT chậm hoặc dễ sai |

**Trạng thái:** 🔴 Mở · 🗣️ Đang bàn · ↗️ Hỏi BTC · ✅ Đã chốt (trỏ sang QĐ) · 🛠️ Làm tool (trỏ sang `source-tool/`) · ⚪ Bỏ (ghi lý do)

---

## P-001

**Không phân biệt được area/drivable và area/alternative**

- **Loại:** Guideline chưa nói tới
- **Mục guideline:** §2
- **Người phát hiện:** @levietanhoffice · 15/09/2026
- **Link CVAT:**
  - 
- **Mô tả:** §2 chỉ phân loại area/drivable và area/alternative, chưa nói mô tả cụ thể 2 class hoặc cách phân biệt.
- **Các cách hiểu:**
  1. area/drivable là vùng đường chính xe đang đi, area/alternative là vùng không phải đường chính xe đang đi.
- **Xử lý tạm trong lúc chờ:** làm theo cách hiểu 1.
- **Kết quả:** ↗️ Hỏi BTC

## P-002

**Xe dạng bánh xích dùng cho dây dựng, sửa chữa chưa biết chọn class nào**

- **Loại:** Guideline chưa nói tới
- **Mục guideline:** §2
- **Người phát hiện:** @levietanhoffice · 15/09/2026
- **Link CVAT:**
  - 
- **Mô tả:** §2 chưa nói mô tả cụ thể class car, truck.
- **Các cách hiểu:**
  1. Coi là xe dạng truck.
- **Xử lý tạm trong lúc chờ:** làm theo cách hiểu 1.
- **Kết quả:** ↗️ Hỏi BTC
---

## Mẫu để copy

```markdown
## P-NNN

**Tóm tắt một dòng**

- **Loại:** Guideline chưa nói tới | Guideline mơ hồ | Guideline mâu thuẫn | Pain point công cụ
- **Mục guideline:** §
- **Người phát hiện:** @ · dd/mm/yyyy
- **Link CVAT:** (bỏ trống nếu không có)
  - https://…/tasks/<id>/jobs/<id>?frame=<n> — frame này có gì
- **Mô tả:**
- **Các cách hiểu:** (với pain point công cụ thì ghi **Hướng đang cân nhắc:**)
  1.
  2.
- **Xử lý tạm trong lúc chờ:**
- **Kết quả:** 🔴 Mở
```

Nhớ thêm một dòng vào bảng **Danh sách** ở đầu file.
