# ENGCE301 - Term Project_Team04 🚀

> **This is our solution for the ENGCE301 Term Project.** 

🌐 **Visit our website**: [Click Here](https://lab-wb.cpe-rmutl.net/team04/)

---

## 📝 Overview
### **Wallboard / Agent Notification**
 
![Overview](img/Overview.mp4)

---

### **📌 Data Flow Diagram (DFD)**
<img src="" alt="DFD" width="600"/>

### **📌 ER Diagram**
<img src="" alt="ER Diagram" width="600"/>

### **📌 Activity Flow Diagram**
<img src="" alt="Activity Flow" width="600"/>

---

## 🛠 Test Cases

## **📌Test Case (Agent Notification)**
| Test Section | Test Description | Test Step | Test Result |
|----------|----------|----------| ----------| 
| R 1.1| Agent สามารถ Login โดยใช้ Password ได้ โดยถ้า Password ผิดจะไม่สามารถ login ได้|1.กรอก Username/password2.กดปุ่ม Login | รหัสถูกจะเข้าสู่ระบบได้ รหัสผิดจะเข้าสู่ระบบไม่ได้ |
|R 1.2|สามารถเก็บประวัติการ login และ logout ได้ ในรูปแบบของวันเวลาที่ Login/Logout|ทดสอบการ Login-Logout เเละดูผลการทดสอบผ่านเว็บ|เเสดงผลประวัติการ login/logout , วันเเละเวลาที่เข้า-ออก ของ Agent บนเว็บ|
|R 1.3|สามารถเก็บประวัติการเปลี่ยนสถานะเวลาเริ่มต้นและสิ้นสุดแต่ละสถานะได้|ทดสอบโดยการส่ง Request เพื่ออัพเดทสถานะของ Agent|เเสดงผลการเปลี่ยนสถานะของ Agent บนเว็บ|
|R 1.4|สามารถเก็บประวัติการพูดคุยของแต่ละ Agent ได้|ทดสอบการส่งข้อความจาก Agent หนึ่งไปยังอีก Agent หนึ่ง และบันทึกข้อความนั้นผ่าน API|มีการเเสดงประวัติการส่งข้อความของ Agent , รายชื่อผู้ส่ง-รับ บนเว็บ|
## **📌Test Case (Agent Wallboard)**
| Test Section | Test Description | Test Step | Test Result |
|----------|----------|----------| ----------|
|R 2.1|สามารถแสดง Banner ที่ wallboard รวมทุก Agent ได้|ตรวจสอบ route /wallboard |มี Banner เเสดงสถานะการทำงานของ Agent|
|R 2.2|สามารถแสดงประวัติการ login logout และการเปลี่ยนสถานะของแต่ละ Agent ได้|ทดสอบการ Login - Logout ของ Agent ผ่าน agent-notification|มีการเเสดงประวัติการเข้า-ออก ของ Agent |
|R 2.3|สามารถเเสดงประวัติการพูดคุยของเเต่ละ Agent ได้|ทดสอบส่ง message จาก Agent สู่ Agent หนึ่ง ผ่าน agent-notification|มีการเเสดงประวัติการส่งข้อความของ Agent , รายชื่อผู้ส่ง-รับ |

---

## 🔗 API Specification
📄 **API Documentation**: [Click Here](./API%20Specification/README.md)

---

## 👨‍💻 Our Team
| Role | Name |
|------|------|
| 🏆 **Team Leader** | ธีรวัฒน์ พรมชัย รหัสนักศึกษา 65543206018-5 |
| 📊 **System Analyst (SA)** | จิรายุส ธรรมมงคล รหัสนักศึกษา 65543206008-6 |
| 💻 **Developer** | กิตติพงษ์ ปาลี รหัสนักศึกษา 65543206005-2 |
| 🔍 **Tester** | พิทักษ์ บุญน้อย รหัสนักศึกษา 65543206027-6 |

---
