🚀 Next.js Professional Starter Template
Một bộ khung (Boilerplate) hiện đại được tối ưu hóa cho tốc độ phát triển, hiệu năng SEO và trải nghiệm người dùng cao cấp. Phù hợp nhất cho các dự án Landing Page, Corporate Website và Product PR Site.

🛠 Tech Stack Core
Framework: Next.js 14+ (App Router) - Tối ưu Server Components & Streaming.

Styling: Tailwind CSS - Utility-first CSS cho việc tùy biến giao diện cực nhanh.

UI Components: Shadcn/ui (Radix UI Primitives) - Hệ thống component chất lượng cao, dễ tùy chỉnh.

Preset: Nova (Geist Font + Lucide Icons) - Mang lại cảm giác Modern, Technical & Clean.

Language: TypeScript - Đảm bảo an toàn kiểu dữ liệu và giảm thiểu lỗi runtime.

✨ Tính năng nổi bật

1. Kiến trúc Modern Slate & Geist Font
   Sử dụng bảng màu Slate trung tính, chuyên nghiệp, phù hợp với các website công nghệ và doanh nghiệp.

Tích hợp sẵn font Geist (Sans & Mono) từ Vercel, tối ưu cho việc đọc nội dung kỹ thuật và hiển thị sắc nét trên mọi thiết bị.

2. Cấu hình SEO Tập Trung
   Hệ thống Metadata API được setup sẵn tại src/config/site.ts.

Tối ưu hóa thẻ tiêu đề, mô tả và ảnh OpenGraph (thumbnail khi share Facebook/Zalo) một cách tự động.

Cấu trúc HTML Semantic giúp bot tìm kiếm (Google, Bing) dễ dàng lập chỉ mục.

3. Sẵn sàng cho Hiệu năng (Performance)
   React Compiler (Optional): Cấu hình sẵn flag thực nghiệm để tối ưu hóa re-render tự động.

Image Optimization: Sử dụng Next.js Image component để tự động resize và lazy load ảnh.

Icon Library: Tích hợp Lucide React - bộ icon nhẹ, đồng bộ và dễ sử dụng.

4. Cấu trúc Thư mục Chuẩn (Scalable Structure)
   Plaintext
   src/
   ├── app/ # Routes, Layouts và Pages (App Router)
   ├── components/  
   │ ├── ui/ # Shadcn/ui components (Atomic)
   │ └── shared/ # Components dùng chung (Header, Footer, Navbar)
   ├── config/ # Cấu hình site, SEO, navigation
   ├── lib/ # Utils, API clients, constants
   └── types/ # TypeScript interfaces/types
   🚀 Bắt đầu nhanh
1. Sử dụng Template
   Nhấn nút "Use this template" trên GitHub để tạo Repo mới từ bộ khung này.

1. Cài đặt môi trường
   Bash
   npm install

# hoặc

yarn install 3. Chạy Development Server
Bash
npm run dev
Mở http://localhost:3000 trên trình duyệt để xem thành quả.

💡 Lộ trình phát triển sản phẩm (Tips)
Landing Page: Tập trung vào các Section trong src/components/shared để tái sử dụng cho nhiều dự án.

SEO: Luôn cập nhật thông tin trong src/config/site.ts trước khi deploy dự án mới.

UI: Sử dụng lệnh npx shadcn-ui@latest add [component-name] để bổ sung thêm các thành phần khi cần thiết.
