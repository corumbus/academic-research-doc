# ระบบช่วยค้นหา Academic Research ในอดีตของ MSMIS TBS

## วิธีใช้
1. เข้าที่ Line Official Account [ArbnahmChat](https://lin.ee/PLopCTG)
    
    <img src="https://qr-official.line.me/gs/M_055xjhqs_GW.png"  width="200" height="200">
2. พิมพ์คำสั่ง 
    ```
    /mis <keyword ที่ต้องการค้นหา(ภาษาอังกฤษเท่านั้น)>
    ```
    เช่น
    ```
    /mis invest
    ```
3. ระบบแสดงรายชื่อ Academic Research 20 อันดับแรกที่เกี่ยวข้องกับ Keyword โดยเรียงจากเกี่ยวข้องมากไปน้อย พร้อมระบุประเภทของ Reseach และปีที่จัดทำ
4. นำชื่อ paper ไปดาวน์โหลด Full paper ที่ห้องสมุด มธ. [https://digital.library.tu.ac.th/tu_dc/frontend/Search/](https://digital.library.tu.ac.th/tu_dc/frontend/Search/)

## Note
1. ระบบนี้เกิดมาทำไม? [ระบบห้องสมุด](https://digital.library.tu.ac.th/tu_dc/frontend/Search/)เป็นการ macthing คำ แต่บาง reseach title ไม่มี Keyword ระบบนี้จึงสร้างขึ้นเพื่อเพิ่มความแม่นยำในการค้นหา
2. ข้อมูลทั้งหมดมากจาก https://mis.tbs.tu.ac.th/is-thesis/
3. ข้อมูล Raw Data รายชื่อ Academic Research ทั้งหมดของในอดีต ดูได้ที่ [thesis_list.csv](./thesis_list.csv)

## Disclaimer
1. ค้นหาด้วยภาษาอังกฤษเท่านั้น!!
2. ระบบนี้เป็นระบบที่ช่วยในการค้นหาเท่านั้น ในขณะนี้ ระบบไม่ได้อ่านบทคัดย่อ (Abstract) ของงานวิจัย โดยใช้ข้อมูลข้อความของชื่องานวิจัย (Research Title) และหาความสัมพันธ์กับคำค้นหา (Keyword) โปรดใช้ระบบนี้ร่วมกับการทำการค้นหาด้วยคำปกติ เช่น [ระบบห้องสมุด มธ.](https://digital.library.tu.ac.th/tu_dc/frontend/Search/)
3. ระบบไม่ได้ Realtime update หากมี paper ใหม่ต้อง update ข้อมูล
4. Academic Research ในอดีตปีแรกๆ ไม่มีชื่อภาษาอังกฤษ แต่ระบบสามารถทำงานได้ปกติ