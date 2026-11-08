# X-T1 Film Shelf

ชั้นวางฟิล์มแบบ M-Film สำหรับ iPhone: 72 ฟิล์มจาก M-Film, ถ่ายด้วย iPhone แบบไม่เห็นรูปจนล้าง,
เอารูปในเครื่องมาล้างและปรับแต่ง, สูตรตั้งค่า Fuji X-T1 (Q menu, C1–C7) และ preset Lightroom ในโฟลเดอร์ `lightroom/`

เว็บแอปไฟล์เดียว ไม่ต้อง build เปิด `index.html` ผ่าน HTTPS แล้ว Add to Home Screen ใน Safari

## ที่มา

- รายชื่อฟิล์ม, ลายกลัก, คำอธิบาย และโมเดลสีของฟิล์ม (เส้นโค้ง, สมดุลสี, การเลื่อนเฉดสี, halation, เกรน) พอร์ตจาก
  [M-Film](https://github.com/) (`ml-dev/films/films.py`, `ml-dev/filmos/fos_dev.c`, `ml-dev/filmos/tools/catalog.py`)
  ซึ่งใช้สัญญาอนุญาต GPL-2.0 โปรเจกต์นี้จึงใช้ GPL-2.0 ตาม (ดู `LICENSE`)
- สีของ 63 ฟิล์มมาจาก LUT ชุด [Film-Luts](https://github.com/YahiaAngelo/Film-Luts) (MIT, Copyright (c) 2024 Yahia)
  ฝังอยู่ใน `index.html` เป็นภาพ atlas ขนาด 13×13×13 ต่อฟิล์ม ตามคำเตือนของ repo ต้นทาง LUT บางตัวอาจมีลิขสิทธิ์ของเจ้าของเดิม
- สูตร X-T1 และ preset Lightroom เป็นค่าประมาณ ไม่ใช่การจำลองแบบ LUT
