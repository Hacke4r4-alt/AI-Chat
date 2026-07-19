# โปรเจคนี้ยังไม่สมบูรณ์ แต่ที่แจกทันที เพื่ออยากทำโปรเจคอื่นต่อ และ ให้คนที่โหลดไปได้ลองใช้งาน และ ปรับปรุงแก้ไข้ด้วยตนเองดู

โปรเจคนี้ใช้ api กับ google api ถูกล็อคไว้ที่ Gemini 3.1 Flash Lite (ตัวฟรีของ gemini ใช้ได้ 500 คำขอ คุยจนเบื่อก็ไม่เต็มถ้า RPM TPM ไม่เต็มก่อน )
คา key api ได้ที่ https://aistudio.google.com/api-keys

โปรเจคนี้ไม่ซับซ้อน จับลง xampp และใช้งานได้เลยผ่าน localhost ไม่หนักเครื่อง


โฟลเดอร์ที่จะสร้างเองอัตโนมัติถ้าตั้งค่าอะไรเสร็จ
- characters
- data
- user_profile

สำหรับ backup คือ ไฟล์ที่ backup index และ sttings ไว้ เผลอเราทำโค๊ตพังก็ย้อนกลับมาได้ อย่าพยายามไปยุ่งกับมัน

This project is incomplete, but it's being released immediately to allow me to work on other projects and to let those who download it try it out and make improvements themselves.

This project uses a Google API, locked to Gemini 3.1 Flash Lite (the free version of Gemini allows 500 requests – you can keep requesting as long as the RPM/TPM isn't full). The API key can be found at https://aistudio.google.com/api-keys

This project is not complicated. Just install it on XAMPP and use it via localhost; it's not resource-intensive.

The folders will be automatically created once the configuration is complete.

characters

data

user_profile

For backup: This file backs up the index and settings. If you accidentally break your code, you can revert back. Do not attempt to tamper with it.