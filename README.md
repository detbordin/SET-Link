# SET Link

เว็บแอปรับ/ส่งข้อมูลกับกล้อง Sokkia SET630RK (Series 30R) ผ่านสาย USB-RS232 โดยไม่ต้องใช้ไดรเวอร์ COM port ที่ Windows 11 ไม่รองรับ

## ความสามารถ
- แปลงไฟล์ CSV เป็น DXF ได้เลยโดยไม่ต้องต่อกล้อง (แท็บ CSV → DXF)
- รับ JOB จากกล้อง (SDR33/SDR2x) → ตารางจุด, บันทึกเป็น .sdr / CSV / CSV สำหรับ CAD / DXF
- ส่งพิกัด Known data เข้ากล้องจากข้อมูล Excel/CSV
- ไดรเวอร์ในตัว (WebUSB) สำหรับชิป Prolific PL2303, CH340/CH341, FTDI, CP210x
- ใช้ COM port ผ่าน Web Serial ได้ด้วย ถ้าไดรเวอร์ใช้งานได้

## วิธีใช้
- **Windows 11**: เปลี่ยนไดรเวอร์สายเป็น WinUSB ด้วย [Zadig](https://zadig.akeo.ie) (ครั้งเดียว) แล้วเปิด `index.html` ด้วย Chrome/Edge → กด "USB โดยตรง"
- **Android**: เสียบสายผ่าน OTG แล้วเปิดหน้าเว็บ (https) ด้วย Chrome

ขั้นตอนละเอียดอยู่ในแท็บ "วิธีใช้" ในแอป

## วิดีโอแนะนำการใช้งาน
[SET-Link-howto.mp4](SET-Link-howto.mp4) — ตั้งค่ากล้อง, ใช้งานบนคอม Windows 11 และมือถือ Android, รับงานและส่งพิกัด
