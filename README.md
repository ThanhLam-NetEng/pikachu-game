# Pikachu Game

Game nối hình Pikachu đơn giản dành cho web, tối ưu cho cả desktop và điện thoại.

## Tính năng

- 5 màn chơi tăng dần
- Nối 2 ô giống nhau với tối đa 2 lần gấp khúc
- Gợi ý mất 20 điểm
- Xáo bài khi bí
- Đồng hồ đếm ngược
- Kỷ lục lưu trên `localStorage`
- Chế độ ban đêm
- Bật/tắt âm thanh
- Responsive cho điện thoại

## Cách chơi

1. Nhấn `Bắt đầu`
2. Chạm vào 2 ô cùng Pokémon để nối
3. Nếu không có đường đi thì dùng `Xáo bài`
4. Màn xong khi hết toàn bộ ô

## Màn chơi

Hiện tại game có 5 màn:

- Màn 1: 6 x 8, 12 loại Pokémon
- Màn 2: 8 x 8, 16 loại Pokémon
- Màn 3: 8 x 10, 20 loại Pokémon
- Màn 4: 8 x 10, 20 loại Pokémon
- Màn 5: 10 x 10, 20 loại Pokémon

## Cài đặt & chạy

1. Clone repo:
   ```bash
   git clone https://github.com/ThanhLam-NetEng/pikachu-game.git
   ```
2. Mở `index.html` bằng trình duyệt hoặc dùng server tĩnh:
   ```bash
   npx http-server .
   ```

## GitHub Pages

Để chia sẻ trên GitHub Pages, bật Pages trong `Settings > Pages` và chọn branch `main` với thư mục root. Sau khi bật, trang sẽ có thể truy cập tại:

`https://ThanhLam-NetEng.github.io/pikachu-game/`

> Nếu muốn, tôi có thể giúp bạn tạo sẵn `gh-pages` branch hoặc cấu hình action tự động deploy.

## Ghi chú

- Âm thanh có thể cần cho phép trong trình duyệt lần đầu
- Chế độ ban đêm lưu lại trên trình duyệt
- Game đã tối ưu cho cả chạm và click
