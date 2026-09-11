# App tính điện nước

App web/PWA tối ưu cho điện thoại, giao diện mô phỏng bảng Excel `tính điện nước 1.xlsx`.

## Công thức đã giữ nguyên
- C4 = ((C3 - (C2 / 100)) * 100)
- D4 = ((D3 - (D2 / 100)) * 100)
- B5 = B3 - B2
- C5 = C4 - C2
- D5 = D4 - D2
- E5 = B5 - (C5 + D5)

## Chạy
Mở `index.html` trên trình duyệt.

Để cài như app trên điện thoại, đưa thư mục này lên một hosting có HTTPS (GitHub Pages, Netlify, Vercel...) rồi mở bằng Chrome/Safari và chọn "Thêm vào màn hình chính".

Dữ liệu đang nhập được lưu cục bộ trong trình duyệt bằng localStorage.
