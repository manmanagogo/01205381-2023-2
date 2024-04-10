# แบบรายงานผลการทดลอง 
# เรื่อง Transmission Line Filter Design 
sec 11 <br/>
# กลุ่ม กลุ่มสาม
### จัดทำโดย
ธนดล    เนตรรัตนา    6410500751 <br/>
พีรวัส    แฉ่งชัยศรี     6410502231 <br/>
โยษิตา   ถิ่นจันทร์ฉาย  6410502273 <br/>
นพรุจ    พีรเพ็ญโภคัย  6410552076 <br/>

### เสนอ 
ผศ.ดร.เด่นชัย วรเศวต <br/>
รายงานนี้เป็นส่วนหนึ่งของรายวิชา ปฏิบัติการสถาปัตยกรรมและอุปกรณ์สื่อสาร <br/>
รหัสวิชา 01205381 ภาควิชาวิศวกรรมไฟฟ้า คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ ปีการศึกษา 2566 <br/>

## การทดลอง

นำค่า Electrical Length, Impedance และ Frequency ที่ได้จากการคำนวณบน excel แบบ  butterworth filter  7 order ไปสร้างเป็นชิ้นงานในโปรแกรม sonnet โดยการหาขนาดจาก TXLine <br/>

![Screenshot (248)_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/5a6520e8-6f9a-40c4-a667-1b6d47947515) <br/>
![Screenshot (249)_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/118aa89a-3e1d-44c2-b56f-360fd8e2fd78) <br/>

### ทำให้ได้กราฟออกมาดังนี้ 
- กราฟ port1 to port1
  
![sonnets11](https://github.com/NPeerawat/LAB_G3/assets/164756138/2bd31889-2a07-483b-bea8-54d2ec7675e7) <br/>

- กราฟ port1 to port2
  
![sonnets1,2](https://github.com/NPeerawat/LAB_G3/assets/164756138/ad7742a6-827b-4eba-9b48-c50f8ef976f8) <br/>

เมื่อได้รูปกราฟออกมาตามที่ต้องการ จึงนำชิ้นงานที่วาดได้ผ่านsonnet ไปวาดลงEasyEDA เพื่อนำไปสั่งทำเป็นผลงานจริง 

![Screenshot (258)_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/62315e64-3965-4eb5-b48d-aba62f3a94ed) <br/>

![Screenshot (257)_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/819b66d1-4f8a-464a-b568-49432131a00a) <br/>

![Screenshot (256)_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/ed71208e-a994-4672-a64d-05da5075c327) <br/>

##ภาพการสั่งทำชิ้นงาน

<img width="1438" alt="ภาพถ่ายหน้าจอ 2567-03-01 เวลา 20 17 14" src="https://github.com/NPeerawat/LAB_G3/assets/164756138/7fc90388-b471-4fd1-ac31-32dc96e766a2"> <br/>

<img width="1440" alt="ภาพถ่ายหน้าจอ 2567-03-01 เวลา 19 43 21" src="https://github.com/NPeerawat/LAB_G3/assets/164756138/0daa750a-e29b-451a-a09b-35560d34729e"> <br/>


นำชิ้นงานของจริงที่ได้ไปวัดค่าจริง โดยอ่านค่าผ่านโปรแกรม Putty แล้วนำไปพล้อตกราฟ<br/>

ค่าจริงที่ได้มีดังนี้ <br/>

## port1 to port1 <br/>

![s111_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/bc26c774-a328-4612-8b40-87224969d96e) <br/>
![s112_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/00dbf9a1-0bf1-4322-b79f-838a25685e02) <br/>


## เปรียบเทียบกราฟที่ได้จากชิ้นงานจริง และ sonnet (port1 to port1)<br/>

-กราฟที่ได้จากชิ้นงาน และ sonnet <br/>
![s11](https://github.com/NPeerawat/01205381-2023-2/assets/164756138/806f3920-de5f-49dc-a95f-91b7076d9763) <br/>

## port1 to port2 <br/>

![s121_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/ba202f5c-1d2a-4a4d-8c45-7920e5cc36f5)<br/>
![s122_0](https://github.com/NPeerawat/LAB_G3/assets/164756138/5eff05c3-b1a9-4b05-ac50-d1b55e0aa49b)<br/>


## เปรียบเทียบกราฟที่ได้จากชิ้นงานจริง และ sonnet (port1 to port2) <br/>

-ภาพที่ถ่ายจากเครื่องวัด <br/>
![IMG_9022](https://github.com/NPeerawat/01205381-2023-2/assets/164756138/77b865c0-ae99-49f6-a9bf-e9bf533223f6) <br/>

-กราฟที่ได้จากชิ้นงาน และ sonnet <br/>
![s12](https://github.com/NPeerawat/01205381-2023-2/assets/164756138/cf039aa2-02ec-4e50-a8d6-a73c2b909e4a)<br/>



## สรุปผลการทดลอง
 จากการทดลองออกแบบ Low pass filter กราฟที่แสดงออกมาจากเครื่องวัดจากชิ้นงานจริง และ กราฟที่ได้จำลองในโปรแกรม Sonnet พบว่ามีความคลาดเคลื่อน ที่สามารถรับยอมรับได้ ส่วนการสร้างแผ่นชิ้นงาน ในโปรแกรม EasyEDA มีปัญหาในการออกแบบของชิ้นงานบริเวรด้านหลังซึ่งไม่มี solder mark สำหรับบัดกรีเข้ากับ connect footprint ซึ่งค่าที่วัดได้จากชิ้นงาน ที่ -3.61 dB มีความถี่ 2 GHz และค่าที่ -30 dB มีความถี่ 2.76 GHz ซึ่งจากกราฟที่ได้จากชิ้นงานจริง เมื่อเทียบกับกราฟที่สร้างจาก Sonnet จะพบว่ามีความคลาดเคลื่อน ซึ่งจะเห็นว่าผลลัพธ์จากชิ้นงานจริงมีแนวโน้มที่ดีกว่า
