# Mẫu Tiểu Luận UEH

Đây là mẫu tiểu luận dành cho sinh viên Đại học Kinh tế TP. Hồ Chí Minh (UEH), hỗ trợ trình bày bài tiểu luận theo chuẩn UEH với trang bìa, cấu trúc chương, và trích dẫn tài liệu tham khảo theo chuẩn APA.

## Cấu trúc thư mục

- `main.tex`: File LaTeX chính, quản lý toàn bộ cấu trúc bài tiểu luận.
- `ueh/cover.tex`: Trang bìa UEH, thiết kế bằng TikZ.
- `chapters/`: Thư mục chứa các chương nội dung (`chapter1.tex`, `chapter2.tex`, ...).
- `references.bib`: File chứa các tài liệu tham khảo theo định dạng BibTeX.
- `vietnamese.lbx`, `vietnamese-apa.lbx`: Hỗ trợ hiển thị tiếng Việt cho các trường và định dạng APA trong mục tài liệu tham khảo.

## Hướng dẫn sử dụng

1. **Có thể sử dụng trực tiếp trên Overleaf** (không cần cài đặt TeX Live thủ công).
2. **Biên dịch tài liệu** theo trình tự:
   - Chạy `pdflatex main.tex`
   - Chạy `biber main`
   - Chạy lại `pdflatex main.tex` (2 lần)
3. **Chỉnh sửa thông tin cá nhân, môn học, giảng viên** trong `ueh/cover.tex`.
4. **Thêm nội dung các chương** vào các file trong thư mục `chapters/`.
5. **Thêm tài liệu tham khảo** vào `references.bib` theo chuẩn BibTeX.

## Tính năng nổi bật
- Trang bìa UEH hiện đại, đúng chuẩn.
- Hỗ trợ tiếng Việt cho toàn bộ tài liệu và mục tài liệu tham khảo.
- Trích dẫn và hiển thị tài liệu tham khảo theo chuẩn APA.
- Dễ dàng chỉnh sửa thông tin cá nhân và nội dung các chương.

## Đóng góp
Nếu bạn có ý tưởng cải tiến hoặc phát hiện lỗi, vui lòng tạo issue hoặc gửi pull request.

---

**Liên hệ:**
- Github: [vanlocvo](https://github.com/vanlocvo)

