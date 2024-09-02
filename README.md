## จุดประสงค์ของ Strapi
Strapi เป็นระบบจัดการเนื้อหาแบบไร้ส่วนหัว (Content Management System) ที่เป็น open-source ที่ช่วยให้ผู้พัฒนาสามารถสร้างและจัดการ API ได้อย่างมีประสิทธิภาพ โดยการแยกส่วนของแบ็คเอนด์ (การจัดการเนื้อหาและการจัดเก็บข้อมูล) ออกจากฟรอนต์เอนด์ (ส่วนติดต่อผู้ใช้) ทำให้ Strapi มีความยืดหยุ่นในการนำเสนอเนื้อหาบนแพลตฟอร์มหลากหลายรูปแบบ เช่น เว็บไซต์ แอปพลิเคชันมือถือ และอุปกรณ์ IoT ด้วยการออกแบบที่ให้ความสำคัญกับ API เป็นหลัก ทำให้สามารถสร้าง API ที่เป็น RESTful และ GraphQL ที่ปรับแต่งได้ตามต้องการ เหมาะสำหรับโปรเจกต์ที่ต้องการการพัฒนาอย่างรวดเร็วหรือพัฒนาร่วมกับระบบจากภายนอก

นอกจากนี้ Strapi ยังมีตัวเลือกในการปรับแต่งและขยายความสามารถที่หลากหลาย ช่วยให้ผู้พัฒนาสามารถปรับแต่งแผงควบคุมการจัดการเนื้อหา โมเดลเนื้อหา และการตอบกลับของ API ให้สอดคล้องกับความต้องการเฉพาะของโครงการ ความยืดหยุ่นนี้ทำให้ Strapi เหมาะสมกับการใช้งานที่หลากหลาย ตั้งแต่เว็บไซต์เน้นเนื้อหาธรรมดาตลอดจนถึงระดับองค์กรที่ซับซ้อนซึ่งต้องการกระบวนการทำงานและโครงสร้างข้อมูลที่ปรับแต่งได้เอง
### แหล่งอ้างอิง
- [Welcome to the Strapi Developer Docs!](https://docs.strapi.io/dev-docs/intro)<br>
- [What is Strapi, and Why You Should Use it?](https://radixweb.com/blog/what-is-strapi)<br>
- [ออกแบบสร้าง APIs แบบโคตรเร็ว, จัดการเนื้อหาแบบโคตรง่าย ด้วย Strapi Headless CMS](
https://medium.com/@themaxaboy/%E0%B8%AD%E0%B8%AD%E0%B8%81%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-apis-%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B9%82%E0%B8%84%E0%B8%95%E0%B8%A3%E0%B9%80%E0%B8%A3%E0%B9%87%E0%B8%A7-%E0%B8%88%E0%B8%B1%E0%B8%94%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%99%E0%B8%B7%E0%B9%89%E0%B8%AD%E0%B8%AB%E0%B8%B2%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B9%82%E0%B8%84%E0%B8%95%E0%B8%A3%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-strapi-headless-cms-da907437040)

## กรณีการใช้งานของ Strapi
- **เว็บไซต์และแอปพลิเคชันที่เน้นเนื้อหา:** Strapi เหมาะสำหรับการพัฒนาเว็บไซต์และแอปพลิเคชันที่มีเนื้อหาจำนวนมาก ซึ่งต้องการการอัปเดตเนื้อหาอย่างต่อเนื่องและส่งต่อผ่านช่องทางหลากหลาย สถาปัตยกรรมแบบไร้ส่วนหัวของ Strapi ช่วยให้สามารถผสานการทำงานกับเทคโนโลยีฟรอนต์เอนด์ต่าง ๆ ได้อย่างไร้รอยต่อ เช่น React, Vue.js และ Angular

- **แพลตฟอร์มอีคอมเมิร์ซ:** Strapi สามารถใช้จัดการข้อมูลสินค้า ประเภทสินค้า รีวิวผู้ใช้ และเนื้อหาแบบไดนามิกอื่น ๆ ในแอปพลิเคชันอีคอมเมิร์ซ ด้วยแนวทางที่เน้น API เป็นหลัก ทำให้ง่ายต่อการผสานการทำงานกับระบบชำระเงิน ระบบการจัดการสินค้าคงคลัง และบริการของบุคคลที่สามต่าง ๆ

- **แอปพลิเคชันมือถือ:** โดยใช้ Strapi เป็นแบ็กเอนด์ ผู้พัฒนาสามารถสร้างและจัดการเนื้อหาสำหรับแอปพลิเคชันมือถือได้อย่างมีประสิทธิภาพมากขึ้น API ที่ Strapi ให้มาสามารถส่งเนื้อหาไปยังทั้งแพลตฟอร์ม iOS และ Android โดยไม่จำเป็นต้องมีแบ็กเอนด์แยกต่างหากสำหรับแต่ละแพลตฟอร์ม

- **แอปพลิเคชันระดับองค์กร:** ความยืดหยุ่นและการปรับขยายของ Strapi ทำให้เหมาะสมสำหรับแอปพลิเคชันระดับองค์กรที่ต้องการความซับซ้อนของความสัมพันธ์ของข้อมูลและกระบวนการทำงาน บริษัทสามารถปรับแต่ง Strapi ให้เหมาะกับความต้องการทางธุรกิจเฉพาะ รวมถึงผสานรวมกับระบบที่มีอยู่แล้วและขยายขนาดตามความจำเป็น
### แหล่งอ้างอิง
- [Live Demo | Strapi the leading open-source headless CMS](https://strapi.io/demo)<br>
- [An in-depth review of using Strapi in a real-world application](https://levelup.gitconnected.com/should-i-use-strapi-on-my-next-project-ec2daa7df11c)<br>
- [Use Cases of Strapi 2024](https://levelup.gitconnected.com/should-i-use-strapi-on-my-next-project-ec2daa7df11c)

## ส่วนประกอบหลักต่าง ๆ ของ Strapi

**Content Types Builder:** เป็นเครื่องมือที่ใช้งานง่าย ซึ่งช่วยให้เราสามารถกำหนดและจัดโครงสร้างโมเดลข้อมูลสำหรับแอปพลิเคชันได้โดยไม่ต้องเขียนโค้ด มีอินเตอร์เฟซที่เข้าใจง่ายสำหรับการสร้างประเภทเนื้อหาใหม่และปรับแต่งฟิลด์ต่าง ๆ เช่น ข้อความ ตัวเลข วันที่ และสื่อ รวมถึงการกำหนดความสัมพันธ์ระหว่างประเภทเนื้อหาต่าง ๆ คุณสมบัตินี้ช่วยให้เราสามารถสร้างโครงสร้างข้อมูลที่ซับซ้อนได้อย่างง่ายดาย ทำให้เป็นเครื่องมือที่ทรงพลังในการตั้งค่าแบ็กเอนด์ของแอปพลิเคชัน

**Content Manager:** เป็นอินเตอร์เฟซที่ใช้ในการจัดการการบันทึกเนื้อหาจริงตามประเภทเนื้อหาที่เราได้กำหนดไว้ ช่วยให้ผู้ใช้สามารถสร้าง แก้ไข และจัดระเบียบการบันทึกเนื้อหาผ่านอินเตอร์เฟซที่เป็นภาพ ซึ่งมีฟังก์ชันต่าง ๆ เช่น การค้นหา การกรอง และการจัดการสถานะการเผยแพร่ นอกจากนี้ ยังมีการแสดงผลข้อมูลในรูปแบบที่เป็นระเบียบและอิงตามสิทธิ์ของผู้ใช้ ทำให้การจัดการเนื้อหามีประสิทธิภาพและปลอดภัย

### แหล่งอ้างอิง
- [Strapi APIs to access your content](https://docs.strapi.io/dev-docs/api/content-api)<br>
- [Introduction to the Content-type Builder](https://docs.strapi.io/user-docs/content-type-builder)<br>
- [Introduction to the Content Manager](https://docs.strapi.io/user-docs/content-manager)<br>
- [Managing content-types](https://docs.strapi.io/user-docs/content-type-builder/managing-content-types)<br>

## ติดตั้ง Strapi
**สิ่งที่ต้องติดตั้งก่อนการติดตั้ง Strapi**
- Node.js `v18` หรือ `v20` (ในครั้งนี้เราเลือกใช้ `v20`) ตรวจสอบว่าติดตั้งแล้วโดยใช้คำสั่ง
```
node -v
```
- เลือก Node.js package manager ที่ต้องการระหว่าง `yarn` หรือ `npm` (ในที่นี้เราเลือกใช้ `npm`) ตรวจสอบว่าติดตั้งแล้วโดยใช้คำสั่ง
```
npm -v
```
*หมายเหตุ: หากเลือกใช้ `npm` จะต้องเป็น `v6` หรือสูงกว่า*

**ขั้นตอนการสร้างโปรเจกต์ของ Strapi**
1. เปืด Terminal
2. `cd` ไปยังโฟลเดอร์ที่ต้องการ
3. จากนั้นให้รันคำสั่งต่อไปนี้
```
npx create-strapi-app@latest my-project --quickstart
```
4. จากนั้นให้รันคำสั่งต่อไปนี้<br>
```
cd my-project
```

```
npm install
```

```
npx run develop
```
5. เข้า http://localhost:1337/admin/auth/login เพื่อทำการสมัครและล็อกอินเข้าใช้งานระบบ
### แหล่งอ้างอิง
- [Installing from CLI](https://docs.strapi.io/dev-docs/installation/cli)

## นำโค้ดลง GitHub
1. ในเทอร์มินัล ตรวจสอบว่ายังคงอยู่ในโฟลเดอร์ของโปรเจ็กต์ Strapi ที่สร้างขึ้น
2. รันคำสั่ง `git init` เพื่อเริ่มต้น git สำหรับโฟลเดอร์นี้
3. รันคำสั่ง `git add .` เพื่อเพิ่มไฟล์ที่แก้ไขทั้งหมดลงใน git
4. รันคำสั่ง `git commit -m "Initial commit"` เพื่อสร้างคอมมิตที่มีการเปลี่ยนแปลงที่เพิ่มเข้ามาทั้งหมด
5. เข้าสู่ระบบบัญชี GitHub ของคุณและสร้าง repository ใหม่
6. กลับไปที่เทอร์มินัลและ push local repository ในเครื่องคุณลง GitHub:
   - เรียกใช้คำสั่งที่คล้ายกับต่อไปนี้: `git remote add origin https://github.com/Teerapat6509650468/CS360-Strapi-6509650468.git` โดยเปลี่ยนส่วน `https://github.com/Teerapat6509650468/CS360-Strapi-6509650468.git` เป็นลิ้งก์ repository ของคุณแทน
   - รันคำสั่ง `git push --set-upstream origin main` เพื่อส่งการคอมมิตไปยัง repository บน GitHub ของคุณ
  
### แหล่งอ้างอิง
- [Installing from CLI](https://docs.strapi.io/dev-docs/installation/cli)

## นำ Strapi Project ขึ้นบน EC2
**EC2 Instance Spec**
- Instance Type : t2.medium
- Operating System : Ubuntu 24.04
- Storage : 8 gb

**Security Group Rules**
- Type: `SSH`, Protocol: `TCP`, Port Range `22`, Source: `::/0`
- Type: `HTTP`, Protocol: `TCP`, Port Range `80`, Source: `0.0.0.0/0, ::/0`
- Type: `HTTPS`, Protocol: `TCP`, Port Range `443`, Source: `0.0.0.0/0, ::/0`
- Type: `Custom TCP Rule`, Protocol: `TCP,` Port Range `1337`, Source: `0.0.0.0/0`

**วิธีการนำขึ้นบน EC2**
1. ทำการเข้าถึง EC2 Instance ที่สร้างด้วย SSH (เช่น `ssh -i "StrapiKey.pem" ubuntu@ec2-54-226-105-3.compute-1.amazonaws.com`)
2. รันคำสั่งต่อไปนี้เพื่อติดตั้ง Nodejs

   
   ```
   sudo apt update
   ```
   ```
   sudo apt install unzip
   ```
   ```
   curl -fsSL https://fnm.vercel.app/install | bash
   ```
   ```
   source ~/.bashrc
   ```
   ```
   fnm use --install-if-missing 20
   ```
   ```
   node -v && npm -v
   ```
   หลังจากรันคำสั่ง `node -v && npm -v` แล้วขึ้นตัวเลขอย่างเช่น `v20.x` และ `v10.x` เป็นอันว่าติดตั้ง nodejs เสร็จสมบูรณ์


 3. ตั้งค่า default directory ของ npm
 ```
 cd ~
 ```
 ```
 mkdir ~/.npm-global
 ```
 ```
 npm config set prefix '~/.npm-global'
 ```
 สร้างหรือแก้ไขไฟล์ `~/.profile`
 ```
 sudo nano ~/.profile
 ```
 เพิ่มส่วนด้านล่างนี้ลงบนท้ายสุดของไฟล์ `~/.profile`
 ```
 # set PATH so global node modules install without permission issues
 export PATH=~/.npm-global/bin:$PATH
 ```
 อัพเดทตัวแปรของระบบ
 ```
 source ~/.profile
 ```

 4. ตรวจสอบว่ามี Git อยู่บน EC2 Instance ด้วยคำสั่ง `git --version` หากไม่มีให้ติดตั้งด้วยคำสั่ง `sudo apt install git -y`

 5. คัดลอก repository ของ Strapi project บน GitHub ลงบน EC2 Instance ด้วยคำสั่ง
 ```
 git clone <your repository url>
 ```

 6. `cd` เข้าสู่โฟลเดอร์ที่คัดลอกมา
 7.  รันคำสั่งต่อไปนี้
 ```  
 npm install
 ```
 ```
 NODE_ENV=production npm run build
 ```
 8. ในโฟลเดอร์ของ Strapi ให้สร้างไฟล์ `.env` 
 ```
 touch .env
 ```
 9. คัดลอกเนื้อหาจากไฟล์ `.env` ที่อยู่บนเครื่องของคุณมาวางลงบนไฟล์ `.env` ที่อยู่ใน EC2 Instance ในส่วนท้ายไฟล์ให้เพิ่ม `NODE_ENV=production`
 ```
 nano .env
 ```
 10. รันเซิร์ฟเวอร์ด้วยคำสั่ง
 ```
 npm start
 ```
### แหล่งอ้างอิง
[Strapi | Amazon AWS - Deployment](https://docs.strapi.io/dev-docs/deployment/amazon-aws)

## `.gitignore`
### จุดประสงค์ของ `.gitignore`
`.gitignore` เป็นไฟล์ที่มีความสำคัญอย่างมากในการจัดการไฟล์และไดเรกทอรีใด ๆ ก็ตามที่ Git ควรเพิกเฉยในโปรเจกต์ ซึ่งช่วยให้ repository สะอาดโดยการยกเว้นไฟล์ที่ไม่จำเป็น นอกจากนี้ ยังช่วยปกป้องข้อมูลที่อ่อนไหว และปรับปรุงประสิทธิภาพจากการป้องกันไม่ให้ Git ติดตามไฟล์ที่มีขนาดใหญ่หรือไฟล์ที่ไม่เกี่ยวข้อง

### การใช้ `.gitignore` ในโปรเจกต์ JavaScript**
ในโปรเจ็กต์ JavaScript ไฟล์ `.gitignore` ถือเป็นสิ่งสำคัญสำหรับการจัดการไฟล์ที่สร้างขึ้นระหว่างการพัฒนาแต่ไม่จำเป็นต้องใช้ใน repository โดยเหตุผลถึงความสำคัญของไฟล์ `.gitignore` ต่อโปรเจกต์ JavaScript มีดังนี้: 

- **ไดเรกทอรี Node Modules:** ไดเรกทอรี `node_modules` ถูกสร้างขึ้นโดยอัตโนมัติโดยแพ็กเกจเมเนเจอร์ (`npm` หรือ `yarn`) และมีการพึ่งพาที่โปรเจกต์ของคุณต้องการ ไฟล์เหล่านี้มักจะมีขนาดใหญ่และเฉพาะเจาะจงสำหรับแพลตฟอร์ม ทำให้ไม่เหมาะสมสำหรับการควบคุมเวอร์ชัน

- **ไฟล์บันทึก:** ระหว่างการพัฒนา อาจมีการสร้างไฟล์บันทึก (`*.log`) ซึ่งโดยทั่วไปแล้วไม่เป็นประโยชน์สำหรับการควบคุมเวอร์ชัน และสามารถมีขนาดใหญ่ได้อย่างรวดเร็ว

- **ไฟล์สภาพแวดล้อม:** ไฟล์เช่น `.env` มีตัวแปรที่เฉพาะเจาะจงสำหรับสภาพแวดล้อม เช่น คีย์ API หรือ URL ของฐานข้อมูล ซึ่งควรจะเก็บไว้เป็นความลับ

- **ไฟล์ที่เป็นผลลัพธ์จากการสร้างโปรแกรม:** ไฟล์ในไดเรกทอรี `dist/` หรือ `build/` หรือไฟล์ใด ๆ ที่เป็นผลลัพธ์ของกระบวนการสร้าง ควรได้รับการยกเว้นจาก repository เพื่อหลีกเลี่ยงการทำให้ repository มีขนาดใหญ่เกินไปจากไฟล์ไบนารีที่สามารถสร้างใหม่ได้"**

### แหล่งอ้างอิง
[Ignoring files - GitHub Docs](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)
