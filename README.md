# GitProject

Bài tập **Sử dụng Git** trong khóa học CodeGym.

## Mục tiêu

Thực hành tạo repository, quản lý mã nguồn bằng Git và đẩy mã nguồn lên GitHub.

## Cấu trúc dự án

```text
GitProject/
├── README.md
└── source/
    ├── index.html
    └── news.html
```

## Cách xem

Mở `source/index.html` bằng trình duyệt. Sử dụng liên kết trên trang để chuyển sang trang tin tức.

## Các lệnh Git cơ bản

```bash
git clone https://github.com/dangdieu5588/GitProject.git
cd GitProject
git add README.md
git commit -m "Add README.md"
git push origin main
git add source/
git commit -m "Add source files"
git push origin main
```

- `git clone`: sao chép repository và lịch sử commit về máy, thiết lập remote `origin`.
- `git add`: đưa thay đổi vào vùng chuẩn bị commit (staging area).
- `git commit`: ghi lại các thay đổi đã chuẩn bị vào lịch sử Git trên máy.
- `git push origin main`: đẩy các commit trên nhánh `main` lên remote `origin`.
