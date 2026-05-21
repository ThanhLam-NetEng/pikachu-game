# Pikachu Game

Game nối hình Pikachu đơn giản dành cho web, tối ưu cho cả desktop và điện thoại.

## Tính năng

- Chế độ `Dễ` với ô lớn, ít ô hơn, phù hợp cho người lớn tuổi chơi trên điện thoại
- Chế độ `Thường` cho màn hình lớn hoặc người muốn thử thách hơn
- Nối 2 ô giống nhau với tối đa 2 lần gấp khúc
- Gợi ý mất 20 điểm
- Xáo bài khi bí
- Đồng hồ đếm ngược
- Kỷ lục và cài đặt lưu trên `localStorage`
- Chế độ ban đêm
- Bật/tắt âm thanh
- Responsive cho điện thoại

## Cách chơi

1. Chọn `Dễ` hoặc `Thường`
2. Nhấn `Bắt đầu`
3. Chạm vào 2 ô cùng Pokémon để nối
4. Nếu không có đường đi thì dùng `Xáo bài`
5. Màn xong khi hết toàn bộ ô

## Màn chơi

Chế độ `Dễ` có 5 màn, tối đa 6 x 8 để ô luôn dễ nhìn trên điện thoại:

- Màn 1: 4 x 4, 8 loại Pokémon
- Màn 2: 4 x 6, 6 loại Pokémon
- Màn 3: 5 x 6, 5 loại Pokémon
- Màn 4: 6 x 6, 9 loại Pokémon
- Màn 5: 6 x 8, 12 loại Pokémon

Chế độ `Thường` có 5 màn:

- Màn 1: 6 x 8, 12 loại Pokémon
- Màn 2: 6 x 10, 10 loại Pokémon
- Màn 3: 8 x 8, 16 loại Pokémon
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

## Ghi chú

- Âm thanh có thể cần cho phép trong trình duyệt lần đầu
- Chế độ ban đêm và chế độ chơi được lưu lại trên trình duyệt
- Game đã tối ưu cho cả chạm và click
