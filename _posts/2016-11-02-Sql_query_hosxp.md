---
layout: post
title: การใช้งาน Sql Qurey in Hosxp_pcu
---

#### วิธีเข้าใช้งาน Sql Query ในโปรแกรม  Hosxp_pcu
---
การเข้าใช้งาน Sql Query ในโปรแกรม Hos_xp_pcu  นั้นใช้งานในหลายๆอย่าง เช่นการตรวจสอบตารางต่างๆ ใน Database หรือการปรับตั้งค่าตารางให้ถูกต้อง 
การนำเข้ารายงานที่มีคนเขียนมาแจก ซึ่งข้อมูลทั้งหมดเป็นข้อมูลที่สำคัญของระบบ หากปรับผิดพลาดอาจจะเกิดปัญหาตามมาได้ การเขา้ใช้งานนั้นจึงต้องใช้สิทธิ ADMIN 
ในการเข้าใช้งาน 
> `การตรวจสอบสิทธิ Admin`

![Systen Setting](/img/sql/menu_systemsetting.png)

แล้วก็ดูใน Tabs ผู้ใช้งานว่า User ของเรามีสิทธิ Admin หรือไม่  โดยดูที่ accessright แล้วเราก็ทำ การ Login ด้วย User นั้น

![Admin](/img/sql/admin.png)

> การเข้าใช้งาน Sql Query

![Sql Query](/img/sql/sql_query.png)

แล้วก็จะได้หน้าตา ที่สามารถเขียนคำสั่ง SQl ได้รวมถึงการนำเข้า Report หรือ การปรับปรุงตารางได้ โดยสามารถพิมชื่อตาราง แล้วสั่ง ```Run```  ได้

![windows Sql](/img/sql/terminal_sql.png)


  