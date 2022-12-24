# Service
จุดประสงในการทำ ขึ้นมาคือ เหงาเบื่อๆแค่นั้นแหละ <br />
ทั้งหมดนี้ ฟรี !! ใช้ได้ฟรี
# All star <br />
ทำไม ถึงควรใช้ Losery Macro Record All star 
เพราะว่า ตัว Record marco เราเสถียรและ ไม่มีบัค และมีระบบ คำนวน ค่าตำแหน่งในกรณี All star ขยับแมพ <br /> 
คำนวน หาค่าตำแหน่งที่เปลี่ยนไปคืออะไร <br /> 
ถ้าหากคุณเคยใช้ค่ายอื่นๆ ที่ไม่ไช่ Royx มาก่อน ทุกๆครั้งที่ All star อัพเดต<br /> 
จะเกิดการขยับแมพขึ้นทำให้ ค่า CFrame เปลี่ยนไปทำให้ไฟล์เก่าๆ ที่คุณ อัดไว้ มันเสีย<br /> 
แต่ถ้าหากใช้อันนี้ จะไม่เจอปัญหานั้นอีกต่อไป <br /> 
ในกรณี ที่มี Hub ที่เอา ตัวMacro  ไปใช้คุณสามารถแชร์ไฟล์กับค่ายอื่นๆได้ด้วย<br /> 
เสถียรในระดับ Royx <br />
มี Optionดังนี้  <br />
Record Marco ใช้ได้โดยการ ปรับ ผ่าน Env หรือคนส่วนใหญ่รู้จักกัน ในชื่อ getgenv()<br />
Example <br />
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
หน้าตา macro https://raw.githubusercontent.com/nomed-rin/script_example/main/MarcoService
