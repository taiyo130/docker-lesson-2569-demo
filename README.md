# Todo App — ตัวอย่าง repo ของนักศึกษาหลังจบวันที่ 2

ตัวอย่างผลลัพธ์ของ workshop [docker-lesson-2569](https://github.com/taiyo130/docker-lesson-2569)
ทุก push เข้า `main` → test → build & push image ขึ้น GHCR → scan → deploy ขึ้น `std00.cpedev.cloud`

```
app/
  api/        Express + TS  (Dockerfile จาก Lab 3)
  web/        React + Vite  (Dockerfile + nginx จาก Lab 5)
  compose.yaml
.github/workflows/ci-cd.yml
```
