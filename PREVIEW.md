# Preview — เทียบ code block 3 แบบ

เปิดหน้านี้บน GitHub แล้วดูว่าแบบไหนถูกใจ แล้วบอกหมายเลขมา

---

## แบบ 1 — `console` (ของที่ push ไปแล้วตอนนี้)

```console
$ ltd status
research   Physical AI — VLA, diffusion policy
learning   FRA503 Deep RL · Isaac Lab
shipped    ESP32 pump controller — watchdog, OTA
running    homelab — Pi 4, n8n, Home Assistant
building   LTD OS — personal ops + AI companion
```

GitHub ทาสีบรรทัด output เป็นสีเด่น ส่วนบรรทัดคำสั่งกลับจาง — กลับด้านกับที่ควรเป็น

---

## แบบ 2 — บล็อกเปล่า ไม่ระบุภาษา

```
$ ltd status
research   Physical AI — VLA, diffusion policy
learning   FRA503 Deep RL · Isaac Lab
shipped    ESP32 pump controller — watchdog, OTA
running    homelab — Pi 4, n8n, Home Assistant
building   LTD OS — personal ops + AI companion
```

ทุกบรรทัดสีเดียวกัน สะอาด `$` ยังบอกได้ว่าเป็น terminal

---

## แบบ 3 — บล็อกเปล่า + เส้นคั่นหัว

```
$ ltd status
─────────────────────────────────────────
research   Physical AI — VLA, diffusion policy
learning   FRA503 Deep RL · Isaac Lab
shipped    ESP32 pump controller — watchdog, OTA
running    homelab — Pi 4, n8n, Home Assistant
building   LTD OS — personal ops + AI companion
```

เส้นคั่นทำให้บรรทัดคำสั่งแยกออกจาก output ชัดขึ้นโดยไม่ต้องพึ่งสี

---

## แบบ 4 — ไม่มีคำสั่ง เหลือแต่สถานะ

```
research   Physical AI — VLA, diffusion policy
learning   FRA503 Deep RL · Isaac Lab
shipped    ESP32 pump controller — watchdog, OTA
running    homelab — Pi 4, n8n, Home Assistant
building   LTD OS — personal ops + AI companion
```

ตัดปัญหา "คำสั่งปลอม" ทิ้งไปเลย เหลือแค่ลิสต์จัดคอลัมน์
