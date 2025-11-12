# Auto Whisk - Tự động hóa Prompt cho Whisk [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 

Tiện ích mở rộng Chrome giúp tự động hóa toàn bộ quy trình làm việc của bạn với Whisk (trên `labs.google`). Tự động gửi hàng loạt prompt, tiết kiệm thời gian, tăng tốc sáng tạo và kiểm soát toàn diện quy trình của bạn!

[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/auto-whisk-prompt-automat/gedfnhdibkfgacmkbjgpfjihacalnlpn)

## Tính năng chính

* **Gửi Prompt hàng loạt:** Nhập danh sách prompt trực tiếp hoặc tải lên từ tệp `.txt`.
* **Tự động tải ảnh:** Tự động quét và tải xuống các ảnh được tạo ra vào thư mục bạn chỉ định.
* **Điều khiển linh hoạt:** Bắt đầu, Tạm dừng, Tiếp tục, và Dừng (Pause/Resume/Stop) quy trình bất cứ lúc nào.
* **Hai chế độ bắt đầu:**
    * `Tạo dự án mới`: Tự động điều hướng và tạo một project Whisk mới.
    * `Chạy luôn tại đây`: Bắt đầu tự động trên project Whisk bạn đang mở.
* **Tùy chỉnh nâng cao:**
    * Thiết lập thời gian chờ (cố định hoặc ngẫu nhiên) giữa các prompt để quản lý tốc độ.
    * Thiết lập số lần lặp lại cho *mỗi* prompt trong danh sách.
    * Bắt đầu từ một prompt cụ thể (ví dụ: bắt đầu từ prompt số 50).
* **Xử lý lỗi thông minh:** Tự động phát hiện khi Whisk bị quá tải (hàng chờ đầy), tự động chờ, thử lại và thậm chí tự động làm mới (refresh) trang để đảm bảo quy trình tiếp tục.
* **Lịch sử & Log:** Theo dõi tiến trình chi tiết trong tab "Lịch Sử" và dễ dàng sao chép lại các prompt bị lỗi.

## Hướng dẫn sử dụng

1.  Cài đặt tiện ích từ Chrome Web Store.
2.  Truy cập trang [Whisk của Google Labs](https://labs.google/fx/tools/whisk).
3.  Nhấp vào biểu tượng tiện ích (hình con vịt) trên thanh công cụ của Chrome để mở bảng điều khiển (Side Panel).
4.  **Tab "Điều Khiển":**
    * Dán danh sách prompt của bạn vào ô (mỗi prompt một dòng).
    * Hoặc, nhấp vào "Nhập từ file" để tải prompt từ tệp `.txt`.
5.  **Tab "Cài Đặt":**
    * Bật **"Tự động tải ảnh"** và đặt tên **"Thư mục tải về"** (ví dụ: `Whisk Downloads`).
    * Thiết lập **Thời gian chờ** (ví dụ: 10-20 giây) để Whisk có thời gian tạo ảnh.
    * Đặt **"Thực thi mỗi prompt"** nếu bạn muốn mỗi prompt chạy nhiều lần.
6.  **Quay lại Tab "Điều Khiển":**
    * Nhấn nút **"Bắt đầu"**.
    * Bạn sẽ thấy hai lựa chọn: "Tạo dự án mới" hoặc "Chạy luôn tại đây". Chọn một chế độ.
    * Tool sẽ bắt đầu chạy.

## Lưu ý quan trọng

* **Luôn mở Panel:** Luôn mở tab Whisk và bảng điều khiển (Side Panel) của tiện ích khi tool đang chạy.
* **Dùng cửa sổ riêng:** Để tool chạy ổn định nhất, hãy chạy trong một cửa sổ trình duyệt riêng.
* **Tắt hỏi khi tải:** Nếu bật "Tự động tải ảnh", hãy vào cài đặt tải về của trình duyệt (`chrome://settings/downloads`) và tắt **"Hỏi vị trí lưu..."** để không bị làm phiền.
