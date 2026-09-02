# 🔮 Arcanum — 78 Tarot Oracle & Hand Gesture Recognition

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/MediaPipe-00979D?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
</p>

**Arcanum** เว็บแอปพลิเคชันดูดวงไพ่ยิปซี 78 ใบ ธีมแฟนตาซี พรีเมียม พร้อมระบบการตรวจจับสัญญาณมือ (Hand Gesture Control) ผ่านกล้อง Webcam ด้วยระบบปัญญาประดิษฐ์ MediaPipe

---

## 🌟 ฟีเจอร์หลัก (Key Features)

- **Circular Cards Motion (ตัวไพ่ไม่หมุน):** - เมื่อสั่งกระจายไพ่ กองไพ่จะขยายออกเป็นรูปวงกลมและหมุนวน
  - **ตัวไพ่แต่ละใบจะรักษาแนวตั้งตรง** ไม่หมุนเอียงตามแกน ช่วยให้ได้ visual ที่สวยงามและสบายตา
- **Hand Gesture Control (การควบคุมด้วยมือ):**
  - ✋ **กางมือ (Open Hand):** สั่งเริ่มสุ่มไพ่ (กระจายไพ่และเริ่มหมุนวน)
  - ✊ **กำมือ (Fist):** สั่งหยุดไพ่และสุ่มสุ่มเปิดไพ่พร้อมคำทำนายทันที
- **Complete 78 Tarot Cards:** ฐานข้อมูลไพ่ครบถ้วนทั้ง Major Arcana 22 ใบ และ Minor Arcana 56 ใบ (ถ้วย/คทา/ดาบ/เหรียญ)
- **Fantasy Popup Detail:** หน้าต่างแสดงผลคำทำนายพร้อมชื่อภาษาอังกฤษ-ไทย สัญลักษณ์ Line-Art และการเปลี่ยนสีธีมตามตระกูลไพ่อัตโนมัติ

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

- **HTML5 & CSS3:** พัฒนาโครงสร้าง ลำดับชั้นฟอนต์ และ Animation แบบ 2D Transform
- **JavaScript (Vanilla ES6+):** การคำนวณตำแหน่งวงกลมเชิงคณิตศาสตร์ (`Math.cos`, `Math.sin`) และ Animation Loop
- **MediaPipe Hands:** โมเดล Machine Learning ตรวจจับและวิเคราะห์ตำแหน่งข้อมือและปลายนิ้ว real-time

---

## 🚀 วิธีการใช้งาน (Getting Started)

เนื่องจากระบบต้องเรียกใช้งานกล้อง Webcam ควรเปิดใช้งานผ่าน **Local Web Server** หรือ **HTTPS**:

### เปิดด้วย VS Code (Live Server)
1. เปิดโฟลเดอร์โปรเจกต์ใน VS Code
2. คลิกขวาที่ไฟล์ `index.html` แล้วเลือก **Open with Live Server**

---

## 🎮 วิธีการเล่น (How to Play)

1. **กางมือ ✋ หน้ากล้อง:** เพื่อสั่งให้กองไพ่กระจายตัวออกและเริ่มหมุนวนสุ่ม
2. **กำมือ ✊ หน้ากล้อง:** เพื่อสั่งหยุดไพ่ และเปิดคำทำนายชะตาชีวิตของคุณ
3. (สามารถใช้ปุ่มกดบนหน้าจอหรือคลิกที่กองไพ่แทนการใช้กล้องได้เช่นกัน)
