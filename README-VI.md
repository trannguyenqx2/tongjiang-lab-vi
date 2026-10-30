# Tongjiang Lab — Bản Việt hóa (54 bài học khoa học 3D)

Bản Việt hóa tiếng Việt của **Tongjiang Lab** — kho bài học khoa học 3D tương tác miễn phí cho học sinh THPT, gồm 54 bài: Vật lý (10), Hóa học (25), Sinh học (5), Địa lý (14).

## Cách mở và sử dụng

1. Giải nén file `tongjiang-lab-vi.zip` vào một thư mục bất kỳ trên máy.
2. Mở file **`index.html`** (ở thư mục gốc sau khi giải nén) bằng trình duyệt **Chrome** hoặc **Edge** — nhấp đúp chuột hoặc kéo thả file vào cửa sổ trình duyệt.
3. Dùng ô tìm kiếm và các nút lọc theo môn (Tất cả / Vật lý / Hóa học / Sinh học / Địa lý) để tìm bài, bấm **▶ Mở bài** để vào bài học tương tác. Trong trang mục lục, bấm vào tên bài/mục bước để xem danh sách các bước học tiếng Việt của từng bài.
4. **Chạy offline hoàn toàn:** gói này không cần Internet, không cần cài thêm phần mềm hay máy chủ. Mỗi bài học là một file HTML tự chứa, mở trực tiếp từ ổ đĩa, dùng tốt trên máy chiếu và bảng tương tác.

## Cấu trúc thư mục

```text
tongjiang-lab-vi/
├── index.html        ← Trang mục lục tiếng Việt (tìm kiếm + lọc theo môn + 54 bài)
├── README-VI.md      ← File này
└── courses/          ← 54 bài học 3D đã Việt hóa (mỗi bài 1 file .html)
    ├── haber-step.html
    ├── river-step.html
    └── … (54 file)
```

## Nguồn và giấy phép

- Nguồn gốc: repo **smithjohn78390/tongjiang-lab** (Release v2026.10.28), trang gốc của tác giả: Tongjiang Lab.
- Tác giả: **Tongjiang**.
- Giấy phép: **CC BY-NC 4.0** — được phép sử dụng, chia sẻ và chuyển thể cho mục đích **phi thương mại**, với điều kiện ghi nguồn “Tongjiang Lab”. Bản Việt hóa này là bản chuyển thể (dịch) theo cùng giấy phép.
- Các bài học bám sát chuẩn chương trình THPT và vị trí trong sách giáo khoa **PEP 2019** (Nhà xuất bản Giáo dục Nhân dân, Trung Quốc) như ghi trong mục lục; không liên kết với Nhà xuất bản Giáo dục Nhân dân.
- Mã bên thứ ba đi kèm trong các bài học (three.js, giấy phép MIT) giữ nguyên giấy phép riêng của chúng.

## Ghi chú kỹ thuật về bản dịch

- Toàn bộ giao diện và nội dung hiển thị của 54 bài học đã được dịch sang tiếng Việt và đã kiểm chứng tự động (54/54 file đạt).
- Có **9 đoạn mã rất dài thuộc CSS/GLSL** (shader/hiệu ứng 3D) mà chữ tiếng Trung chỉ xuất hiện trong **comment của mã nguồn** — phần người học **không bao giờ nhìn thấy** trên giao diện. Các đoạn này được giữ nguyên có chủ đích để tránh làm hỏng hiệu ứng 3D; chúng không ảnh hưởng gì đến trải nghiệm học tập.
