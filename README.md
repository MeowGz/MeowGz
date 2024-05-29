<h3 align="center">โครงงานการศึกษาเชิงเปรียบเทียบประสิทธิภาพของโมเดลในการสร้างคำบรรยายภาพ</h3>
<h3 align="center">COMPARATIVE STUDIES ABOUT IMAGE CAPTIONING MODEL PERFORMANCE</h3>

#### ที่มาและความสำคัญ Introduction
โครงงานนี้มีเป้าหมายเพื่อเปรียบเทียบระหว่างปัญญาประดิษฐ์(AI) กับ มนุษย์โดยธรรมชาติ ว่าข้อความที่ถูกคาดการณ์ ผ่าน image-captioning A.I. หรือ ปัญญาประดิษฐ์ด้านการสร้างคำบรรยายภาพ ว่า A.I. มีความสามารถในการหลอกมนุษย์ได้หรือไม่ สามารถสร้างข้อความบรรยายภาพที่สามารถเทียบเคียงมนุษย์ได้หรือไม่ และสามารถพัฒนาต่อด้านนี้ได้อย่างไร
1.	เพื่อศึกษาหลักการทำงานของโมเดลการสร้างคำบรรยายภาพ
2.	เพื่อเปรียบเทียบประสิทธิภาพของโมเดลการสร้างคำบรรยายภาพกับคำบรรยายภาพจากมนุษย์


#### Software ที่ใช้
* Kaggle
* Accelerator TPM VM v3-8
* Python version 3.10.12
* torch version 2.1.0+cu131
* NLTK version 3.8.1
* OS version 0.6.2.post8
* numpy version 1.23.5
* pandas version 2.1.2
* Efficientnet-B3
* json 
* gc
* Google Forms
* 

#### ไฟล์และโฟลเดอร์ที่เกี่ยวข้อง
* dataset เป็นโฟลเดอร์ที่เก็บข้อมูล dataset ทั้งหมดที่ใช้

#### ขั้นตอนการทำงาน
* เข้าไปยังเว็บ https://www.kaggle.com/code/immeowg/flickr-image-captioning-tpu-tf2-glove 
* ทำการ run code แต่ละชุดเริ่มตั้งแต่
* การติดตั้ง library,software
* ติดตั้งและนำ dataset มาใช้
* ทำการจัดการข้อมูลประโยคคำบรรยายภาพ
* ติดตั้งและปรับแต่ง CNN ENCODER,RNN DECODER และ Attention Mechanism
* แบ่ง dataset เป็น training และ validation 
* เริ่มทำการประกอบสร้างโมเดล
* เริ่มทำการ training model
* เริ่มทำการใช้งานโมเดลกับ dataset ฝั่ง training
* เริ่มทำการใช้งานโมเดลกับ dataset ฝั่ง validation 
