# 🔒 Security Requirement: 
## 5.1.1 Input Validati  

## ✨ Detail  
Verify that the application has defenses against HTTP parameter pollution
attacks, particularly if the application framework makes no distinction about
the source of request parameters (GET, POST, cookies, headers, or
environment variables).  

---

## 💡 Explanations from Different AI Models  

### 🤖 ChatGPT  
การโจมตี HTTP Parameter Pollution (HPP) เป็นเทคนิคที่ผู้โจมตีแทรก พารามิเตอร์ที่ซ้ำกัน หรือ ดัดแปลงพารามิเตอร์ ในคำขอ HTTP (GET, POST, Cookies, Headers หรือ Environment Variables) เพื่อหลีกเลี่ยงการตรวจสอบความปลอดภัยหรือเปลี่ยนแปลงพฤติกรรมของแอปพลิเคชัน

### 🔮 Gemini  
การตรวจสอบการป้องกัน HTTP Parameter Pollution
HTTP Parameter Pollution (HPP) คือช่องโหว่ด้านความปลอดภัยที่ผู้โจมตีสามารถใช้ประโยชน์จากวิธีที่แอปพลิเคชันจัดการกับพารามิเตอร์ HTTP ที่ซ้ำกันในคำขอเดียว  โดยทั่วไปแล้ว แอปพลิเคชันบางตัวอาจใช้ค่าพารามิเตอร์แรกที่พบ ในขณะที่บางตัวอาจใช้ค่าสุดท้าย หรือบางตัวอาจใช้ค่าทั้งหมดในรูปแบบอาร์เรย์  ผู้โจมตีสามารถใช้ประโยชน์จากความแตกต่างนี้เพื่อเปลี่ยนแปลงพฤติกรรมของแอปพลิเคชัน เช่น การเข้าถึงโดยไม่ได้รับอนุญาต การข้ามการตรวจสอบ หรือการเปลี่ยนแปลงข้อมูล  

### 🌟 Myself  
การโจมตี HPP สามารถส่งผลต่อความปลอดภัยของระบบได้อย่างร้ายแรง ดังนั้นแอปพลิเคชันต้องมีการกรองและตรวจสอบพารามิเตอร์อย่างรอบคอบเพื่อป้องกันช่องโหว่นี้  

---
