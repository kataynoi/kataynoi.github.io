---
layout: post
title: วิธีบันทึก KPI กระทรวงสาธารณสุข ใน Cockpit V.3เขตสุขภาพที่ 7
---
 [Cockpit V.3 เขตสุขภาพที่ 7](http://r7.moph.go.th/cpreg7)
 ![import Report](/img/cockpit/cockpit1.png)
#### ขั้นตอนคร่าวๆดังนี้ 
> 1. สมัคร Username ของ Cockpit
> 2. กำหนดตัวชี้วัดเป็นของตัวเอง 
> 3. บันทึกข้อมูลผลงานตามตัวชี้วัด

#### 1 .สมัคร Username ของ Cockpit 
--- 
> 1. เข้าสูหน้าเว็บ Cockpit  http://r7.moph.go.th/cpreg7
>   - แล้วคลิกที่มุมขวา บน เลือกเมนู " ลงทะเบียน "
![import Report](/img/cockpit/cockpit2.png)<br><br>
> 2. การลงทะเบียน แบ่งการบันทึกข้อมูลเป็น 3 ส่วน
>   - ส่วนที่ 1 ข้อมุลสำหรับใช้งานระบบ ให้บันทึก email username password ให้ครบถ้วน
![import Report](/img/cockpit/cockpit3.png)<br><br>
>   - ส่วนที่ 2 ข้อมูลการลงทะเบียน ให้บันทึกชื่อ สกุล ตำแหน่ง สังกัด หน่วยงาน กลุ่มงาน เบอร์โทร
![import Report](/img/cockpit/cockpit4.png)
>   - ส่วนที่ 3 การลงทะเบียน Line Alert เพื่อรับการแจ้งเตือน หากไม่สามารถ เข้าสู่ Line  สามารถข้ามไป ได้โดยบันทึก UID ทีหลัง
> ทำการ Scan QR Code เพื่อเข้ากลุ่ม Line Alert Reg7
> เมื่อเข้ากลุ่ม เสร็จแล้ว ให้พิมพ์ UID เพื่อรับรหัส 
> แล้วนำ UIDที่ได้มากรอกลงใน ช่อง UID ในเว็บลงทะเบียน

<img src='/img/cockpit/cockpit5.png' width='300px'><br><br>

> แล้วทำการกดเพิ่มเพื่อน เพื่อเข้าสู่ กลุ่ม Line Alert Reg7
<br>
<img src='/img/cockpit/cockpit6.jpg' width='250px'><br><br>

> หลังจากนั้น พิมพ์ UID เพื่อรับรหัส 
<br>
<img src='/img/cockpit/cockpit7.jpg' width='250px'><br><br>

> หลังจากนั้นทำการ Coppy รหัส UID ส่งไปเครื่องคอมพิวเตอร์ที่ลงทะเบียน ทาง Line PC หรือ Facebook ก็ได้
> นำรหัส UIDที่ได้มากรอก ในเว็บลงทะเยียนดังรูป
> เสร็จแล้ว Click ลงทะเบียน เสร็จแล้วรอการอนุมัติ
![import Report](/img/cockpit/cockpit8.png)

#### 2 .กำหนดตัวชี้วัดเป็นของตัวเอง  
--- 
> 1. คลิกเมนู มุม ขวาบนที่หน้าเว็บ เลือกเมนู "เข้าสู่ระบบ" 
![import Report](/img/cockpit/cockpit9.png)<br><br>
> 2. กรอก Username Password เพื่อเข้าสู่ระบบ
![import Report](/img/cockpit/cockpit10.png)<br><br>
> 3. ทำการเลือก เมนูมุมขวาบน เลือก "แก้ไขข้อมูลส่วนตัว"
![import Report](/img/cockpit/cockpit11.png)<br><br>
> 4. หลังจากนั้น เลื่อนลงไปในส่วน " ข้อมูลตัวชี้วัดที่รับผิดชอบ" แล้วคลิกเลือก KPI ที่รับผิดชอบ หาก ไม่พบ  KPI สามารถใช้เมนูค้นหาได้ 
![import Report](/img/cockpit/cockpit12.png)<br><br>
> 5. เลือกเมนู ด้านบน " บันทึกตัวชี้วัด " เพื่อตรวจสอบ KPI ที่เรารับผิดชอบว่าครบถ้วนถูกต้องหรือไม่ เพื่อเตรียมบันทึกข้อมูลต่อไป 
![import Report](/img/cockpit/cockpit13.png)

#### 3 .บันทึกข้อมูลผลงานตามตัวชี้วัด 
---
**ผลการดำเนินงานมี 2 ประเภทคือ**
>   - REC -> ผลงานที่ต้อง Key in ในระบบ
>   - HDC -> ผลงานที่ประมวลผลจาก HDC จะทำการดึงข้อมูลมาอัตโนมัติ จาก  HDC Service
![import Report](/img/cockpit/cockpit141.png)

**การบันทึกผลงานประเภท Key  in**
> 1. หากยังไม่ได้ Login เข้าสู่ระบบ ให้ Login ก่อน
![import Report](/img/cockpit/cockpit10.png)<br><br>
> 2. เข้าสู่การบันทึกข้อมูลตัวชี้วัด เมนู " บันทึกตัวชี้วัด "
![import Report](/img/cockpit/cockpit14.png)<br><br>
> 3. คลิกที่รูปดินสอ หน้าตัวชี้วัดเพื่อ เข้าสู่หน้าบันทึกตัวชี้วัด
![import Report](/img/cockpit/cockpit15.png)<br><br>
> 4. ตรวจสอบไตรมาสที่บันทึกตัวชี้วัด วัน ปิดระบบบันทึก 
>   - สามารถกรอกตัวเลข เป้าหมาย ผลงานได้ แยกรายอำเภอ เมื่อกรอกเสร็จระบบจะทำการบันทึกให้อัตโนมัติ 
>   - ระบบจะทำการคำนวน ผลงาน เป็นร้อยละ หรือ อัตราอื่นๆ ตามตัวชี้วัด
>   - หากตัวชี้วัดเป็นผลงานระดับจังหวัด ให้บันทึกที่ อำเภอเมือง 
![import Report](/img/cockpit/cockpit16.png)<br><br>
> 5. สำหรับตัวชี้วัดที่ไม่มีเป้าหมาย จะบันทึกผลงานอย่างเดียว 
![import Report](/img/cockpit/cockpit17.png)<br><br>
> 6. กลับเข้าสู่หน้าหลัก เลือกเมนูตัวชี้วัด เพื่อตรวจสอบผลงานที่บันทึก
![import Report](/img/cockpit/cockpit18.png)<br><br>




