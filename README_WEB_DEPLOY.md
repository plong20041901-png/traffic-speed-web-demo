# Traffic Speed Violation Web Demo

Đây là web demo tĩnh cho đồ án phát hiện phương tiện chạy quá tốc độ.

## Nội dung web

- Dashboard giao diện giám sát giao thông
- Link video demo đã xử lý trên Google Drive
- Bảng thống kê kết quả
- CSV log tốc độ và vi phạm
- Confusion Matrix
- PR Curve
- F1 Curve
- Ảnh bằng chứng vi phạm

## Cách deploy bằng GitHub Pages

1. Tạo repository mới trên GitHub, ví dụ: `traffic-speed-web-demo`.
2. Upload toàn bộ nội dung trong thư mục `10_web_demo` lên repository.
3. Vào `Settings`.
4. Chọn `Pages`.
5. Trong mục `Build and deployment`, chọn:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Bấm Save.
7. Sau vài phút, GitHub sẽ cấp link web public.

## Ghi chú

Web này là web tĩnh. Hệ thống YOLO đã xử lý video trước đó, sau đó kết quả được đưa lên dashboard. Vì vậy web vẫn hoạt động khi Colab/code đã tắt.