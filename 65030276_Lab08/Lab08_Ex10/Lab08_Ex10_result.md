# 10.1
<img width="640" alt="Screenshot 2024-03-30 212809" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-08/assets/144866059/62aa17a0-f1e7-4f62-8a7b-b3db7e8650e2">

# 10.2
<img width="640" alt="Screenshot 2024-03-30 212823" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-08/assets/144866059/fcc31ac3-cb7d-4d8f-9262-5caa80cfade9">

### ในการทดลองนี้ เราสร้างคลาส DerivedClass ซึ่งสืบทอดจาก BaseClass และกำหนดตัวแปร Field1 ใหม่ใน DerivedClass โดยใช้คีย์เวิร์ด new เพื่อแสดงว่าเรากำลังซ่อนตัวแปร Field1 ใน BaseClass ดังนั้น Field1 ใน DerivedClass จะไม่ส่งผลต่อ Field1 ใน BaseClass ในการสร้างอ็อบเจกต์ของ DerivedClass และ BaseClass ลงในตัวแปร DC และ BC ตามลำดับ จะเห็นว่า Field1 ของ DerivedClass จะถูกเรียกใช้เมื่ออ็อบเจกต์ของ DerivedClass ถูกใช้งาน ในทำนองเดียวกัน Field1 ของ BaseClass จะถูกเรียกใช้เมื่ออ็อบเจกต์ของ BaseClass ถูกใช้งาน ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "Field1 of DerivedClass" สำหรับ DC.Field1 และ "Field1 of BaseClass" สำหรับ BC.Field1 ตามลำดับ ซึ่งแสดงให้เห็นถึงการเรียกใช้ Field1 ต่างกันของ DerivedClass และ BaseClass จากการใช้งานผ่านอ็อบเจกต์ของแต่ละคลาส
