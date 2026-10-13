# TĐKT Web v1.5.3 — bản HTML tĩnh GitHub Pages

Bản này chạy **100% bằng HTML/CSS/JavaScript trong trình duyệt**.

- Không cần Python.
- Không cần FastAPI.
- Không cần cài đặt phần mềm trên máy người dùng.
- Có thể đưa thẳng lên GitHub Pages.
- Dữ liệu nghiệp vụ được lưu bằng `localStorage` trên từng trình duyệt.

## Lưu ý quan trọng

GitHub Pages là website tĩnh. Vì vậy dữ liệu **không tự đồng bộ giữa các máy/người dùng**. Mỗi trình duyệt có một bộ dữ liệu riêng.

Để chuyển dữ liệu hoặc chống mất dữ liệu:

1. Vào **Quản trị** → **Tải tệp sao lưu JSON**.
2. Trên máy khác, vào **Quản trị** → chọn tệp JSON → **Khôi phục dữ liệu**.

Không đưa dữ liệu hồ sơ cá nhân thật vào chính repository GitHub. Dữ liệu người dùng chỉ nên nằm trong localStorage của trình duyệt và trong tệp sao lưu do người sử dụng tự quản lý.

## Đăng nhập mặc định

- Tên đăng nhập: `admin`
- Mật khẩu: `Tdk@2026!`

Đây chỉ là lớp đăng nhập cục bộ để giữ trải nghiệm sử dụng, **không phải cơ chế bảo mật máy chủ**.

## Đưa lên GitHub Pages

Xem file `HUONG_DAN_DUA_LEN_GITHUB_PAGES.html`.
