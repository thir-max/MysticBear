# 🔮 Arcanum — 78 Tarot Oracle & Hand Gesture Recognition

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/MediaPipe-00979D?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/License-MIT-gold?style=for-the-badge" alt="License" />
</p>

**Arcanum** คือเว็บแอปพลิเคชันดูดวงไพ่ยิปซีแบบ interactive ครบทั้ง 78 ใบ นำเสนอด้วยงานดีไซน์สไตล์แฟนตาซี ลึกลับ และหรูหรา มาพร้อมกับระบบสุ่มไพ่แบบวงกลมหมุนวนรอบศูนย์กลาง (โดยตัวไพ่ตั้งตรงไม่หมุนเอียง) และฟีเจอร์ไฮไลต์อย่าง **Hand Gesture Control** ที่ใช้ปัญญาประดิษฐ์ในการตรวจจับการกำมือเพื่อหยุดการสุ่มไพ่ผ่านกล้อง Webcam

---

## 🌟 ฟีเจอร์เด่น (Key Features)

- **ฐานข้อมูลไพ่ยิปซีครบ 78 ใบ (Complete 78-Card Deck):** - **Major Arcana 22 ใบ:** ตั้งแต่ *The Fool (0)* จนถึง *The World (XXI)*
  - **Minor Arcana 56 ใบ:** ครบทั้ง 4 ตระกูล ได้แก่ ถ้วย (Cups), คทา (Wands), ดาบ (Swords) และเหรียญ (Pentacles)
- **ระบบสุ่มไพ่และ Animation สเปรดวงกลม (Circular Scatter Animation):**
  - เมื่อคลิกเริ่มไพ่จะกระจายตัวออกจากกองเป็นทรงกลม
  - ตัวไพ่แต่ละใบจะรักษาแนวตั้งตรง (ไม่หมุนเอียงตามแกน) ในขณะที่ทั้งวงหมุนวนอย่างนุ่มนวล
- **ระบบตรวจจับท่าทางมือผ่านกล้อง (MediaPipe Hand Gesture Tracking):**
  - ควบคุมการหยุดไพ่ด้วยการ **กำมือ ✊ (Fist Detection)** ค้างไว้หน้ากล้อง
  - มีระบบสลับไปใช้การคลิกปุ่มแทนได้ หากไม่อนุญาตการเข้าถึงกล้อง
- **Pop-up รายละเอียดพร้อมดีไซน์ระดับ พรีเมียม (Esoteric & Magical UI):**
  - แสดงผลสัญลักษณ์ Line-Art, ชื่อไพ่ภาษาอังกฤษ-ไทย, สรุปคีย์เวิร์ดสำคัญ และคำทำนายอย่างครบถ้วน
  - ระบบเปลี่ยนสีธีมหลัก (Accent Color) ตามตระกูลของไพ่ที่จับได้แบบไดนามิก

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

* **HTML5 / CSS3 (Vanilla Code):** ใช้เทคนิค CSS Flexbox, Grid, 3D Perspective, CSS Variables และ Custom Animations
* **JavaScript (ES6+):** ใช้ Web Animations API, Math Algorithms สำหรับการจัดตำแหน่งวงกลม และ Event Loop
* **MediaPipe Hands (Google AI):** โมเดล Machine Learning แบบ Real-time บนเบราว์เซอร์สำหรับตรวจจับ พิกัดมือ (Hand Landmarks)
* **Google Fonts:**
  * `Cinzel Decorative` & `Cinzel` (สำหรับหัวข้อภาษาอังกฤษสไตล์คลาสสิก)
  * `Charmonman` & `Taviraj` (สำหรับภาษาไทยสไตล์แฟนตาซีและเนื้อหาอ่านง่าย)

---

## 🚀 วิธีการใช้งาน (Getting Started)

เนื่องจากโปรเจกต์นี้มีฟีเจอร์การดึงภาพจากกล้อง Webcam (MediaPipe) การเปิดไฟล์ `index.html` ตรงๆ ผ่านระบบไฟล์ (`file:///`) อาจทำให้เบราว์เซอร์บล็อกการทำงานของกล้องได้ตามนโยบายความปลอดภัย

แนะนำให้รันโปรเจกต์ผ่าน **Local Web Server** ด้วยวิธีใดวิธีหนึ่งดังนี้:

### วิธีที่ 1: รันด้วย VS Code (Extension Live Server)
1. เปิดโฟลเดอร์โปรเจกต์ในโปรแกรม **VS Code**
2. ติดตั้งส่วนขยาย (Extension) ชื่อ **Live Server**
3. คลิกขวาที่ไฟล์ `index.html` แล้วเลือก **Open with Live Server**

### วิธีที่ 2: รันด้วย Python Server (ผ่าน Terminal)
1. เปิด Terminal หรือ Command Prompt ในโฟลเดอร์โปรเจกต์
2. ป้อนคำสั่ง:
   ```bash
   python -m http.server 8000
