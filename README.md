ทดสอบระบ# 🧾 Firebase CRUD + รูปภาพ

ระบบจัดการข้อมูลแบบ CRUD (Create, Read, Update, Delete) พร้อมรองรับการอัปโหลดและจัดเก็บรูปภาพ โดยใช้ **Firebase Firestore** เป็นฐานข้อมูล และ Deploy ผ่าน **Netlify**

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange)
![Netlify](https://img.shields.io/badge/Deploy-Netlify-blue)

---

## ✨ ฟีเจอร์หลัก

- ✅ **CRUD ครบวงจร** — เพิ่ม, ดู, แก้ไข, ลบข้อมูล
- 🖼️ **รองรับรูปภาพ** — อัปโหลดรูปพร้อมข้อมูล (ปรับขนาดอัตโนมัติเป็น 100×100 px)
- 🔍 **ระบบค้นหา** — ค้นหาข้อมูลแบบ Real-time
- 🗑️ **ลบทั้งหมด** — ล้างข้อมูลทั้งหมดในตารางด้วยคลิกเดียว
- 📱 **Responsive Design** — ใช้งานได้ทั้ง Desktop และ Mobile
- ⚡ **Real-time Sync** — ข้อมูลอัปเดตทันทีผ่าน Firestore

---

## 🛠️ เทคโนโลยีที่ใช้

| เทคโนโลยี | รายละเอียด |
|-----------|------------|
| **HTML5 / CSS3** | โครงสร้างและสไตล์ของหน้าเว็บ |
| **JavaScript (Vanilla)** | Logic ของแอปพลิเคชัน |
| **Firebase Firestore** | NoSQL Database แบบ Real-time |
| **Firebase Storage** *(ทางเลือก)* | เก็บรูปภาพแบบ Base64 / URL |
| **Netlify** | Hosting & Deployment |

---

## 📂 โครงสร้างข้อมูล (Firestore Collection)

Collection: `items` (หรือชื่อที่กำหนด)

| ฟิลด์ | ประเภท | คำอธิบาย |
|-------|--------|----------|
| `name` | String | ชื่อ |
| `address` | String | ที่อยู่ |
| `idCard` | String | เลขบัตรประชาชน |
| `phone` | String | เบอร์โทร |
| `note` | String | หมายเหตุ |
| `image` | String | URL หรือ Base64 ของรูปภาพ (100×100 px) |
| `createdAt` | Timestamp | วันที่สร้าง |

---

## 🚀 การติดตั้งและใช้งาน

### 1. Clone โปรเจกต์

```bash
git clone https://github.com/your-username/firebase-crud-image.git
cd firebase-crud-image
