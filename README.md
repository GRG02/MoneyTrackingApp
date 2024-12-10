# money_tracking_project

นี่เป็น mini project สำหรับการเรียนเขียนโปรแกรมในปี 3 เทอม 1 

Application ประกอบด้วย UI 7 หน้า ดังนี้

##1.SplashScreenUI

![1](https://github.com/user-attachments/assets/3ea472c8-729b-45d7-82a8-2a71f2bc19ea)

##2.WelcomeUI

ให้เลือกระหว่างจะไปหน้า Login หรือ Register

![2](https://github.com/user-attachments/assets/141aa955-b76e-4572-b325-57b4aa762d1c)

##3.LoginUI

เป็นหน้าสำหรับกรอก "ชื่อผู้ใช้" และ "รหัสผ่าน" สำหรับบัญชีที่ผ่านการสมัครและมีข้อมูลอยู่ในฐานข้อมูลแล้ว

![3](https://github.com/user-attachments/assets/1186231b-2103-427a-a3a6-b509564d2315)

##4.RegisterUI

เป็นหน้าสำหรับถ่ายรูปโปรไฟล์ และ กรอก "ชื่อ-สกุล", "วันที่เกิด", "ชื่อผู้ใช้" และ "รหัสผ่าน" สำหรับการสมัครบัญชีใหม่

![4](https://github.com/user-attachments/assets/74213fce-773d-40c4-8a89-59ad733df850)

##HomeUI มีหน้าที่เรียก subview ทั้ง 3 หน้าดังต่อไปนี้ และ BottomNavigationBar

##5.MainView(subview)

มีการแสดง Card ยอดรวมรายรับ, รายจ่าย, เงินคงเหลือ และ เป็นหน้าสำหรับแสดงรายการเงินเข้า - ออกที่เป็น ListView ที่จะแสดงรายการเพิ่มขึ้นเมื่อมีการกรอกข้อมูลในหน้า IncomeView หรือ OutcomeView

![5](https://github.com/user-attachments/assets/bf740a7a-e87a-4774-99c3-edb6ab89d7c0)

##6.IncomeView(subview)

มีการแสดง Card ยอดรวมรายรับ, รายจ่าย, เงินคงเหลือ และ เป็นหน้าสำหรับกรอก "รายละเอียดรายการเงินเข้า", "จำนวนเงิน" และ "วันที่เงินเข้า" เพื่อที่จะไปเพิ่มใน ListView ของหน้า MainView และคำนวณยอดรวมและเงินคงเหลือที่แสดงใน Card หลังจากที่กลับสู่หน้า MainView

![6](https://github.com/user-attachments/assets/266d614d-a1f2-4664-9920-6929e2fd742c)

##7.OutcomeView(subview)

มีการแสดง Card ยอดรวมรายรับ, รายจ่าย, เงินคงเหลือ และ เป็นหน้าสำหรับกรอก "รายละเอียดรายการเงินออก", "จำนวนเงิน" และ "วันที่เงินออก" เพื่อที่จะไปเพิ่มใน ListView ของหน้า MainView และคำนวณยอดรวมและเงินคงเหลือที่แสดงใน Card หลังจากที่กลับสู่หน้า MainView

![7](https://github.com/user-attachments/assets/653a693d-7940-4dfe-9bda-2ca2a3c296e6)



