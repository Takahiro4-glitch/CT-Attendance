# CT-Attendance

หน้าเว็บสำหรับฝังระบบเช็กชื่อนักเรียน โรงเรียนจอมทอง จาก Google Apps Script

## เปิด GitHub Pages

Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save

URL เมื่อเปิดเผยแพร่แล้ว: https://takahiro4-glitch.github.io/CT-Attendance/

หน้าเว็บแสดง Web app ผ่าน iframe และมีลิงก์เปิดในแท็บใหม่ หากเบราว์เซอร์จำกัดการลงชื่อเข้าใช้ภายใน iframe

Apps Script และ Google Sheets ยังเป็นระบบประมวลผลและจัดเก็บข้อมูลเดิม การฝังไม่เพิ่มโควต้าหรือความเร็วการบันทึก

URL ของระบบอยู่ใน index.html ไม่ควรเพิ่มรหัสผ่าน โทเคน หรือรายชื่อนักเรียนลงใน repository สาธารณะ

ต้องทดสอบการเข้าสู่ระบบและบันทึกผ่านบัญชีครูจริงหลังเปิด Pages โดยสิทธิ์เข้าถึงขึ้นอยู่กับ deployment ของ Apps Script
