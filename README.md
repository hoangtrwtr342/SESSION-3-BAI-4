HỌ VÀ TÊN : BÙI MINH HOÀNG

LỚP :HCM-CNTT 1

SESSION 3 BÀI 4


PHẦN 1: PHÂN TÍCH NGUYÊN NHÂN LAG & MÔ HÌNH BÀN LÀM VIỆC / NGĂN TỦ

1. Chẩn đoán Task Manager (%RAM và %CPU)

%RAM báo đỏ (95–100%): Mở 20 tab Chrome + VS Code đã "ăn trọn" 8GB RAM. Khi RAM cạn kiệt, hệ điều hành phải dùng đến Swap file (mượn tạm ổ cứng SSD làm bộ nhớ tạm). Do tốc độ SSD chậm hơn RAM hàng chục lần nên máy tính bị "khựng/đứng hình".

%CPU tăng cao: CPU bị quá tải vì phải liên tục điều phối việc chuyển dữ liệu qua lại giữa ổ cứng và RAM.

  
2. Phân biệt RAM (Bàn làm việc) và Storage (Ngăn tủ)

Storage / Ổ cứng (Ngăn tủ chứa đồ): Dùng để lưu trữ lâu dài (tắt máy không mất). Ngăn tủ rất to (256GB) nhưng mỗi lần mở tủ lấy tài liệu ra thì chậm.

RAM (Mặt bàn làm việc): Dùng để chứa những thứ đang làm dở (tắt máy là mất). Mặt bàn có diện tích nhỏ (8GB) nhưng lấy đồ cực nhanh. Mở 20 tab Chrome giống như bày quá nhiều sách vở lên mặt bàn làm chật cứng, không còn chỗ để mở file code ra viết tiếp.

PHẦN 2: THIẾT KẾ CÂY THƯ MỤC TRÊN Ổ D:

Cấu trúc thư mục chuẩn (Dùng chuẩn kebab-case: chữ thường, không dấu, nối bằng dấu -):

Ổ đĩa D:

ptit-projects (Thư mục gốc chứa các môn học ở trường)

  python-first-app (Thư mục dự án ứng dụng Python)

    docs (Trụ cột 1: Chứa tài liệu, báo cáo đề tài)

      project-report.docx
      
src (Trụ cột 2: Chứa mã nguồn code Python chính)

  main.py
  
assets (Trụ cột 3: Chứa hình ảnh, logo, icon)

  app-logo.png
  
data (Trụ cột 4: Chứa dữ liệu đầu vào)

  input-data.cs
