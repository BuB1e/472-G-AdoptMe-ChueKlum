# AdoptMe

## วัตถุประสงค์
AdoptMe เป็นเว็บไซต์ที่ใช้ปล่อยหรือหาสัตว์เพื่อรับเลี้ยง รวมถึงการซื้อสินค้าต่างๆเกี่ยวกับสัตว์เลี้ยงและหาสถานพยาบาลหรืออ่านบทความต่างๆเกี่ยวกับสัตว์เลี้ยงด้วย

## สมาชิกทีม

1. **ชื่อ-นามสกุล:** นายหฤษฎ์ สมบัติศิริ
   - **รหัสนิสิต:** 6510451018
   - **หมู่เรียน:** 200
   - **ชั้นปี:** 3
   - **ฟีเจอร์ที่รับผิดชอบ:** @Bub1e Feat: Order สินค้า

2. **ชื่อ-นามสกุล:** กฤช วงศ์วรรณดี
   - **รหัสนิสิต:** 6510450143
   - **หมู่เรียน:** 200
   - **ชั้นปี:** 3
   - **ฟีเจอร์ที่รับผิดชอบ:** @Kriwn Feat: ระบบ Products

3. **ชื่อ-นามสกุล:** กวินท์ สินธพสิริพร
   - **รหัสนิสิต:** 6510450160
   - **หมู่เรียน:** 200
   - **ชั้นปี:** 3
   - **ฟีเจอร์ที่รับผิดชอบ:** @UADG Feat: Review Product

4. **ชื่อ-นามสกุล:** นุตประวีณ์ กาวี
   - **รหัสนิสิต:** 6510450534
   - **หมู่เรียน:** 200
   - **ชั้นปี:** 3
   - **ฟีเจอร์ที่รับผิดชอบ:** @nammeyyy Feat: Emergency
   
5. **ชื่อ-นามสกุล:** ษริกา โอภาสพิชญดำรง
   - **รหัสนิสิต:** 6510450984
   - **หมู่เรียน:** 200
   - **ชั้นปี:** 3
   - **ฟีเจอร์ที่รับผิดชอบ:** @sarika25171 Product Owner
   
## รายละเอียดฟีเจอร์
- **Order สินค้า** - page history, get order detail, cart system, payment
- **ระบบ Products** - page product, add product page, get product and product category detail
- **Review Product** - page product review details, get product reviews detail, admin reply review
- **Emergency** - emergency's places page, admin add-remove places, get emergency's places detail

## เทคโนโลยีที่ใช้
- **Frontend:** RemixJS, Tailwind CSS 
- **Backend:** Bun Elysia
- **CI/CD:** GitHub Actions, Docker  
- **Cloud Deployment:** Docker

## วิธีการติดตั้งและใช้งาน
1. clone project
   ```bash
   git clone --recurse-submodules https://github.com/BuB1e/472-G-AdoptMe-ChueKlum
   ```  
2. run website
   ```bash
   docker-compose up -d --build
   ```  