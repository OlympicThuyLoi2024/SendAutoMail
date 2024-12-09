# SendAutoMail
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)

Xây dựng gửi email tự động cho hệ thống SafeZone khi có người trong khu vực bị nhiễm bệnh bằng nền tảng công nghệ LCDP n8n

## Changelogs

### v1.0
- Gửi email tự động cho mọi người khi có 1 người bị nhiễm bệnh trong khu vực.
- Gửi email tự động cho người dân khi tình trạng sức khỏe được cập nhật.

## Hướng dẫn cài đặt
### 1. Yêu cầu hệ thống
- **Tài khoản SMTP**: Là tài khoản gửi email đến các tài khoản khác  
- **N8N**: Phiên bản >=1.66.0

### 2. Cài đặt dữ án
#### Bước 1: Tải mã nguồn từ bản phát hành
1. Truy cập trang phát hành chính thức tại: [Releases](https://github.com/trungthanhcva2206/Service-AutoSendEmail/releases).
2. Chọn phiên bản phù hợp với nhu cầu của bạn.
3. Trong phần **Assets**, tải tệp:
   - `Source code (zip)` hoặc
   - `Source code (tar.gz)`.

#### Bước 2: Giải nén và truy cập thư mục
```bash
# Giải nén file đã tải
unzip Service-AutoSendEmail.zip
cd Service-AutoSendEmail
```
#### Bước 3: Import vô N8N 
1. Tạo 1 workflow trong N8N
2. Import file My-workflow.json, file này lấy được ở trong thư mục Service-AutoSendEmail

#### Bước 4: Chỉnh sửa các tài khoản dịch vụ
Ở trong node Send Email sẽ có phần **Credential to connect with**, có thể chỉnh sửa tài khoản SMTP của mình ở đây. 

 ## Đóng góp cho dự án

<a href="https://github.com/OlympicThuyLoi2024/SendAutoMail/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=BUG">Bug Report ⚠️
</a>

<a href="https://github.com/OlympicThuyLoi2024/ChatBot/issues/new?assignees=&labels=&projects=&template=feature_template.md&title=Feature">Request Feature 👩‍💻</a>

Nếu bạn muốn đóng góp cho dự án, hãy đọc [CONTRIBUTING.md](.github/CONTRIBUTING.md) để tìm hiểu thêm chi tiết.

Chúng tôi rất trân trọng mọi đóng góp từ các bạn. Đừng ngần ngại tạo pull request và gửi đến dự án.

## Tác giả
- Nguyễn Lê Trung Thành
- Trần Tuấn Anh
- Lê Văn Quang

# License
Phần mềm sử dụng License  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
