# Lab 7-1: Local Component Demo

## คำอธิบาย
การทดลองนี้แสดงการใช้งาน component ที่มีอยู่ในโฟลเดอร์ `components/Sensors/` ของ project


## สรุปคำสั่งที่ใช้ และผลลัพธ์ที่ได้
  ## คำสั่งที่ใช้
        ```bash
        # เข้าไปยังโฟลเดอร์โปรเจค Lab 7-1
        cd lab7-1_Managed_Local_Component

        # Export environment สำหรับ ESP-IDF
        . $IDF_PATH/export.sh

        # กำหนด target เป็น ESP32
        idf.py set-target esp32

        # สั่ง Build Project
        idf.py build

        # (ถ้ามีบอร์ดจริง) Flash และ Monitor
        idf.py -p <PORT> flash monitor
## โจทย์ท้าทาย
1. สร้าง component ชื่อ Display โดย นำไฟล์ display.c และ display.h จากใบงานที่ 6 มาใช้
2. นำโค้ดจาก main.c ในใบงานที่ 6 มาใช้ แล้ว build พร้อมทดสอบ
<img width="748" height="438" alt="Screenshot 2025-08-19 234655" src="https://github.com/user-attachments/assets/462383be-2d19-4b7f-9ddd-1ed3c7c99149" />

