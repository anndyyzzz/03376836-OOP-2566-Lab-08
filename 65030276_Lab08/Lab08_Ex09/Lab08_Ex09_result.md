# 9.1
<img width="639" alt="Screenshot 2024-03-30 212545" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-08/assets/144866059/c1363232-df80-4ea0-8196-bfb1699e3cc0">

# 9.2
<img width="640" alt="Screenshot 2024-03-30 212555" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-08/assets/144866059/bc3a750d-3184-4025-b03b-85537b9c4a83">

### ในการทดลองนี้ เราสร้างคลาส DerivedClass ซึ่งสืบทอดจาก BaseClass และกำหนดตัวแปร Hello ใหม่ใน DerivedClass โดยใช้คีย์เวิร์ด new เพื่อแสดงว่าเรากำลังซ่อนตัวแปร Hello ใน BaseClass ดังนั้น Hello ใน DerivedClass จะไม่ได้ส่งผลต่อ Hello ใน BaseClass จากนั้น เราสร้างเมธอด PrintBaseHello ใน DerivedClass เพื่อพิมพ์ค่าของ Hello ใน BaseClass โดยใช้ base.Hello เพื่อเข้าถึง Hello ใน BaseClass ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "Hello From BaseClass" ตามค่าที่กำหนดใน BaseClass แม้ว่าเราจะกำหนดค่าใหม่ใน Hello ใน DerivedClass แต่ PrintBaseHello ใช้ base.Hello ซึ่งจะใช้ค่าจาก Hello ใน BaseClass
