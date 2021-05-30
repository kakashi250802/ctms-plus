# CTMS+
#### The Next Generation Of CTMS

[![Check](https://img.shields.io/github/checks-status/belivipro9x99/ctms-plus/main?style=for-the-badge)](https://github.com/belivipro9x99/ctms-plus/actions/workflows/main.yml)
[![Build](https://img.shields.io/github/workflow/status/belivipro9x99/ctms-plus/Build?style=for-the-badge)](https://github.com/belivipro9x99/ctms-plus/actions/workflows/main.yml)
[![CodeFactor](https://www.codefactor.io/repository/github/belivipro9x99/ctms-plus/badge?style=for-the-badge)](https://www.codefactor.io/repository/github/belivipro9x99/ctms-plus)

---

### 🤔 CTMS+ là gì ?

CTMS+ là một phiên bản được *thay áo mới* của CTMS với giao diện thân thiện hơn với người dùng. Toàn bộ dữ liệu hiển thị trong CTMS+ được lấy trực tiếp từ CTMS

CTMS+ hiện đang chạy trên các host sau:
 * Netlify: https://ctmsplus.netlify.com

### ☠ CTMS+ có đáng tin cậy không ?

CTMS+ gửi trực tiếp request của bạn tới CTMS thông qua middleware. Middleware hoạt động như một **shipper** có nhiệm vụ gửi yêu cầu của bạn tới đích một cách hiệu quả. Middleware được sử dụng để vượt qua những giới hạn của trình duyệt, nhờ đó mà CTMS+ có thể truy xuất dữ liệu trực tiếp từ CTMS

Mã nguồn của middleware có thể tìm thấy tại `/api/middleware.php` trong repo này.

### 🧩 Cấu trúc repository

Repo này chứa mã nguồn của `CTMS+` và `middleware API` được sử dụng để phục vụ cho `CTMS+`, bao gồm 3 nhánh chính:

 + 🌿 Branch `main`: Chứa mã nguồn của `CTMS+`. Mọi pull request sẽ được thực hiện tới branch này. Thay đổi trong branch này sẽ tự động chạy build của Github Action và merge vào branch `production`
 + 🌿 Branch `development`: Chứa mã nguồn với các tính năng đang trong thời gian hoàn thiện, các commit sẽ được thực hiện tại đây trước khi được nhập vào `main`
 + 🔮 Branch `production`: Chứa mã nguồn đã được thay đổi để phù hợp cho việc deploy site tới một host nào đó

### 😇 Đóng góp

> **⚠ Dự án hiện đang trong giai đoạn hoàn thiện và còn rất nhiều lỗi cũng như một số tính năng căn bản!**

Chúng mình không nhận tiền mặt làm hình thức đóng góp, thay vào đó chúng mình sẽ tiếp nhận công sức đóng góp của mọi người! Mọi đóng góp về code, ý tưởng hoặc góp ý đều được chào mừng!

Nếu bạn có một ý tưởng, một tính năng mà bạn muốn thấy trong tương lai, hoặc gặp một lỗi nào đó khi dùng phần mềm, bạn có thể gửi nó bằng cách tạo một **Bug Report/Feature Request** trong tab *Issues* của repo này.

Nếu bạn muốn ủng hộ bằng cách viết code, hãy chắc chắn rằng bạn đã đọc qua [Contributing Guidelines](CONTRIBUTING.md) trước khi submit một pull request