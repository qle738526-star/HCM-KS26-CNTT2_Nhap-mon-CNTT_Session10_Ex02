# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session10_Ex02

## Phần 1: Phân tích (I/O)
*   **Input:** Văn bản thô nhập từ bàn phím (chữ thuần túy).
*   **Output:** Giao diện trực quan (code được tô màu, bảng biểu chia cột ngay ngắn, danh sách có ô tick chọn).

## Phần 2: Mã nguồn Markdown (Source Code)

Dưới đây là nội dung file `.md` đáp ứng đủ yêu cầu:

# Hướng dẫn cài đặt cảm biến

\* Lưu ý: Cẩn thận không làm chập chân \#5.

## 1. So sánh thiết bị

| Tiêu chí | Cảm biến cũ | Cảm biến mới |
| :--- | :--- | :--- |
| **Độ chính xác** | Thấp | Cao |

## 2. Chuẩn bị (Task List)

- [x] Tắt nguồn điện.
- [ ] Mở Terminal, chạy lệnh `pip install adafruit-dht` để cài thư viện.

## 3. Code điều khiển máy bơm

```python
humidity = 55.0
if humidity < 60.0:
    print("Độ ẩm thấp -> Bật máy bơm!")
else:
    print("Độ ẩm ổn định.")
