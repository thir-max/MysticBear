# 🔮 Arcanum — 78 Tarot Oracle & Gesture Control

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/MediaPipe-00979D?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
</p>

**Arcanum** เว็บแอปพลิเคชันดูดวงไพ่ยิปซี 78 ใบ ธีมแฟนตาซี พรีเมียม พร้อมระบบการตรวจจับสัญญาณมือ (Hand Gesture Control) ผ่านกล้อง Webcam ด้วยระบบปัญญาประดิษฐ์ MediaPipe

---

## 🌟 ฟีเจอร์หลัก (Key Features)

- **Horizontal Ellipse Spread (วงรีแนวนอนไม่ซ้อนกัน):**
  - กองไพ่ขยายตัวสุ่มวนเป็นแนววงรีแนวนอน (Horizontal Ellipse) กว้างเต็มพื้นที่หน้าจอ
  - ตัวไพ่ตั้งตรงสวยงาม กระจายตัวในมุมที่เท่ากัน ไม่ทับซ้อนกัน
- **Complete Reading & Prediction:**
  - เมื่อหยุดสุ่มไพ่ จะแสดง **ชื่อไพ่ (ภาษาอังกฤษและภาษาไทย)**, สัญลักษณ์ตระกูลไพ่, **คำสำคัญ (Keywords)** และ **บททำนายความหมายอย่างสมบูรณ์**
- **Hand Gesture Control (การควบคุมด้วยมือ):**
  - ✋ **กางมือ (Open Hand):** สั่งเริ่มสุ่มไพ่ (กระจายวนเป็นวงรี)
  - ✊ **กำมือ (Fist):** สั่งหยุดหมุนและสุ่มทำนายไพ่ทันที
- **78 Cards Database:** ครอบคลุม Major Arcana 22 ใบ และ Minor Arcana 56 ใบ (ถ้วย/คทา/ดาบ/เหรียญ)

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

- **HTML5 & CSS3:** โครงสร้างและสไตล์ลิ่งระดับพรีเมียม 
- **JavaScript (Vanilla ES6+):** การคำนวณตำแหน่งวงรีแนวนอนแบบตรีโกณมิติ (`Math.cos`, `Math.sin`)
- **MediaPipe Hands:** โมเดล Machine Learning ตรวจจับตำแหน่งข้อมือและปลายนิ้ว real-time

---

## 🎮 วิธีการเล่น (How to Play)

1. **กางมือ ✋ หน้ากล้อง:** สั่งให้กองไพ่กระจายวนเป็นวงรีแนวนอน
2. **กำมือ ✊ หน้ากล้อง:** สั่งหยุดหมุนไพ่ เพื่อสุ่มและเปิดอ่านคำทำนาย
3. (สามารถใช้ปุ่มกดมุมขวาล่าง หรือคลิกที่กองไพ่แทนการใช้กล้องได้เช่นกัน)
