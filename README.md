# Smart Rebar Studio 🏗️

Smart Rebar Studio là ứng dụng Web offline hoàn chỉnh (Single-Page Application) hỗ trợ kỹ sư kết cấu giả thiết và thiết kế cốt thép (Dầm, Cột, Sàn) nhanh chóng, chính xác theo tiêu chuẩn **TCVN 5574:2018**.

## Tính năng nổi bật
- **⚡ Tính Toán Tức Thì (Smart Calc):** Đề xuất tự động các phương án bố trí cốt thép tối ưu ngay khi bạn nhập hoặc kéo thanh trượt thông số.
- **📐 Bản Vẽ CAD Trực Quan:** Tự động vẽ mặt cắt tiết diện với kích thước, cốt thép, thép đai, và lớp bảo vệ một cách chi tiết theo tỷ lệ.
- **🌙 Chế Độ Dark Mode:** Hỗ trợ giao diện tối cho môi trường làm việc thiếu sáng, giảm mỏi mắt (Bản vẽ CAD tự động tối ưu độ tương phản).
- **💾 Lưu Trữ Dự Án (LocalStorage):** Không sợ mất dữ liệu. Chuyển đổi giữa các cấu kiện Dầm/Cột/Sàn mà trạng thái vẫn được giữ nguyên.
- **🖨️ In Ấn & Xuất Bản Vẽ (Print-Ready):** Tối ưu hóa CSS để khi in (Ctrl+P) hoặc xuất ra PDF, bản vẽ luôn ở định dạng nền trắng - chữ đen chuẩn kỹ thuật.
- **📚 Trình Cứu TCVN:** Tích hợp sẵn bảng tra cứu thép tròn, thông số vật liệu bê tông, cốt thép và hướng dẫn cấu tạo cốt thép (khoảng cách tối đa/tối thiểu).

## Công nghệ sử dụng
- **HTML5 & CSS3:** Giao diện Responsive, Semantic Dark Mode, CSS Variables.
- **Vanilla JavaScript (ES6+):** Xử lý DOM, logic tính toán, render SVG.
- **SVG (Scalable Vector Graphics):** Vẽ đồ họa kỹ thuật độ chính xác cao.
- **Không phụ thuộc thư viện ngoài:** Chạy hoàn toàn trên trình duyệt, có thể sử dụng Offline không cần kết nối mạng.

## Hướng dẫn triển khai lên GitHub Pages (Live Website)

Để chia sẻ công cụ này cho mọi người sử dụng thực tế trên internet, bạn hãy làm theo các bước sau:

1. **Tạo Repository trên GitHub:**
   - Đăng nhập vào [GitHub](https://github.com).
   - Chọn **New Repository**.
   - Đặt tên (ví dụ: smart-rebar-studio).
   - Đảm bảo chọn chế độ **Public** (để dùng GitHub Pages miễn phí).

2. **Tải mã nguồn lên GitHub:**
   - Tại trang repo vừa tạo, chọn **"uploading an existing file"**.
   - Kéo thả 2 file index.html và README.md trong thư mục này vào khung upload.
   - Nhấn **Commit changes**.

3. **Kích hoạt GitHub Pages:**
   - Chuyển sang tab **Settings** của repository.
   - Kéo xuống mục **Pages** (ở cột menu bên trái).
   - Dưới phần **Build and deployment** -> **Source**, chọn nhánh main (hoặc master), thư mục / (root).
   - Nhấn **Save**.
   - Chờ khoảng 1-2 phút, GitHub sẽ hiển thị đường link trang web của bạn (ví dụ: https://<username>.github.io/smart-rebar-studio/).

Bây giờ bạn đã có thể truy cập và sử dụng Smart Rebar Studio ở bất cứ đâu!

## Giấy phép
Tài liệu và mã nguồn phục vụ mục đích học tập và hỗ trợ kỹ thuật công trình.
