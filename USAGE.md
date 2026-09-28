# นาฬิกาและตาชั่ง

เว็บภาษาไทย 2 หน้า กดเมนูด้านบนเพื่อสลับใช้งาน

- `index.html` — นาฬิกา: กรอกเวลา ลากเข็ม รีเซ็ต และส่งออก PNG
- `fish-scale.html` — ตาชั่ง: กรอกน้ำหนัก 0–5 กิโลกรัม เลื่อนแถบ และส่งออก PNG
- `navigation.css` — รูปแบบเมนูและการแสดงผลบนมือถือ

เปิด `index.html` ในเว็บเบราว์เซอร์ หรือให้บริการด้วย static web server ไม่ต้องติดตั้ง dependencies

ไฟล์ HTML ต้นฉบับอ้างอิงภาพ clock-reference.png และ fish-scale-reference.png ซึ่งไม่ได้แนบมา เวอร์ชันนี้จึงแสดงหน้าปัด SVG ที่มีอยู่โดยตรง และส่งออกเฉพาะหน้าปัดเป็น PNG พื้นหลังโปร่งใส

## GitHub Pages
ใน repository ไปที่ Settings → Pages → Deploy from a branch → main → / (root) → Save หากบัญชีและประเภท repository รองรับ
