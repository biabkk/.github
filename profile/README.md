# ThaiTipitaka 📚

> ระบบค้นหาและอ่านพระไตรปิฎกภาษาไทย ฉบับมหาจุฬาลงกรณราชวิทยาลัย (MCU)
> พระสุตตันตปิฎก 25 เล่ม | 5,034 สูตร | 17,231 ข้อ

---

## 🌐 Services

| Service | URL | สถานะ |
|---|---|---|
| 🖥️ Frontend (Streamlit) | https://thaitipitaka.org | ✅ Live |
| ⚡ API (FastAPI) | https://api.thaitipitaka.org | ✅ Live |
| 📖 API Docs (Swagger) | https://api.thaitipitaka.org/docs | ✅ Live |
| 📓 JupyterLab | https://jupyter.thaitipitaka.org | ✅ Live |
| 🗄️ pgAdmin4 | https://pgadmin.thaitipitaka.org | ✅ Live |

---

## ⚡ API Endpoints

| Endpoint | ทำอะไร | ตัวอย่าง |
|---|---|---|
| `GET /volumes` | รายการ 25 เล่ม | [ลองเลย](https://api.thaitipitaka.org/volumes) |
| `GET /volumes/{book_no}/suttas` | รายสูตรในเล่ม | [เล่ม 9](https://api.thaitipitaka.org/volumes/9/suttas) |
| `GET /suttas/{id}` | เนื้อหาสูตร | [สูตรที่ 1](https://api.thaitipitaka.org/suttas/1) |
| `GET /search?q=` | ค้นหาข้อความ | [ค้นหา "ทุกข์"](https://api.thaitipitaka.org/search?q=ทุกข์) |
| `GET /ref?b=&kho=` | ค้นจากเล่ม/ข้อ | [เล่ม 9 ข้อ 1](https://api.thaitipitaka.org/ref?b=9&kho=1) |

---

## 🏗️ Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit |
| API | FastAPI + Uvicorn |
| Database | PostgreSQL 16 |
| ORM | SQLAlchemy + psycopg2 |
| DB UI | pgAdmin4 |
| Dev | JupyterLab |
| Proxy | Nginx + SSL (Let's Encrypt) |
| Server | Ubuntu 24.04 LTS on Azure |

---

## 📊 ข้อมูล

| | จำนวน |
|---|---|
| เล่ม | 25 (เล่ม 9–33) |
| สูตร | 5,034 |
| ข้อ | 17,231 |
| ที่มา | [84000.org](https://84000.org) |

---

## 📦 Repositories

| Repo | รายละเอียด |
|---|---|
| [thaitipitaka](https://github.com/biabkk/thaitipitaka) | Main project — Frontend, API, Infrastructure |

---

## 👥 Team

| | GitHub |
|---|---|
| Somrak | [@somrakbia](https://github.com/somrakbia) |
| Korakot | [@korakot](https://github.com/korakot) |
| Buddhadasa | [@buddhadasa2449](https://github.com/buddhadasa2449) |
| Chidcha | [@chidcha](https://github.com/chidcha) |
