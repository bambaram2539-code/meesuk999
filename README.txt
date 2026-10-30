MESOOK REGISTRATION — GOOGLE SHEET LOCKED VERSION
=================================================

ระบบนี้ถูกล็อกให้บันทึกลง Google Spreadsheet ID:
1AJufZpwPvtwtAABDIDGt2vLNJksizZLjfe_5L8tz3EU

แท็บปลายทาง:
Registrations

Apps Script endpoint ที่หน้าเว็บใช้อยู่:
https://script.google.com/macros/s/AKfycbyxDkYTUqhfoQZBWtZI1XUjRg-bQ6a-IyA7eWgIdqfr1VFLYlk52iQx6n9zLLDDaTiE/exec

ไฟล์:
- index.html : หน้าเว็บสำหรับ GitHub/Vercel
- Code.gs : Backend ที่ระบุ Spreadsheet ID โดยตรง
- vercel.json : ตั้งค่า Vercel
- README.txt : คู่มือ

ติดตั้ง Code.gs
1. เปิด Apps Script โปรเจกต์ที่ใช้กับระบบ
2. แทน Code.gs เดิมด้วย Code.gs ในชุดนี้
3. Save
4. Deploy > Manage deployments
5. Edit deployment
6. Version > New version
7. Execute as > Me
8. Who has access > Anyone
9. Deploy และกดอนุญาตสิทธิ์

สำคัญ:
บัญชี Google ที่เป็นเจ้าของ/รัน Apps Script ต้องมีสิทธิ์แก้ไข Spreadsheet นี้

ทดสอบ Backend:
เปิด Web app URL /exec
ควรเห็น:
MESOOK registration API is running | Sheet: [ชื่อไฟล์ Google Sheet]

ติดตั้ง Vercel:
1. นำ index.html และ vercel.json ไปไว้ root ของ GitHub repository
2. Commit changes
3. รอ Vercel Deploy เป็น Ready
4. เปิดหน้าเว็บและกรอกข้อมูลทดลอง
5. ตรวจ Google Sheet > แท็บ Registrations

คอลัมน์:
เวลา | เลขทะเบียน | ชื่อ-นามสกุล | เบอร์โทร | หน่วยงาน | ผู้ติดตาม | หมายเหตุ
