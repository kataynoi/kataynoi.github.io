---
layout: post
title: การตั้งค่า provider ให้สามารถส่งออกได้ถูกต้อง
---

#### แฟ้ม Provider
---
แฟ้ม Provider เป็นแฟ้มประเภทสะสมเอาไว้เก็บข้อมูลผู้ให้บริการ ครับ ซึ่งในการบริการทุกบริการ จะมี `provider` กำกับเสมอว่าใครเป็นผู้ให้บริการ 
ซึ่งในบางงาน จะให้ความสำคัญกับ *Provider* มากเช่นการให้บริการทันตกรรม `Providertype ต้องเป็นรหัส 03 ทันตแพทย์ หรือ 06` เจ้าพนักงานทันตสาธารณสุข ส่วนรหัสบุคลากรประเภทนอื่นๆ 
ดูได้ [ที่นี่](http://203.157.185.18/download/IT/standardcode43_2559_v2.1_15JULY16/) ดังนั้นการตั้งค่าการส่งออก  Provider จึงสำคัญมาก มีผลต่อการรายงานตามตัวชี้วัดด้วย

บุคคลากร Provider ประเภทต่างๆ 
![providertype](/img/setting/providertype.png)

#### การตั้งค่า Provider ใน  Hosxp_pcu 
---
> Hosxp:pcu->Tool->System setting แล้วเลือกแท๊บ `แพทย์/พยาบาล`

![system setting](/img/setting/provider1.png)

หากต้องการแก้ไข คนเดิม ให้ Double Click ที่รายชื่อนั้นเพื่อแก้ไข หรือ คลิกที่ปุ่ม `แก้ไข` ก็ได้
![system setting](/img/setting/provider2.png)
แล้วทำการกรอกข้อมูลให้ครบทุกช่องที่กำหนด  แล้วคลิกบันทึก
![system setting](/img/setting/provider3.png)

#### ดูข้อมูลการส่งออก จาก Hosxp_pcu ว่าส่งออกได้มั้ย
---
> เมื่อเราทำการบันทึกข้อมูล Provider แล้ว คนที่เรา ติ๊ก `Active Doctor `ไว้ควรจะต้องถูกส่งออกทุกคน ครับ 
 
 ![system setting](/img/setting/provider4.png)
 
 ![system setting](/img/setting/provider5.png)
 
 > หากข้อมูลส่งออกได้ไม่ครบต้องกลับไปตรวจสอบอีกครั้งนะครับว่าเราบันทึกครบหรือไม่  หรือ เข้าไปดูที่รายงานได้ครับ ตามรูป
 
 ![system setting](/img/setting/provider6.png)
 ![system setting](/img/setting/provider7.png)
 
 หวังว่า `Provider` ของทุกหน่วยบริการจะส่งออกครบนะครับ โดยเฉพาะ ทันตแพย์ และ เจ้าพนักงานทันตสาธารณสุข เพราะมีผลโดยตรงต่อรายงานด้านทันตกรรม
  
 

