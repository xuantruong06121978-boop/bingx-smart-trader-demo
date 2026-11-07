BINGX SMART TRADER — BẢN DEMO/PAPER TRADING

CÓ GÌ
- Giao diện tiếng Việt, thiết kế cho màn hình điện thoại Android.
- Lấy dữ liệu công khai thị trường hợp đồng USDT-M BingX.
- EMA 9/21, RSI 14, MACD 12/26/9 và ATR tham khảo.
- Mô phỏng LONG/SHORT bằng số dư ảo 1.000 USDT.
- Ký quỹ mô phỏng 100 USDT/lệnh, đòn bẩy mô phỏng 3x.
- TP +3% và SL -1% tính trên ký quỹ mô phỏng; tối đa 5 vị thế.
- BOT quét tín hiệu 60 giây/lần; cập nhật giá 5 giây/lần.
- Lỗ mô phỏng trong ngày chạm 30 USDT thì BOT dừng mở lệnh mới.
- Số dư/lịch sử lưu trên trình duyệt của thiết bị (localStorage).

GIỚI HẠN QUAN TRỌNG
- Đây KHÔNG phải APK và không phải app giao dịch chính thức của BingX.
- Đây là mô phỏng phía trình duyệt, không gửi lệnh tới BingX và không dùng VST của BingX.
- Chưa tính phí, funding, trượt giá, thanh lý; kết quả mô phỏng không đại diện kết quả thực.
- Cần kết nối Internet và trình duyệt cho phép gọi API công khai BingX.
- Dữ liệu/ứng dụng không được đảm bảo chạy nền khi Android đóng hoặc tiết kiệm pin.
- Không nhập API key, mật khẩu hoặc mã OTP vào bản này.

CÁCH MỞ THỬ
1. Giải nén ZIP.
2. Mở index.html bằng Chrome trên máy tính hoặc trình duyệt hỗ trợ file HTML.
3. Nếu mở file trực tiếp mà trình duyệt chặn API, cần đưa thư mục lên một máy chủ HTTPS tĩnh (ví dụ GitHub Pages) rồi mở đường dẫn HTTPS.
4. Trên Samsung, mở trang HTTPS bằng Chrome > menu ⋮ > Cài đặt ứng dụng / Thêm vào màn hình chính (tên mục tùy phiên bản Chrome).

LƯU Ý PWA
Service worker và cài đặt dạng ứng dụng yêu cầu HTTPS hoặc localhost. Không thể cài PWA trực tiếp chỉ bằng cách mở file ZIP.
