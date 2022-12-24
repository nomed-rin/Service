# Service
จุดประสงในการทำ ขึ้นมาคือ เหงาเบื่อๆแค่นั้นแหละ <br />
#All star <br />
ทำไม ถึงควรใช้ Losery Marco Record All star 
เพราะว่า ตัว Record marco เราเสถียรและ ไม่มีบัค และมีระบบ คำนวน ค่าตำแหน่งในกรณี All star ขยับแมพ <br />
เสถียรในระดับ Royx <br />
มี Optionดังนี้  <br />
Record Marco ใช้ได้โดยการ ปรับ ผ่าน Env หรือคนส่วนใหญ่รู้จักกัน ในชื่อ getgenv()
Example 
```lua
getgenv().RecordM = true
```
ไฟล์ทั้งหมดที่ Record จะไปอยุ่ที่ folder Losery --> Marco <br />
function Play ที่Support ดังนี้<br />
<br />
-- วางตัว  <br />
-- ขายตัว Unit  <br />
-- เปลี่ยน Priority <br />
-- Upgrade ตัวแบบจำนวนเงินถึง  <br />
วิธีการใช้ 
```lua
Plays("ที่อยุ่ของไฟล์")
```
สามารถ Set เวลาที่จะทำ ต่อไปได้ จริงๆไม่จำเป็นเลยเพราะ ของเราเสถียร ดีอยุ่แล้ว
วิธีการใช้ 
```lua
getgenv().waitTime = 1
```
