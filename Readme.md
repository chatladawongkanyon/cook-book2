## ควบคุม LED ให้กระพริบสลับฝั่ง อิงจากแลปการใช้GPIO และ LED 
เนื้อหาต่อยอดจาก cook-book1

1.เปิด VS Code และใช้คำสั่ง Create ESP-IDF Project เพื่อสร้างโปรเจกต์ใหม่ เลือกบอร์ด ESP32 และตั้งชื่อโปรเจกต์

<img width="911" alt="image" src="https://github.com/user-attachments/assets/0fdb24b4-fb30-4f55-8039-6f67690970c6">

2. เขียนโค้ดสำหรับสลับไฟ LED
   
<img width="369" alt="image" src="https://github.com/user-attachments/assets/27ca7492-0f68-4348-a3cb-3451a359a9c9">

3.คอมไพล์และอัปโหลดโปรเจกต์ไปยัง ESP32 Build, Flash and Monitor เพื่อคอมไพล์และอัปโหลดโค้ดไปยัง ESP32
ถ้าเชื่อมต่อบอร์ดสำเร็จ จะเห็นข้อความใน Serial Monitor และ LED จะเริ่มกระพริบสลับฝั่ง ทุกๆ 1 วินาที
