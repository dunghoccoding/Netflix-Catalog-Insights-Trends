# 🎬 Netflix Catalog & Content Strategy Analysis

Dự án phân tích khám phá dữ liệu (EDA) và trực quan hóa thông tin danh mục phim của Netflix với hơn 8.700 tác phẩm. Dự án nhằm mục đích bóc tách cơ cấu nội dung, mức độ phủ sóng địa lý, tính mùa vụ và xu hướng phát hành để đề xuất chiến lược tối ưu hóa ngân sách mua bản quyền nội dung (Content Acquisition).

---

## 📌 Executive Summary (Tóm tắt cốt lõi)

* **Cơ cấu danh mục:** Phim lẻ (Movies) chiếm tỷ trọng áp đảo **69.7%** (6.129 tác phẩm), trong khi Phim bộ (TV Shows) chiếm **30.3%** (2.664 tác phẩm). Đáng chú ý, **67.2%** các TV Show dừng lại ở mùa phát hành đầu tiên (Season 1).
* **Chiến lược địa phương hóa:**
  * **Ấn Độ:** Tập trung mạnh vào điện ảnh với **92.0%** là Movie, phản ánh văn hóa tiêu thụ điện ảnh Bollywood.
  * **Hàn Quốc & Nhật Bản:** Đảo chiều ưu tiên sang Phim bộ (TV Shows) với tỷ lệ lần lượt là **73.6%** và **62.3%** (K-Dramas và Anime), đóng vai trò then chốt trong việc giữ chân thuê bao.
* **Độ trễ phát hành (Content Freshness):** **55.0%** nội dung được phát hành trên Netflix trong vòng chưa đầy 1 năm kể từ thời điểm sản xuất (trong đó **36.9%** lên sóng ngay trong năm ra mắt).
* **Tính mùa vụ:** Lưu lượng phát hành nội dung mới đạt đỉnh vào **Tháng 7** (827 phim) và **Tháng 12** (812 phim), đón đầu các kỳ nghỉ hè và nghỉ lễ dài ngày của khán giả.
* **Phân loại độ tuổi:** Nhãn **TV-MA** (người trưởng thành) và **TV-14** chiếm ưu thế lớn nhất trong toàn bộ thư viện.

---

## 🛠 Tech Stack & Tools

* **Ngôn ngữ & Môi trường:** Python 3.x, Jupyter Notebook.
* **Thư viện phân tích:** Pandas, NumPy.
* **Thư viện trực quan hóa:** Matplotlib, Seaborn.
* **Công cụ BI & Dashboard:** Microsoft Power BI Desktop.

---

## 📂 Cấu trúc thư mục dự án

```text
├── data/
│   ├── netflix_titles.csv               # Dữ liệu gốc
│   └── netflix_titles_final_clean_2.csv # Dữ liệu sạch sau tiền xử lý
├── notebooks/
│   └── EDA_Anal.ipynb                   # Luồng tiền xử lý và EDA chi tiết
├── dashboard/
│   ├── dashboard.pbix                   # File thiết kế Power BI
│   
├── docs/
│   └── KhaoSat.docx                     # Tài liệu khảo sát và báo cáo dự án
└── README.md
