# Assignment: Check Integer Number with JavaScript

โปรแกรมนี้เขียนด้วยภาษา **JavaScript** เพื่อรับ input จากผู้ใช้ผ่าน `prompt()` บน web browser  
แล้วตรวจสอบว่าเป็น  
- เลขคู่ (even integer number)  
- เลขคี่ (odd integer number)  
- หรือศูนย์ (zero integer number)  

จากนั้นจะแสดงผลลัพธ์ผ่าน `alert()` popup

---

```
.
├── index.html   # ไฟล์หลักที่มีโค้ด JavaScript
└── README.md    # คำอธิบายโปรเจค
```

---

1. Clone repository มาที่เครื่อง
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>
   ```

2. เปิดไฟล์ `index.html` ด้วย Web Browser (Chrome, Firefox, Edge ฯลฯ)

3. จะมี **popup** เด้งขึ้นมาให้กรอกค่า input → กรอกตัวเลขแล้วกด OK เพื่อดูผลลัพธ์

---

- กรอก `10`  
  **Output:** `"even integer number"`

- กรอก `5`  
  **Output:** `"odd integer number"`

- กรอก `0`  
  **Output:** `"zero integer number"`

- กรอก `abc` (ไม่ใช่ตัวเลข)  
  **Output:** `"Invalid input! Please enter an integer."`

---