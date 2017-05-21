# How to install-nodejs on cloud

บทความนี้ผมจะขออธิบายเกี่ยวกับการติดตั้ง Nodejs บนเซิร์ฟเวอร์กันนะครับ (แต่กรณีนี้สำหรับคนที่มีเซิร์ฟเวอร์อยู่แล้ว) ส่วนคนที่ยังไม่มีก็สามารถไปศึกษาเกี่ยวกับการติดตั้งเซิร์ฟเวอร์ก่อนนะครับ เอาไว้ถ้ามีโอกาสผมจะมานำเสนอ บทความเกี่ยวกับการใช้งานและวิธีลงทะเบียนเพื่อใช้งานเซิร์ฟบนคลาว ของทาง Google ซึ่งเปิดให้เราใช้งานได้ฟรีๆ 1 ปีเต็ม ไม่เลวเลยใช่มั้ยครับสำหรัลเซิร์ฟเวอร์ฟรี แต่จริงๆก็มีอีกหลายค่ายนะครับที่ทำออกมาให้เราได้ใช้ฟรี นอกจาก Google ก็ยังมีอีกสองค่ายใหญ่คือ Amazon และ IBM ซึ่งก็น่าจะรู้จักกันดีอยู่แล้วหรือไม่ก็ต้องเคยผ่านหูมาบ้าง ลองไปศึกษาดูนะครับ

Step 1.
Install node package manager โดยใช้ apt (advance package tool).
![](https://raw.githubusercontent.com/sermsaksukprasert/install-nodejs/master/1.png)

Step 2.
ตอบ Y เลยครับ = เพื่อยอมรับการติดตั้ง advance package tool.
![](https://raw.githubusercontent.com/sermsaksukprasert/install-nodejs/master/2.png)

Step 3.
ติดตั้ง node package manager n global หรือเรียกง่ายๆคือ npm install n -g.
![](https://raw.githubusercontent.com/sermsaksukprasert/install-nodejs/master/3.png)

Step 4.
ติดตั้ง package n ให้เป็นเวอร์ชั่นล่าสุดนะครับ
![](https://raw.githubusercontent.com/sermsaksukprasert/install-nodejs/master/4.png)

Step 5.
เราสามารถตรวจสอบได้ครับว่าเป็นเวอร์ชั่นล่าสุดหรือยังโดยใช้คำสั่ง node -v, เพียงเท่านี้ก็สามารถใช้งาน nodejs ได้แล้วครับ!!!
![](https://raw.githubusercontent.com/sermsaksukprasert/install-nodejs/master/5.png)
