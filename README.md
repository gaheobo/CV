# Portfolio CV - Nguyễn Đào Hoàng Đức

Trang portfolio cá nhân giới thiệu Nguyễn Đào Hoàng Đức với vai trò Frontend Developer. Dự án được xây dựng dưới dạng website tĩnh, trình bày thông tin cá nhân, kỹ năng, các dự án tiêu biểu và kênh liên hệ.

## Mô tả

Giao diện được thiết kế theo hướng mobile-first, sử dụng HTML ngữ nghĩa và CSS để hiển thị phù hợp trên điện thoại, máy tính bảng và máy tính. Các mục điều hướng dẫn tới từng phần ngay trên trang; không cần máy chủ backend để xem nội dung.

## Chức năng

- Giới thiệu cá nhân và định hướng nghề nghiệp.
- Hiển thị các kỹ năng và công nghệ.
- Trình bày danh sách dự án dưới dạng thẻ.
- Điều hướng tới các phần Giới thiệu, Kỹ năng, Dự án và Liên hệ.
- Cung cấp thông tin liên hệ và liên kết quay lại đầu trang.
- Bố cục responsive, hỗ trợ nhiều kích thước màn hình.

> Lưu ý: Các thẻ dự án hiện chỉ trình bày nội dung minh họa; nút “Xem chi tiết” chưa được nối tới trang dự án. Portfolio không có JavaScript hoặc backend.

## Công nghệ

- HTML5: cấu trúc và nội dung trang.
- CSS3: giao diện, Flexbox, CSS Grid, biến CSS và responsive design.
- Git/GitHub: quản lý mã nguồn (nếu sử dụng).

## Cấu trúc thư mục

```text
.
├── index.html
├── README.md
└── assets/
	 ├── css/
	 │   └── styles.css
	 └── img/
		  ├── anhdaidien.png
		  ├── Project1.png
		  ├── Project2.png
		  └── Project4.png
```

## Yêu cầu môi trường

- Windows, macOS hoặc Linux.
- Trình duyệt hiện đại như Chrome, Firefox, Edge hoặc Safari.
- Trình soạn thảo mã nguồn (không bắt buộc), ví dụ Visual Studio Code.
- Không cần cài Node.js, package hoặc cơ sở dữ liệu để xem website.
- Python 3 chỉ cần thiết nếu muốn chạy máy chủ HTTP cục bộ theo hướng dẫn bên dưới.

## Cài đặt

### Windows

1. Tải hoặc clone mã nguồn về máy. Nếu đã cài Git, mở PowerShell hoặc Windows Terminal và chạy:

	```powershell
	git clone <URL-kho-ma-nguon>
	cd <ten-thu-muc-du-an>
	```

	Nếu tải file ZIP, giải nén vào thư mục mong muốn rồi mở PowerShell tại thư mục đó.
2. Mở `index.html` bằng trình duyệt để xem trực tiếp, hoặc chạy máy chủ cục bộ:

	```powershell
	py -m http.server 8000
	```

	Nếu lệnh `py` không có nhưng đã cài Python, thử `python -m http.server 8000`.

### macOS

1. Mở Terminal, clone kho mã nguồn và chuyển vào thư mục dự án:

	```bash
	git clone <URL-kho-ma-nguon>
	cd <ten-thu-muc-du-an>
	```

	Hoặc tải file ZIP và giải nén.
2. Mở `index.html` bằng trình duyệt, hoặc chạy máy chủ cục bộ:

	```bash
	python3 -m http.server 8000
	```

### Linux

1. Mở Terminal, clone kho mã nguồn và chuyển vào thư mục dự án:

	```bash
	git clone <URL-kho-ma-nguon>
	cd <ten-thu-muc-du-an>
	```

	Hoặc tải file ZIP và giải nén bằng trình quản lý tệp.
2. Mở `index.html` bằng trình duyệt, hoặc chạy máy chủ cục bộ:

	```bash
	python3 -m http.server 8000
	```

## Cấu hình

Dự án không có bước cấu hình môi trường hay file `.env`. Có thể tùy chỉnh nội dung trực tiếp trong `index.html` và giao diện trong `assets/css/styles.css`.

- Thay ảnh trong `assets/img/` và cập nhật đường dẫn `src` tương ứng trong HTML.
- Cập nhật email, GitHub, LinkedIn và các liên kết dự án trong phần Liên hệ/thẻ dự án. Một số liên kết trong mã nguồn hiện là placeholder (`#`) hoặc địa chỉ mẫu.
- Có thể điều chỉnh màu sắc, font chữ, khoảng cách và kích thước trong nhóm biến CSS `:root` của `assets/css/styles.css`.

## Chạy thử

Nếu đã khởi chạy máy chủ HTTP ở bước cài đặt, mở địa chỉ sau trong trình duyệt:

```text
http://localhost:8000
```

Để dừng máy chủ, quay lại cửa sổ Terminal/PowerShell và nhấn `Ctrl+C`. Nếu mở trực tiếp `index.html`, không cần chạy hoặc dừng máy chủ.

## Thông tin liên hệ

- **Tác giả:** Nguyễn Đào Hoàng Đức
- **Email:** [nguyendaohoangduc@example.com](mailto:nguyendaohoangduc@example.com) (địa chỉ mẫu, cần thay bằng email sử dụng thực tế nếu cần)
- **GitHub:** [github.com/gaheobo](https://github.com/gaheobo)
- **LinkedIn:** liên kết hồ sơ hiện được khai báo trong `index.html`; hãy kiểm tra và cập nhật URL hồ sơ trước khi phát hành.

## Giấy phép

Chưa khai báo giấy phép sử dụng. Hãy bổ sung giấy phép phù hợp nếu muốn cho phép người khác sử dụng hoặc phân phối mã nguồn.
