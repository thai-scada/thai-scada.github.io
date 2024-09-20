- [Home](README.md)

## คู่มือการใช้งาน xAlarm

***Version 2024.8.1.1, September 2014***

***Manual Revision 2024.8.1.1 (September 9, 2024)***

## Installer

- Download ตัว install xAlarm-2024.8.1.2.msi หลังจากนั้นดับเบิ้ลคลิกที่ตัว install จะปรากฎหน้าต่างดังภาพ

![01](https://github.com/user-attachments/assets/3bd79533-3710-412e-9429-8a7dd584897e)

- หลังจากนั้นให้กด install และหลังจากนั้น จะปรากฎหน้าต่าง versions ของตัว install ให้กดช่องสี่เหลี่ยม หลังจากนั้นให้กด Next เพื่อดำเนินการต่อไป

![02](https://github.com/user-attachments/assets/650f5368-1f6b-454c-8ae6-e397e787e3e8)

- หลังจากนั้น จะเป็นการเลือกตำแหน่งที่ตั้งของตัวโปรแกรม xAlarm เมื่อเลือกตำแหน่งที่ต้องการแล้วให้กด Next ต่อไป

![03](https://github.com/user-attachments/assets/17fead04-ad8f-4229-9bec-e2a7d2b69ac9)

> [!NOTE]  
> แนะนำให้ลงที่ตำแหน่งไดร์ฟเดียวกับที่โปรแกรม xView เวลาตวรจเช็คจะสามารถหาโปรแกรมได้ง่าย

- หลังจากนั้น จะปรากฎตามหน้าต่างนี้ให้ กด Install เพื่อลงโปรแกรมต่อไป

![04](https://github.com/user-attachments/assets/58b9b18d-489f-401a-ac5a-ed3cc34f8ba4)

## Windows service

- เมื่อลงโปรแกรมได้สำเร็จให้ มาตรวจสอบว่ามีตัว Service ปรากฎบนหน้า Service หรือไม่ ถ้ามีให้ทำการ Start service   

![05](https://github.com/user-attachments/assets/475c71a6-5c52-4c36-9692-4428f8e765a0)

## Login

- ให้ทำการเช็ค License ของโปรแกรมก่อนว่ามี    
  - License `Messaging Service = Yes`  
  - Rockey HL with License Version 2.1 ขึ้นไป
- ตัวอย่าง Rockey HL

![06](https://github.com/user-attachments/assets/6c232f78-04ba-45da-8f4d-4ea60e1bed5d)

- เมื่อทำการตรวจสอบ license แล้ว ก็สามารถใช้งานได้ โดยเข้าไปที่ Web Browser และเข้าไปที่ `http://localhost:5010`

> [!NOTE]  
> หากต้องการเปลี่ยน URL หรือ Port โปรดติดต่อฝ่ายสนับสนุน

- เมื่อเข้ามาจะพบหน้า Login ดังภาพ   

![07](https://github.com/user-attachments/assets/a5e60a1b-48c4-4cfb-a07c-a88a66853f0f)

- ให้ทำการ Create account โดยระบุ Email ที่ต้องการใช้งานและทำตามขั้นตอนที่ได้รับทาง Email นั้น ๆ  
- หลังจากนั้นให้ทำการ Login จะเข้ามาที่หน้าจอหลัก ดังภาพ

![08](https://github.com/user-attachments/assets/01860cf6-1ec7-432b-917b-3bb8aa6c947d)

## Settings

- เมื่อเข้ามาหน้าจอหลัก จะเริ่มการตั้งค่าของ Alarm ให้ไปที่ `Tool > Settings`

![09](https://github.com/user-attachments/assets/1124e5dd-bbf3-494d-ab7b-5bf47dfb0437)

- จะมี 3 หัวข้อที่สามารถกำหนดค่า Setting ได้
  - Global Setting
  - User Setting
  - Group Setting

## Global Setting    

- Setting ในส่วนนี้จะเป็นการตั้งค่าหลักของการ Alarm และรูปแบบต่าง ๆ ดังนี้

### General Setting

- ในส่วนหน้าต่างนี้ จะบอกในส่วนของ Project ID และ Project name

![10](https://github.com/user-attachments/assets/b5cd23c4-f683-4dc5-90b8-730b8c2fdb19)

### Alarm Setting

- ในส่วนหน้าต่างนี้ จะบอกในส่วนของ การกำหนดว่าจะให้ Alarm ออกในส่วนไหน Email, SMS, Line notify, Line bot

![11](https://github.com/user-attachments/assets/0d92f900-0de6-47ae-8a6e-65bc19a1e0a4)

### Message Setting  

- ในส่วนหน้าต่างนี้ จะบอกในส่วนของการกำหนดรูปแบบ Alarm โดยจะมี หัวข้อดังนี้
  - Message Mode
    - รูปแบบของ Alarm มี 2 รูปแบบ คือเป็น Card หรือเป็น Text สามารถเลือกทั้งสองแบบได้  
  - Message title
    - กำหนดหัวข้อ ข้อความที่จะเป็นหัวข้อ
  - Card background image (preferred 1000x1000 pixels)
    - กำหนดรูป background โดยเลือกจากรูปที่อยู่ในโฟล์เดอร์ `xAlarm\app\wwwroot\assets\images`
  - Card background image opacity (0-100%)
    - กำหนดความเข้มของ background
  - Card font size (px)
    - ขนาดตัวอักษร
  - Card font weight
    - ความหนาตัวอักษร
  - Card font color
    - สีของตัวอักษร
 
![12](https://github.com/user-attachments/assets/42700a89-55c9-44ed-bb33-d5b9071c1c32)

### Email Setting

- ในส่วนหน้าต่างนี้ จะบอกในส่วนของการใส่ส่วนต่างๆของ Email
- ในส่วนต่าง ๆ สามารถ set ตาม default ได้ จะมีในส่วนของ Account name และ Account password สามารถใส่ได้ ตรงนี้จะเป็นในส่วนของ Email และ password (Email จะต้องเป็น Email ที่ปลด Security แล้ว)

![13](https://github.com/user-attachments/assets/32369e33-c4f1-46ce-98e8-7bd35cd74375)

### SMS Setting    

- ในส่วนหน้าต่างนี้ จะบอกในส่วนของการตั้งค่าของการส่ง SMS

![14](https://github.com/user-attachments/assets/d1670860-edf0-4c57-8039-3a54048630f0)

### Line Setting

- ในส่วนหน้าต่างนี้ จะ บอกในส่วนของการตั้งค่าของการส่ง ของ line โดยจะต้องใช้ Line notify token
- กรอกตรงช่องLine notify token

> [!NOTE]  
> การสมัคร Line notify เพื่อรับ token ควรมีการประสานงานเกี่ยวกับ email ที่จะใช้สมัครกับ End User ให้เรียบร้อย

![15](https://github.com/user-attachments/assets/b38de93f-22e7-42aa-938d-f0646f84abfd)

### User Setting

- Setting ในส่วนนี้จะเป็นการตั้งค่าจะเป็นการตั้งค่า User ที่จะนำมาใช้ในการรับ Set Point จากตัวโปรแกรม xView

![16](https://github.com/user-attachments/assets/e9fa6449-4021-4486-b7f2-911e1a2322e4)

### Group Setting  

- Setting ในส่วนนี้จะเป็นการตั้งค่าจะเป็นการตั้งค่า Group ที่จะนำมาใช้ในการรับ Set Point จากตัวโปรแกรม xView โดยที่ Group สามารถเพิ่มหรือลบ User เข้าไปแต่ละกลุ่มได้

![17](https://github.com/user-attachments/assets/226c507f-1552-40e1-a217-681462db2b6a)

## Events & log file

- สามารถตรวยสอบ Log ได้จาก หน้าต่าง Events ได้ โดยเข้าไปที่ `Tools > Events` จะมีรายการข้อมูลแสดงดังรูปภาพต่อไปนี้

![18](https://github.com/user-attachments/assets/84cba93c-4a7d-4199-bca2-84c6c5b1e3f1)
