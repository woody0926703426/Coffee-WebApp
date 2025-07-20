Coffee WebApp – OOAD + GitHub Project

บทนำ

โปรเจกต์นี้เป็นตัวอย่างของระบบสั่งเครื่องดื่มออนไลน์สำหรับร้านกาแฟ โดยออกแบบตามหลัก Object-Oriented Analysis and Design (OOAD) ด้วย UML Diagram และสามารถนำไปใช้ในโปรเจกต์จริงร่วมกับ GitHub

ฟีเจอร์ของระบบ

- ลูกค้าสามารถ:
  - ลงทะเบียน / เข้าสู่ระบบ
  - สั่งเครื่องดื่มจากเมนู
  - ชำระเงินออนไลน์
  - ตรวจสอบสถานะการสั่งซื้อ
- พนักงาน:
  - ตรวจสอบออเดอร์ที่เข้ามา
  - อัปเดตสถานะว่าเสร็จแล้วหรือกำลังทำ
- แอดมิน:
  - จัดการรายการเมนู
  - ดูยอดขายและรายงาน

เทคโนโลยีที่ใช้

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js
- Database: MySQL
- DevOps: GitHub, GitHub Actions

Diagram ที่ใช้

- Use Case Diagram (./docs/usecase/usecase-coffee.png)
- Sequence Diagram (./docs/sequence/order-flow.png)

