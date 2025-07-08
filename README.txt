
# Hướng dẫn chạy ứng dụng cục bộ

## Bước 1: Cài đặt Python và Visual Studio Code
- Đảm bảo bạn đã cài đặt Python (phiên bản 3.7 trở lên) và Visual Studio Code.

## Bước 2: Tạo và kích hoạt môi trường ảo
```bash
python -m venv venv
source venv/bin/activate  # Đối với Linux/MacOS
venv\Scripts\activate   # Đối với Windows
```

## Bước 3: Cài đặt các thư viện cần thiết
```bash
pip install -r requirements.txt
```

## Bước 4: Chạy ứng dụng
```bash
python app.py
```

## Bước 5: Truy cập ứng dụng
Mở trình duyệt và truy cập `http://127.0.0.1:5000`
