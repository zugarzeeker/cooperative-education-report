<h1 align="center">ลักษณะของงานที่ปฏิบัติ</h1>

## 2. รายละเอียดของงานที่ปฏิบัติ

***เนื่องจากงานหลายชิ้นอยู่ภายใต้ Non-disclosure agreement จึงไม่สามารถเปิดเผยชื่อผลงานได้***

> ชิ้นงานข้อ 2.1 กับ 2.2 ทำเสร็จสิ้นในช่วงฝึกงานปิดเทอม

### 2.1 พัฒนาระบบ Admin ส่วน Frontend ด้วย AngularJS

<p align="center">
  <img src="./assets/task/2-1.png">
  <small>รูปที่ 2-1 Screenshot หน้าจัดการ Image Size Presets ของระบบ Admin</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
เป็นการทดลองใช้ AngularJS ครั้งแรก ซึ่งทางพี่ผู้ดูแลงานนี้ได้ให้ Requirements จากทางผู้ว่าจ้างมา แล้วให้ลองศึกษาทำดูเลย ซึ่ง Admin ต้องกระทำการต่างๆได้ดังนี้

* จัดการ User accounts ทั้งหมด
* เขียนบทความ
* ลงรูปภาพ Banner
* ลงข้อมูลทั่วไป (ข้อมูลผลิตภัณฑ์ Disclaimer ข้อมูลติดต่อ ฯลฯ)
* จัดการ/เพิ่มสินค้า (ราคาในหน่วยเงินต่างๆ จำนวนสินค้าที่เหลือ ฯลฯ)
* จัดหมวดหมู่สินค้า
* จัดการโปรโมชั่น
* ตรวจสอบรายการสั่งซื้อ และยืนยันการชำระเงิน
* แก้ไขราคาค่าขนส่ง
* จัดการข้อมูลของตัวแทนจำหน่วย
* แก้ไขข้อมูลทางการเงิน (หน่วยเงิน ข้อมูลบัญชีที่รับการโอนเงิน ฯลฯ)
* ข้อมูลสีของตัวต่อที่ลูกค้าสามารถ Custom ได้
* ข้อมูลขนาดรูปภาพที่ลูกค้าสามารถนำมา Pixelate
* Preset ของการ Pixelate
* ข้อมูลบางส่วนสามารถ Export ออกมาในรูปแบบไฟล์​ Excel (.xlsx) ได้

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยใช้โครงสร้างของ AdminLTE เป็นหลัก ซึ่งปัญหาที่เจอโดยมากเกิดจาก Learning curve ที่ใช้เวลาในการศึกษาการใช้ Framework ที่ไม่เคยใช้มาก่อน แต่ก็ถือได้ว่าเป็นงานที่ไม่ซับซ้อนเกินไปนัก เหมาะเป็นงานชิ้นแรกสำหรับการเรียนรู้วิธีการทำงานขององค์กร

### 2.2 พัฒนาระบบ Pixelate รูปภาพด้วย AngularJS
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
เป็นงานที่ทำให้กับผู้ว่าจ้างรายเดียวกับงานในข้อ 2.1 ซึ่งเป็นระบบที่ให้ลูกค้าสามารถนำรูปภาพที่ต้องการมาทำการ Pixelate เพื่อนำไปสั่งซื้อสินค้าตัวต่อเพื่อนำมาต่อเป็นรูปภาพผลลัพธ์ได้

<p align="center">
  <img src="./assets/task/2-2.png">
  <small>รูปที่ 2-2 ภาพก่อนและหลังการ Pixelate</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยหลังจากลูกค้าปรับแต่งรูปเสร็จสิ้นแล้ว ระบบจะคำนวณสิ้นค้าที่ต้องใช้ทั้งหมดให้ เช่น ตัวต่อเม็ดสีต่างๆ เพลทที่เป็นฐานของรูป และตัวเชื่อมเพลทหากรูปภาพมีขนาดใหญ่ รวมถึงสามารถ Download ไฟล์ PDF ที่ถูก Generate ขึ้นมา ซึ่งจะมีคำแนะนำในการต่ออย่างละเอียด

<p align="center">
  <img src="./assets/task/2-3.png">
  <small>รูปที่ 2-3 Screenshot หน้า Output ของระบบ Pixelate</small>
</p>
<p align="center">
  <img src="./assets/task/2-4.png">
  <small>รูปที่ 2-4 ตัวอย่างบางส่วนของ PDF คำแนะนำการต่อรูป Pixelate</small>
</p>

### 2.3 พัฒนาเว็บแอพพลิเคชันสำหรับแนะนำการรักษาพยาบาลและการท่องเที่ยวในต่างประเทศ ด้วย ReactJS, Redux

<p align="center">
  <img src="./assets/task/2-5.png">
  <small>รูปที่ 2-5 Screenshot หน้าหลัก ของเว็บไซต์แนะนำการรักษาพยาบาลและการท่องเที่ยว</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
เป็นเว็บไซต์ที่จะแนะนำสถานพยาบาลที่มีคุณภาพในต่างประเทศ รวมถึงจัดแผนการท่องเที่ยวในประเทศนั้นๆให้ด้วย ซึ่งกลุ่มเป้าหมายหลักคือประชากรชาวจีน เนื่องจากโรงพยาบาลในจีนที่มีคุณภาพนั้นมีราคาที่สูง และมีผู้ใช้งานจำนวนมาก ทำให้การไปใช้บริการโรงพยาบาลในต่างประเทศ (เช่น​ ญี่ปุ่น ไทย) นั้นมีค่าใช้จ่ายที่ไม่ต่างกันมากนัก และผู้ใช้บริการหรือผู้ที่ติดตามไปก็สามารถท่องเที่ยวได้ด้วย

> ซึ่งเป็นครั้งแรกสำหรับการใช้ ReactJS, Redux ทำให้ใช้เวลาไปกับ Learning Curve พอสมควร

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยระบบหลักๆคือการให้ผู้ใช้งานสามารถค้นหาโรงพยาบาลที่ตรงกับความต้องการ ไม่ว่าจะเป็นการค้นหาด้วยสถานที่ โรคที่โรงพยาบาลนั้นสามารถรักษาได้ หรือลักษณะพิเศษต่างๆ เช่น มีห้อง VIP หรือโรงพยาบาลนั้นสะอาดเป็นพิเศษ

<p align="center">
  <img src="./assets/task/2-6.png">
  <small>รูปที่ 2-6 Screenshot หน้าค้นหาโรงพยาบาล ของเว็บไซต์แนะนำการรักษาพยาบาลและการท่องเที่ยว</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
และเว็บไซต์เองก็ยังมีระบบสำหรับการท่องเที่ยวอย่างเดียวด้วยเช่นกัน ซึ่งผู้ใช้งานก็สามารถค้นหาแพ็คเกจของการท่องเที่ยวที่จัดไว้ให้แล้วได้ตามความต้องการ เช่นค้นหาตามช่วงราคา สถานที่ หรือลักษณะพิเศษของแพ็คเกจนั้นๆ เช่นการที่มีไกด์นำทางให้ด้วย

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยที่ผู้ใช้สามารถติดต่อกับทางเว็บไซต์ได้ว่าต้องการปรับเปลี่ยนแพ็คเกจส่วนไหน เพื่อให้ตรงกับความต้องการมากที่สุด

<p align="center">
  <img src="./assets/task/2-7.png">
  <small>รูปที่ 2-7 Screenshot หน้าค้นหาแพ็คเกจ ของเว็บไซต์แนะนำการรักษาพยาบาลและการท่องเที่ยว</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งเป็นเว็บไซต์นี้จะมีข้อมูลโดยละเอียดของโรงพยาบาลที่ร่วมกับบริการนี้ และข้อมูลของแพ็คเกจเองก็มีอยู่อย่างครบถ้วน เพื่อที่ผู้ใช้จะสามารถตัดสินใจได้อย่างสะดวก และมีความพึงพอใจสูงที่สุด

<p align="center">
  <img src="./assets/task/2-8.png">
  <small>รูปที่ 2-8 Screenshot หน้าข้อมูลโรงพยาบาล ของเว็บไซต์แนะนำการรักษาพยาบาลและการท่องเที่ยว</small>
</p>
<p align="center">
  <img src="./assets/task/2-9.png">
  <small>รูปที่ 2-9 Screenshot หน้าข้อมูลแพ็คเกจ ของเว็บไซต์แนะนำการรักษาพยาบาลและการท่องเที่ยว</small>
</p>

### 2.4 พัฒนาเว็บแอพพลิเคชันสำหรับบริการ Social Monitoring ด้วย ReactJS, Redux, Node.js, Google DataStore, Google BigQuery, Google AppEngine, Google ComputeEngine
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ในงานที่กล่าวมาก่อนหน้า ข้าพเจ้าทั้งสองร่วมกันทำส่วนเดียวกัน โดยสับเปลี่ยนกันช่วยเหลือแต่ละจุดตามงานที่มี แต่งานชิ้นนี้แบ่งกันชัดเจน โดยเอกดนัยทำส่วนของ Frontend และศุภณัฐทำส่วนของ Backend

<p align="center">
  <img src="./assets/task/2-10.png">
  <small>รูปที่ 2-10 Screenshot หน้าดูข้อความ ของบริการ Social Monitoring</small>
</p>

> งานชิ้นนี้ยังไม่เสร็จสมบูรณ์ อาจมีบางส่วนที่ยังใช้งานได้ไม่สมบูรณ์ หรือ Features บางส่วนอาจเปลี่ยนแปลงนับจากวันที่เขียนรายงานนี้ขึ้น

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งงานนี้ทางผู้ว่าจ้างกำหนดมาว่าต้องการใช้บริการ Google BigQuery ในการเก็บข้อมูลและทำ Indexing ข้อความที่ทางผู้ว่าจ้างเก็บจาก Social Media ช่องทางต่างๆมาได้ ซึ่งมีจำนวนมหาศาลมาก รวมทั้งใช้ Google DataStore ในการเก็บข้อมูลส่วนอื่นๆ เช่นข้อมูลผู้ใช้ ข้อมูลองค์กร ข้อมูลโปรเจ็กต์ และ Deploy Application ไปยัง Google AppEngine สำหรับ Production และ Google ComputeEngine ซึ่งใช้งานเหมือน VPS สำหรับ Development

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
แต่ผลลัพธ์ก็คุ้มค่า เนื่องจาก Google BigQuery สามารถค้นหาข้อความที่ต้องการจากข้อความหลายล้านได้ในเวลาไม่นานนัก(ไม่กี่วินาที) และเครื่องมืออื่นๆเองก็ทำให้ทางรันเนเบิลส์สามารถวางใจเรื่องการ Scale เมื่อมีผู้ใช้งานมากๆได้ในระดับหนึ่ง เพราะทางเครื่องมือที่ใช้สามารถ Spawn Instances เพิ่มขึ้นตาม Demands ได้เอง

> **ข้อควรระวัง**
> จากการใช้งาน Auto Scaling ของ Google App Engine คือควรมีการระบุ max-instances หรือ ให้ปิดเองอัตโนมัติเมื่อใช้งานน้อย เนื่องจากถ้าหาก เพิ่มจำนวน instances ไปเรื่อยๆ จะเป็นผลในเรื่องค่าใช้จ่ายที่ตามมาได้

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
สำหรับโปรเจกต์นี้ Backend แบ่งเป็นหลายๆ MicroServices
ซึ่งต้องเรียกใช้แต่ละ Service ผ่าน API Gateway นอกจากนี้ยังมีการเขียน Datastore Deep Populate ขึ้นมา ใช้งานได้ดีบน Network ของ Google ในการดึง Data Nested Model มาจาก Google Datastore ซึ่งคล้ายๆกับ [mongoose-deep-populate](https://github.com/buunguyen/mongoose-deep-populate) สำหรับ MongoDB ใช้งานได้ดีกับ Google App Engine และ Google Compute Engine เนื่องจาก Network ภายใน Google จะให้ผลดีในการเข้าถึงข้อมูลใน Google Datastore

<p align="center">
  <img src="./assets/task/2-11.png">
  <small>รูปที่ 2-11 กราฟการใช้งานของ VM Instance</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
นอกจากนี้ยังมีการ Setup CircleCI ให้รัน Automated Test ของ Code ที่ push ขึ้น github ถ้าหากผ่านทุก Test Case จะทำการ ตามที่ได้ Set ไว้ แต่หาก เกิด Error ขึ้น เนื่องจาก Run Test Case ไม่ผ่าน หรือ ไม่สามารถ Deploy ได้ ก็จะแจ้งมายัง Slack ที่ใช้สื่อสารกันในบริษัท โดยมีการใช้งานร่วมกับ emoticon (:ambulance: :zap:) ใน commit message ในการกำหนดสถานะการ Deploy ให้แตกต่างกัน

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยขั้นตอนดำเนินการของบริการนี้คือ การให้องค์กรที่ต้องการใช้งานมาลงทะเบียนสร้างองค์กรของตนในระบบไว้ แล้วจากนั้นจึงสร้างโปรเจ็กต์ขึ้นมา โดยระบุข้อมูลว่าต้องการข้อความแบบไหนบ้าง แล้วตัว Crawler ก็จะทำการส่งข้อความที่ตรงเงื่อนไขเข้าสู่โปรเจ็กต์โดยมีจะมี Analyst คอยวิเคราะห์ข้อความดังกล่าว และใส่ข้อมูลระบุคุณสมบัติของข้อความนั้นๆ ว่าพูดถึงองค์กรในแง่บวกหรือลบ และพูดถึงในหัวข้อไหน ซึ่งทางองค์กรเองก็สามารถสร้าง Dashboard เพื่อดูการ Visualization สรุปข้อมูลได้ โดยใช้บริการจาก Third-party (เช่น Tableau)

<p align="center">
  <img src="./assets/task/2-12.png">
  <small>รูปที่ 2-12 Screenshot หน้าสร้างโปรเจ็กต์ ของบริการ Social Monitoring</small>
</p>

<p align="center">
  <img src="./assets/task/2-13.png">
  <small>รูปที่ 2-13 Screenshot หน้าแก้ไขข้อมูลโปรเจ็กต์ ของบริการ Social Monitoring</small>
</p>

<p align="center">
  <img src="./assets/task/2-14.png">
  <small>รูปที่ 2-14 Screenshot ส่วนจัดการ Meta ของบริการ Social Monitoring</small>
</p>

<p align="center">
  <img src="./assets/task/2-15.png">
  <small>รูปที่ 2-15 Screenshot หน้าดู Visualization โดย Tableau ของบริการ Social Monitoring</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งหนึ่งในสิ่งที่ท้าทายของงานชิ้นนี้ก็คือการออกแบบการจัดการ Permission ต่างๆ เพราะมีผู้ใช้งานที่มีสิทธิ์ต่างกันหลายแบบมาก เช่น Super Admin ที่จัดการได้ทุกอย่างบนเว็บไซต์, Admin ขององค์กร ที่สามารถจัดการบุคคลในองค์กร หรือสร้างโปรเจ็กต์ใหม่ๆได้, Admin/Project Owner ที่มีสิทธิ์จัดการข้อมูลโปรเจ็กต์ต่างๆ, Analyst ที่มีสิทธิ์แค่การดูข้อความในโปรเจ็กต์ และใส่ข้อมูลให้กับข้อความต่างๆเท่านั้น ไม่มีสิทธิ์ในการลบโปรเจ็กต์ หรือจัดการเปลี่ยนการตั้งค่าของโปรเจ็กต์ และประเภทอื่นๆอีกมากมาย ทำให้ได้เรียนรู้วิธีการออกแบบการเก็บข้อมูล และวิธีการตรวจสอบสิทธิ์ที่มีประสิทธิภาพ รวมถึง Frontend ก็ต้องกำหนดการเข้าถึงหน้าต่างๆของผู้ใช้แต่ละคนให้เข้าถึงได้เฉพาะหน้าที่ควรเข้าถึงได้ และแสดง Function ต่างๆเท่าที่ผู้ใช้คนนั้นมีสิทธิ์

<p align="center">
  <img src="./assets/task/2-16.png">
  <small>รูปที่ 2-16 Screenshot หน้า Instances ต่างๆ ของ Google Compute Engine</small>
</p>

<p align="center">
  <img src="./assets/task/2-17.png">
  <small>รูปที่ 2-17 Screenshot หน้า Google BigQuery</small>
</p>

### 2.5 พัฒนาเว็บแอพพลิเคชันแหล่งรวมบริการรับสอนพิเศษ ด้วย ReactJS, Redux, Node.js, MongoDB, Google Firebase

> งานชิ้นนี้เพิ่งรับเข้ามาช่วงต้นเดือนธันวาคม และยังไม่ถึงช่วงที่จะเริ่มดำเนินการ ณ​ เวลาที่รายงานนี้ถูกเขียนขึ้น จึงยังไม่มีข้อมูลมากนัก

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
เป็นชิ้นงานที่ต้องทำต่อหลังจากเสร็จสิ้นเวลาฝึกงานแล้ว ซึ่งจะได้ทดลองใช้ Google Firebase ในการทำระบบ Chat ระหว่างผู้เรียนและผู้สอน และการค้นหาข้อมูลคลาสเรียนต่างๆที่ผู้เรียนต้องการ

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยเป็นงานที่วางแผนไว้ว่าจะทดลองหลายๆสิ่ง เช่น `Redux Saga` เป็นต้น และถึงแม้จะยังไม่ได้เริ่มงานนี้โดยตรง แต่ก็เตรียมการหลายๆอย่างไว้แล้ว เช่น config eslint, เตรียม boilerplate ดังที่จะกล่าวอย่างละเอียดในหัวข้อถัดไป

### 2.6 การเตรียม Environment การทำงานที่มีประสิทธิภาพ

#### eslint-config-runnables
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
https://github.com/runnables/eslint-config-runnables

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
เป็นการตั้งค่า Linter ของทีม Runnables (โดยคำอธิบายของ Linter อยู่ในหัวข้อทฤษฎีที่เกี่ยวข้อง)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งเน้นการปรับจาก [eslint ของ airbnb](https://www.npmjs.com/package/eslint-config-airbnb) ที่ทางทีมเห็นว่ามีมาตรฐานอยู่แล้ว แต่ทำการปรับเปลี่ยนบางอย่างเพื่อให้เข้ากับเครื่องมือต่างๆที่ทางทีมใช้ เช่น การใช้ [Lodash](https://lodash.com/) ซึ่งมี [eslint plugin ที่ระบุกฎสำหรับการใช้ Lodash ที่สวยงาม](https://github.com/eslint-plugins/eslint-plugin-lodash)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งการสร้าง Repository ขึ้นมาสำหรับการจัดการ eslint โดยเฉพาะ ทำให้การนำไปใช้ในโครงการถัดๆไปทำได้สะดวกยิ่งขึ้น ซึ่งปกติการใช้ eslint จะต้องมีไฟล์ `.eslintrc` ในการกำหนดมาตรฐานโค้ด โดยภายในไฟล์นั้นมักจะมีกฏมากมายอยู่ ทำให้ไฟล์อ่านยาก และการแก้ในที่นั้นที่เดียวก็ไม่ส่งผลให้โครงการอื่นๆร่วมใช้งานกฏนั้นด้วย แต่เมื่อใช้ `eslint-config-runnables` แล้ว ภายในไฟล์ `.eslintrc` ก็สามารถมีเพียงคำสั่งเดียว คือ

```
{
  "extends": "runnables"
}
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งการทำเช่นนี้ทำให้โครงการใดก็ตามที่ใช้ Config eslint แบบนี้จะแน่ใจได้ว่าทุกโครงการมี Coding standard ที่เหมือนกัน ทำให้การทำงานเป็นไปอย่างมีประสิทธิภาพ

#### การเพิ่มประสิทธิภาพของ Webpack
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
การทำงานโดยปกติของทีม จะใช้ [Webpack](https://github.com/webpack/webpack) ในการช่วยจัดการ ซึ่ง [Boilerplate ที่ทีมใช้ในการพัฒนาเว็บไซต์](https://github.com/erikras/react-redux-universal-hot-example) มีการ Config webpack ที่ส่งผลต่อเวลาในการ Build ที่นานเกินว่าที่ทีมต้องการ จึงต้องมีการปรับแต่ง ซึ่งเทคนิควิธีต่างๆที่ใช้ในการปรับแต่ง จะอธิบายอย่างละเอียดในหัวข้อทฤษฎีที่เกี่ยวข้องเป็นการถัดไป

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
โดยการ Build ครั้งแรกใช้เวลาทั้งหมด 23088 milliseconds

<p align="center">
  <img src="./assets/task/2-18.png">
  <small>รูปที่ 2-18 การ Build Webpack ก่อนจะปรับแต่ง</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งหนึ่งในวิธีที่ใช้ในการลดเวลาการ Build คือการ Cache ไฟล์ที่ไม่ได้เปลี่ยนแปลงนับจากการ Build ครั้งล่าสุด ซึ่งการ Build ครั้งแรกนี้ก็ใช้เวลาไปพอสมควร แต่ก็ใช้เวลาน้อยกว่าก่อนปรับแต่งอยู่ดี โดยใช้เวลาทั้งหมด 16725 milliseconds

<p align="center">
  <img src="./assets/task/2-19.png">
  <small>รูปที่ 2-19 การ Build Webpack ครั้งแรกหลังการปรับแต่ง</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
และเมื่อเกิดการ Cache แล้ว การ Build ครั้งถัดๆไปก็เร็วขึ้นอย่างเห็นได้ชัด ซึ่งใช้เวลาไปทั้งหมด 1671 milliseconds

<p align="center">
  <img src="./assets/task/2-20.png">
  <small>รูปที่ 2-20 การ Build Webpack หลังการปรับแต่ง และมีการ Cache</small>
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ซึ่งเวลาที่ลดลงไม่เพียงแต่เวลาสำหรับการ Build เท่านั้น แต่ยังรวมไปถึงเวลาที่ใช้ในการ Hot Module Replacement (HMR) ด้วย

### 2.7 การ Contribute กับ Open source
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
ในระหว่างการทำงาน เมื่อเจอปัญหาที่ไม่สามารถใช้ Package ของผู้อื่น หรือต้องการเพิ่ม Feature บางอย่างที่ผู้อื่นยังไม่เคยทำไว้ ก็ได้ทำการแยกส่วนนั้นออกมาเปิดเป็น Repository ใหม่แบบ Public รวมทั้งการส่ง Pull Request และ การแจ้ง Issues ซึ่งมีรายการดังนี้

##### ศุภณัฐ
* https://github.com/zugarzeeker/redux-modern-crud เพื่อให้ใช้งานร่วมกับ Middleware ของ `react-redux-universal-hot-example`
* https://github.com/zugarzeeker/modern-express-joi เพื่อให้ง่ายต่อการใช้งานระหว่าง `Joi` (ตัวช่วยในการ Validate) และ `Express` (RESTFul API Framework)
* https://github.com/typicode/json-server/issues/434 ใช้งานในการ Mock Endpoint API ของเว็บแอพพลิเคชันแหล่งรวมบริการรับสอนพิเศษ สำหรับกรณีที่ Backend ยังไม่เสร็จสมบูรณ์
* https://github.com/villadora/express-http-proxy/pull/158 แก้ไขคำผิดของ Document

##### เอกดนัย
* https://github.com/koorgoo/ngCropper/pull/34 โดยเป็นการเพิ่ม Feature ของ Module ใน AngularJS
* https://github.com/JedWatson/react-select/pull/1416 โดยเป็นการเพิ่ม Feature ของ Component ใน ReactJS
* https://github.com/blutarche/react-ui-tree โดยเป็นการเพิ่ม Feature ของ Component ใน ReactJS (แต่เนื่องจากยังไม่ได้ Refactor โค้ดให้ดีจึงยังไม่ได้ส่งเป็น Pull Request)
