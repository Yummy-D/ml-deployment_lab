# ML Deployment Lab — Flask & Docker

## 1. วิธี Build Docker Image

เปิด Terminal ในโฟลเดอร์โปรเจกต์ แล้วรันคำสั่ง

```bash
docker build -t ds-ml-service .
```

ตรวจสอบ Docker Image ที่สร้างสำเร็จ

```bash
docker images ds-ml-service
```

## 2. วิธี Run Docker Container

รัน Docker Container โดยใช้พอร์ต 8080

```bash
docker run --rm -p 8080:5000 ds-ml-service
```

จากนั้นเปิดเว็บเบราว์เซอร์ที่

http://localhost:8080


