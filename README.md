# LAB5 · L3A · T2 Giáo dục · Nhóm Cu Đơ

Trợ lý học bài trên trang khoá học "Nhập môn phân tích dữ liệu" (buổi 3): khi AI không chắc hoặc sai thì học viên thấy gì, và AI được tự làm tới đâu.

Thành viên và phân công: bảng ở đầu [`spec.md`](spec.md).

| File | Nội dung |
|---|---|
| [`spec.md`](spec.md) | Bài nộp, §1–§7 |
| [`prototype/index.html`](prototype/index.html) | Prototype 2 màn hình: học viên và hàng chờ TA. Tải về rồi mở bằng trình duyệt |
| [`prototype/screen-1-hoc-vien.png`](prototype/screen-1-hoc-vien.png), [`prototype/screen-2-ta.png`](prototype/screen-2-ta.png) | Ảnh đánh số ①–⑧ |
| [`prototype/phan_loai.py`](prototype/phan_loai.py) | Lời gọi OpenAI thật cho quyết định chính, kèm các bước hệ thống (đối chiếu, câu từ chối cố định) và bộ tự kiểm |
| [`prototype/log-phan-loai.json`](prototype/log-phan-loai.json), [`prototype/log-v2/`](prototype/log-v2/) | Log bản v1 (chỉ có router) và 4 lần chạy bản v2 |
| [`GLOSSARY.md`](GLOSSARY.md) | Thuật ngữ dùng trong bài |

Chạy lại lời gọi AI thật: `OPENAI_API_KEY=... python3 prototype/phan_loai.py`. Key để ở biến môi trường, không commit.
