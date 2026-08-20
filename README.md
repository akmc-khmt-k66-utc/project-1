# Project 1

Repository **Project 1** phục vụ quá trình học tập và phát triển dự án của sinh viên **Khoa học máy tính – K66 UTC**.

## 📌 Giới thiệu

Repository:

**`project-1`**

Mục đích:

* Lưu trữ source code của dự án.
* Quản lý mã nguồn bằng Git/GitHub.
* Theo dõi lịch sử thay đổi của dự án.
* Hỗ trợ phát triển và làm việc nhóm.
* Lưu trữ các tài liệu, cấu hình và thành phần cần thiết của project.

## 🚀 Quick Setup

### Clone repository

```bash
git clone https://github.com/akmc-khmt-k66-utc/project-1.git
cd project-1
```

### Kiểm tra trạng thái

```bash
git status
```

### Cập nhật code mới nhất

```bash
git pull origin main
```

## 📂 Cấu trúc dự án

```text
project-1/
│
├── README.md
├── .gitignore
├── package.json
├── package-lock.json
│
├── controllers/
├── models/
├── routes/
├── views/
├── middlewares/
├── public/
│
└── ...
```

> Cấu trúc thư mục có thể thay đổi trong quá trình phát triển dự án.

## 💻 Phát triển dự án

Sau khi clone repository, cài đặt các package cần thiết:

```bash
npm install
```

Nếu sử dụng Yarn:

```bash
yarn install
```

Khởi chạy project:

```bash
npm start
```

Hoặc nếu project sử dụng Nodemon:

```bash
npm run dev
```

## 📤 Push code lên GitHub

Sau khi hoàn thành thay đổi:

```bash
git add .
git commit -m "Update project"
git push origin main
```

Có thể sử dụng commit message cụ thể hơn:

```bash
git add .
git commit -m "Add new feature"
git push
```

## 🌿 Làm việc với Branch

Tạo branch mới:

```bash
git checkout -b feature/ten-feature
```

Push branch:

```bash
git push -u origin feature/ten-feature
```

Sau khi hoàn thành có thể tạo Pull Request trên GitHub để merge vào `main`.

## ⚠️ Lưu ý

Không commit các file hoặc thông tin nhạy cảm:

* `.env`
* API key
* Password
* Database credentials
* Access token
* `node_modules/`

Đảm bảo `.gitignore` đã được cấu hình trước khi push code.

Ví dụ:

```gitignore
node_modules/
.env
.env.*
*.log
```

## 🔗 Repository

[GitHub Repository – project-1](https://github.com/akmc-khmt-k66-utc/project-1.git?utm_source=chatgpt.com)

## 🛠️ Công nghệ

Tùy theo phiên bản hiện tại của project, repository có thể sử dụng:

* **Node.js**
* **Express.js**
* **Pug**
* **MongoDB**
* **Mongoose**
* **JavaScript**
* **HTML/CSS**
* **Git & GitHub**

## 👥 Làm việc nhóm

Để đảm bảo code ổn định:

1. Pull code mới nhất trước khi làm việc.
2. Tạo branch riêng cho tính năng.
3. Commit thường xuyên với message rõ ràng.
4. Pull/rebase trước khi push nếu repository có nhiều người cùng làm.
5. Không tự ý force push vào `main` nếu đang làm việc nhóm.

## 📜 Git cơ bản

### Khởi tạo repository

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/akmc-khmt-k66-utc/project-1.git
git push -u origin main
```

### Kết nối repository có sẵn

```bash
git remote add origin https://github.com/akmc-khmt-k66-utc/project-1.git
git branch -M main
git push -u origin main
```

---

**Project 1 — K66 Computer Science, UTC.** 🚀
