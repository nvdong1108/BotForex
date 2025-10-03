# 🎯 Khóa học Code Bot trên MetaTrader 5 (MQL5)
## I. Mục tiêu Khóa học
Sau khi hoàn thành khóa học, học viên sẽ:

Nắm vững kiến thức nền tảng về Ngôn ngữ lập trình MQL5 và môi trường phát triển (MetaEditor).

Thành thạo việc tạo, chỉnh sửa, debug (sửa lỗi), và tối ưu một Expert Advisor (EA)/Bot từ ý tưởng ban đầu đến sản phẩm chạy được.

Hiểu rõ các chiến thuật giao dịch phổ biến (DCA, Hedging, Bot theo chỉ báo) và biết cách lập trình chúng vào bot.

Triển khai bot giao dịch tự động trên môi trường thực tế (VPS).

## II. Kết quả Đạt được
Học viên có khả năng:

Tự tạo một Bot giao dịch (EA) hoàn chỉnh dựa trên ý tưởng và chiến thuật cá nhân (Dự án Cá nhân).

Sử dụng hiệu quả các công cụ AI (Chatbot/Copilot) để hỗ trợ viết code, tìm lỗi và tối ưu hóa mã nguồn MQL5.

Vận hành và quản lý Bot trên nền tảng MT5 và máy chủ ảo (VPS) một cách an toàn.

Phân tích chuyên sâu ưu, nhược điểm và ứng dụng của các chiến thuật Bot sau:

DCA:  Phân tích DCA Âm, DCA Dương, Tỉa lệnh.

Hedging: Chiến thuật phòng hộ cơ bản đến nâng cao.

Bot theo Chỉ báo: Lập trình bot giao dịch theo các chỉ báo kỹ thuật phổ biến.

Tích hợp (Tín hiệu): Tạo bot/script để gửi tín hiệu giao dịch đến nền tảng khác (ví dụ: Telegram).

Backtest và tối ưu hiệu suất của bot trước khi triển khai thực tế.


# 📚 Nội dung Chi tiết theo Module học.
## 📌 Module 1: Thiết lập Môi trường

1. Cài đặt & Thiết lập MT5
    - Tải & Cài đặt: Ưu tiên từ website chính thức hoặc sàn giao dịch uy tín (Link MT5, [Link Sàn Mẫu]). 
    - Giao diện: Tổng quan về MT5, Market Watch, Navigator, Terminal. - Login: Đăng nhập tài khoản Demo/Real.

2. Giới thiệu MetaEditor & Cấu trúc Bot	
    - Mở MetaEditor (IDE của MQL5). 
    - Cấu trúc cơ bản của một EA (OnInit(), OnDeinit(), OnTick(), OnTimer()). 
    - Cơ bản MQL5 (Phần 1): Kiểu dữ liệu, Biến, Hàm Print() để Debug.

3. Bot Đầu Tiên & Thực hành Debug	
    - Tạo dự án EA đầu tiên: "Hello World Bot". 
    - Thêm bot vào chart & Chạy thử. 
    - Sử dụng History (Lịch sử giao dịch): Kiểm tra lệnh vào ra. 
    - Compile Code và xem các loại lỗi (Errors/Warnings).

4. Tận dụng AI (Thực hành)	
    - Nhờ AI: Tạo một đoạn code MQL5 đơn giản (ví dụ: bot Buy 1 lệnh khi mở). 
    - Sửa lỗi: Thực hành tìm và sửa lỗi cú pháp do AI hoặc tự viết.

## 📌 Module 2: Nền tảng Lập trình MQL5 Chuyên sâu

1. Lập trình MQL5 (Phần 2)	
    - Cú pháp: Câu lệnh điều kiện (if/else), Vòng lặp (for, while). 
    - Hàm nhập liệu: Sử dụng biến Input để tùy chỉnh bot dễ dàng (Parameters). 
    - Hàm thời gian & Event: OnTimer(), Sleep(), Time/Date functions.
2. Thao tác Lệnh Giao dịch (Core Functions)	
    - Hàm Order Send: Mở lệnh (Buy/Sell) với SL, TP. 
    - Hàm Order Modify: Chỉnh sửa lệnh đang có. 
    - Hàm Order Close: Đóng lệnh. 
    - Hàm Order Select: Quản lý và duyệt qua các lệnh hiện tại.
3. Lấy dữ liệu Thị trường	
    - Giá: SymbolInfoDouble(), SymbolInfoInteger() (Bid/Ask, Spread, Point, Digits...). 
    - Thanh nến: Sử dụng Arrays và CopyRates()/CopyBuffer() để lấy dữ liệu nến và chỉ báo.
4. Tư duy Lập trình Bot	
    - Tư duy Modular: Chia code thành các hàm nhỏ, dễ quản lý. 
    - Quản lý rủi ro (Cơ bản): Tính toán Lot size cơ bản.

## 📌 Module 3: Lập trình Bot Chiến thuật và Backtest

1. Lập trình Bot theo Chỉ báo	
    - Tạo chỉ báo: Hàm iMA(), iRSI(), iMACD(). 
    - Thực hành: Tạo Bot giao dịch Demo theo chiến thuật Cắt ngang (Moving Average Cross-over) hoặc RSI quá mua/quá bán.
2. Chiến thuật Đặc biệt (Phần 1)	
    - Chiến thuật DCA (Dollar-Cost Averaging): Phân tích và Code hóa một phiên bản DCA cơ bản.
3. Backtest và Tối ưu	
    - Hướng dẫn Backtest chuyên sâu: Sử dụng Strategy Tester của MT5. 
    - Phân tích kết quả: Hiểu các thông số (Profit Factor, Drawdown, Max. Cons. Losses). 
    - Tối ưu hóa (Optimization): Chạy thử nghiệm với các thông số Input khác nhau.
4. Triển khai Thực tế	
    - Hướng dẫn tạo & sử dụng VPS (Virtual Private Server) với tài khoản Demo/Small Real. 
    - Cách quản lý bot khi chạy trên VPS (theo dõi Log, khởi động lại).

## 📌 Module 4: Phân tích Chiến thuật Chuyên sâu và Bot Ứng dụng

1. Phân tích & Code hóa Chiến thuật Chuyên sâu	
    - Chiến thuật Hedging: Lập trình bot đóng mở lệnh đối ứng (tách biệt/cùng cặp). 
    - Phân tích DCA Nâng cao: DCA Âm, DCA Dương, Bot Tỉa lệnh (Grid Trading). 
    - Thảo luận: Ưu điểm/Nhược điểm và kịch bản áp dụng từng loại chiến thuật.
2. Bot Ứng dụng & Mở rộng	
    - Tạo Script: Code script để Gửi tín hiệu giao dịch (Entry/SL/TP) ra ngoài (ví dụ: ghi vào file, sẵn sàng cho việc gửi Telegram). 
    - Giới thiệu Bot Phổ biến: 
    Phân tích mã nguồn/nguyên lý hoạt động của một số bot phổ biến trên thị trường (chỉ mang tính chất tham khảo chiến thuật).
3. Dự án Cá nhân	
    - Ôn tập & Hỏi đáp toàn bộ kiến thức. 
    - Định hướng phát triển cho Dự án Bot Cá nhân (Tối ưu, kết hợp chỉ báo, quản lý vốn).
