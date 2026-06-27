# 🛍️ Skincare Ecommerce

ระบบร้านค้าออนไลน์สำหรับจำหน่ายผลิตภัณฑ์ดูแลผิวพรรณ พัฒนาด้วย React และ Node.js

---

## 📋 รายละเอียดโครงงาน

| รายการ | รายละเอียด |
|--------|-----------|
| **วิชา** | CSI204 Digital Platform for Software Development |
| **ประเภทโครงงาน** | E-Commerce Website |
| **แพลตฟอร์ม** | Web Platform |

---

## 🎯 วัตถุประสงค์

- พัฒนาเว็บไซต์ขายสินค้า Skincare ออนไลน์
- รองรับการแสดงสินค้า ตะกร้าสินค้า และระบบชำระเงิน
- จัดการข้อมูลสินค้าและคำสั่งซื้อผ่าน Admin Dashboard

---

## ⚙️ Tech Stack

### Frontend
- **React.js** — UI Framework
- **CSS3** — Styling

### Backend
- **Node.js + Express.js** — REST API Server

### Database
- **PostgreSQL** — Relational Database (ข้อมูลสินค้า, คำสั่งซื้อ, ผู้ใช้)

### DevOps & Tools
- **GitHub** — Version Control
- **SourceTree** — Git GUI Client
- **GitHub Pages** — Frontend Deployment

---

## 📁 โครงสร้างโปรเจกต์

```
skincare-ecommerce/
├── index.html          # GitHub Pages entry point
├── README.md           # เอกสารโครงงาน
└── docs/
    └── analysis.md     # Analysis & Design Document
```

---

## ✨ ฟีเจอร์หลัก

- **หน้าแสดงสินค้า** — รายการสินค้า Skincare พร้อมรูปภาพและราคา
- **ตะกร้าสินค้า** — เพิ่ม/ลบสินค้า และคำนวณราคารวม
- **ระบบสมาชิก** — สมัครสมาชิก / เข้าสู่ระบบ
- **ระบบชำระเงิน** — รองรับการชำระเงินออนไลน์
- **Admin Dashboard** — จัดการสินค้าและคำสั่งซื้อ

---

## 🚀 การติดตั้งและใช้งาน

### ความต้องการของระบบ
- Node.js v18+
- npm v9+

### ขั้นตอนการติดตั้ง

```bash
# 1. Clone repository
git clone https://github.com/<username>/skincare-ecommerce.git
cd skincare-ecommerce

# 2. ติดตั้ง dependencies (Frontend)
cd frontend
npm install

# 3. ติดตั้ง dependencies (Backend)
cd ../backend
npm install

# 4. รันโปรเจกต์
npm run dev
```

---

## 🌐 GitHub Pages

เข้าถึงเว็บไซต์ได้ที่: `https://SirithepKW.github.io/skincare-ecommerce`

---

## 📄 เอกสารที่เกี่ยวข้อง

- [Analysis & Design Document](docs/analysis.md)
