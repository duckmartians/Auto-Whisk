### **Hướng Dẫn Sử Dụng FlowMate Chi Tiết Cho Người Mới Bắt Đầu**

Chào mừng bạn đến với FlowMate\! Tiện ích này là trợ lý đắc lực giúp bạn tự động hóa hoàn toàn công việc tạo video hàng loạt trên Google Flow, tiết kiệm hàng giờ làm việc thủ công. Hãy cùng bắt đầu\!

-----

### **Phần 1: Cài Đặt Tiện Ích**

Để sử dụng, trước tiên bạn cần thêm FlowMate vào trình duyệt của mình.

1.  **Mở Trình duyệt:** Mở trình duyệt Google Chrome.

2.  **Truy cập Trang Cài Đặt:** Nhấn vào đường link sau để mở trang FlowMate trên Chrome Web Store:

      * [https://chromewebstore.google.com/detail/lhcmnhdbddgagibbbgppakocflbnknoa](https://chromewebstore.google.com/detail/lhcmnhdbddgagibbbgppakocflbnknoa)

3.  **Thêm vào Chrome:** Tại trang webstore, bạn sẽ thấy nút **"Thêm vào Chrome"** (Add to Chrome). Hãy nhấn vào đó.

4.  **Xác nhận Cài đặt:** Một popup sẽ hiện ra yêu cầu quyền truy cập. Nhấn **"Thêm tiện ích"** (Add extension) để hoàn tất.

5.  **Ghim Tiện Ích (Nên làm):**

      * Nhấn vào biểu tượng mảnh ghép (🧩) ở góc trên bên phải trình duyệt.
      * Tìm "FlowMate - Tự động hóa Prompt cho Flow" và nhấn vào biểu tượng ghim (📌) bên cạnh.
      * Bây giờ, icon của FlowMate sẽ luôn xuất hiện trên thanh công cụ để bạn dễ dàng truy cập.

-----

### **Phần 2: Chuẩn Bị Danh Sách Prompt**

  * Soạn danh sách các prompt của bạn trong một trình soạn thảo văn bản như Notepad.

  * **Quy tắc:** Mỗi prompt phải nằm trên **một dòng riêng biệt**.

    *Ví dụ đúng:*

    ```
    a beautiful cinematic shot of a panda eating bamboo
    an epic drone shot of Ha Long Bay, cinematic, golden hour
    a photorealistic video of a cat playing a tiny piano
    ```

-----

### **Phần 3: Hướng Dẫn Sử Dụng Giao Diện Chính**

Bây giờ, hãy truy cập trang **[Google Flow](https://labs.google/fx/tools/flow)**, **mở một dự án có sẵn** hoặc tạo một dự án mới. Sau đó, nhấn vào icon FlowMate trên thanh công cụ để mở bảng điều khiển.

#### **1. Khu Vực Nhập Prompt**

  * **Ô văn bản lớn:** Dán toàn bộ danh sách prompt bạn đã chuẩn bị vào đây.
  * **Nút "Nhập từ file (.txt)":** Nếu bạn đã lưu danh sách prompt thành file `.txt`, bạn có thể nhấn vào đây để tải lên nhanh chóng.

#### **2. Các Nút Điều Khiển**

  * **▶️ Bắt đầu:** Nút điều khiển chính.
      * **Hành động:** Bắt đầu quy trình gửi prompt tự động ngay trên dự án Flow mà bạn đang mở.
      * **Lưu ý quan trọng:** Tiện ích chỉ hoạt động khi bạn đang ở trong một trang dự án cụ thể (URL có chứa `.../project/...`). Nếu không, nó sẽ hiển thị một thông báo hướng dẫn.
  * **⏸️ Tạm dừng:** Tạm ngưng công việc sau khi hoàn thành prompt hiện tại.
  * **▶️ Tiếp tục:** Chạy tiếp quy trình đang tạm dừng.
  * **⏹️ Dừng:** Hủy bỏ toàn bộ quy trình làm việc.

#### **3. Khu Vực Cài Đặt (⚙️ Settings)**

Tất cả các tùy chọn đã được gom vào mục "Cài đặt Chung" để đảm bảo sự gọn gàng.

  * **`Thực thi mỗi prompt`:** Nhập số lần bạn muốn mỗi prompt được lặp lại. Ví dụ, nhập `3` sẽ tạo ra 3 phiên bản video cho mỗi prompt.
  * **`Bắt đầu từ prompt`:** Nếu bạn muốn bắt đầu từ một vị trí cụ thể trong danh sách, hãy nhập số thứ tự của prompt đó.
  * **`Thời gian chờ ngẫu nhiên (giây)`:** Đây là cài đặt cốt lõi giúp tiện ích hoạt động an toàn.
      * **Ý nghĩa:** Thiết lập khoảng thời gian chờ ngẫu nhiên giữa các lần gửi prompt để mô phỏng hành vi người dùng, tránh bị hệ thống phát hiện. Mặc định là 90-120 giây.
      * **Logic hoạt động:**
        1.  **Prompt \#1:** Gửi ngay lập tức.
        2.  **Prompt \#2 - \#5:** Chờ ngẫu nhiên trong khoảng bạn đã cài đặt.
        3.  **Prompt \#6 trở đi:** Chờ hàng đợi của Flow có chỗ trống, sau đó tiếp tục chờ ngẫu nhiên trong khoảng bạn đã cài đặt.
  * **`Ngôn ngữ (Language)`:** Chuyển đổi giao diện giữa Tiếng Việt và Tiếng Anh.

#### **4. Theo Dõi Tiến Trình**

  * **Thanh tiến trình:** Cho biết tổng quan % công việc đã hoàn thành.
  * **Trạng thái trực tiếp:** Hiển thị hành động hiện tại, ví dụ: "Đang xử lý prompt 5/100..." hoặc thông báo lỗi nếu bạn chưa mở đúng trang dự án.
  * **Log chi tiết:** Ghi lại mọi hành động với icon, màu sắc và dấu thời gian cụ thể, giúp bạn dễ dàng theo dõi những gì đang diễn ra.

-----

### **Phần 4: Ví Dụ Luồng Làm Việc Mẫu**

**Mục tiêu:** Tạo 2 phiên bản video cho 10 prompt khác nhau.

1.  Chuẩn bị 10 prompt, mỗi prompt một dòng.
2.  Truy cập Google Flow và **mở một dự án làm việc**.
3.  Nhấn vào icon FlowMate để mở tiện ích.
4.  Dán 10 prompt vào ô văn bản.
5.  Trong **Cài đặt Chung**, đặt `Thực thi mỗi prompt` thành **2**.
6.  (Tùy chọn) Điều chỉnh `Thời gian chờ ngẫu nhiên` nếu muốn.
7.  Nhấn nút **▶️ Bắt đầu**.
8.  Bây giờ, bạn có thể ngồi thư giãn và xem FlowMate làm việc.

Chúc bạn có những trải nghiệm sáng tạo hiệu quả và thú vị với FlowMate\!

-----

-----

### **FlowMate Detailed User Guide for Beginners**

Welcome to FlowMate\! This extension is your powerful assistant designed to fully automate the bulk video creation process on Google Flow, saving you hours of manual work. Let's get started\!

-----

### **Part 1: Installing the Extension**

To get started, you first need to add FlowMate to your browser.

1.  **Open Browser:** Open the Google Chrome browser.

2.  **Go to the Store Page:** Click the following link to open the FlowMate page on the Chrome Web Store:

      * [https://chromewebstore.google.com/detail/lhcmnhdbddgagibbbgppakocflbnknoa](https://chromewebstore.google.com/detail/lhcmnhdbddgagibbbgppakocflbnknoa)

3.  **Add to Chrome:** On the webstore page, click the **"Add to Chrome"** button.

4.  **Confirm Installation:** A popup will appear requesting permissions. Click **"Add extension"** to complete the installation.

5.  **Pin the Extension (Recommended):**

      * Click the puzzle piece icon (🧩) in the top-right corner of your browser.
      * Find "FlowMate - Prompt Automation for Flow" and click the pin icon (📌) next to it.
      * The FlowMate icon will now always be visible on your toolbar for easy access.

-----

### **Part 2: Prepare Your Prompt List**

  * Compose your list of prompts in a text editor like Notepad.

  * **The Rule:** Each prompt must be on **its own separate line**.

    *Correct Example:*

    ```
    a beautiful cinematic shot of a panda eating bamboo
    an epic drone shot of Ha Long Bay, cinematic, golden hour
    a photorealistic video of a cat playing a tiny piano
    ```

-----

### **Part 3: Guide to the Main Interface**

Now, navigate to the **[Google Flow](https://labs.google/fx/tools/flow)** page, **open an existing project** or create a new one. Then, click the FlowMate icon on your toolbar to open the control panel.

#### **1. Prompt Input Area**

  * **Large Textbox:** Paste your entire list of prepared prompts here.
  * **"Import from file (.txt)" Button:** If you have your prompts saved in a `.txt` file, you can click this to quickly upload them.

#### **2. Control Buttons**

  * **▶️ Start:** The main control button.
      * **Action:** Starts the automated prompt submission process on the Flow project you currently have open.
      * **Important Note:** The extension will only work if you are on a specific project page (URL contains `.../project/...`). Otherwise, it will display a helpful error message.
  * **⏸️ Pause:** Pauses the process after the current prompt is finished.
  * **▶️ Resume:** Resumes a paused process.
  * **⏹️ Stop:** Cancels the entire workflow.

#### **3. The Settings Panel (⚙️ Settings)**

All options have been consolidated into the "General Settings" section for a cleaner interface.

  * **`Runs per prompt`:** Enter the number of times you want each prompt to be repeated. For example, entering `3` will generate 3 video versions for every prompt.
  * **`Start from prompt`:** If you want to begin from a specific point in your list, enter the line number of that prompt here.
  * **`Random wait time (s)`:** This is the core setting that ensures the extension operates safely.
      * **What it does:** Sets the random time range between prompt submissions to simulate human behavior and avoid being flagged by the system. The default is 90-120 seconds.
      * **How it works:**
        1.  **Prompt \#1:** Sent instantly.
        2.  **Prompts \#2 - \#5:** Waits for a random duration within your set range.
        3.  **Prompts \#6+:** Waits for a free slot in Flow's queue, *then* waits for an additional random duration within your set range.
  * **`Language`:** Switches the interface between English and Vietnamese.

#### **4. Tracking Progress**

  * **Progress Bar:** Gives a quick overview of the total percentage completed.
  * **Live Status:** Shows the current action, e.g., "Processing prompt 5/100..." or an error message if you are not on a project page.
  * **Detailed Log:** Records every single action with an icon, color, and a specific timestamp, making it easy to see what's happening.

-----

### **Part 4: Sample Workflow Example**

**Goal:** Create 2 video variations for 10 different prompts.

1.  Prepare your 10 prompts, each on a new line.
2.  Navigate to Google Flow and **open a project to work in**.
3.  Click the FlowMate icon to open the extension.
4.  Paste the 10 prompts into the textbox.
5.  In **General Settings**, set `Runs per prompt` to **2**.
6.  (Optional) Adjust the `Random wait time` if needed.
7.  Click the **▶️ Start** button.
8.  Now, you can sit back, relax, and watch FlowMate work its magic.

Enjoy a more productive and creative experience with FlowMate\!
