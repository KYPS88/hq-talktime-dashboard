# hq-talktime-dashboard

เว็บรวม **Talktime Center** ของ INFINITY BLU8 (เสิร์ฟผ่าน GitHub Pages)

| ไฟล์ | หน้าที่ | ใครอัปเดต |
|---|---|---|
| `index.html` | 🏠 หน้าแรก — เปรียบเทียบ 2 สาขา (HQ × RAMA2) | ไฟล์คงที่ แก้มือเท่านั้น — workflow **ห้ามทับ** |
| `hq.html` | 🏢 แดชบอร์ดเต็มสาขา HQ RAM | auto จาก `hq-talktime-scripts` (ทุกชั่วโมง) |
| `payload.json` | ข้อมูล KPI ของ HQ ที่หน้าแรกใช้ | auto จาก `hq-talktime-scripts` |
| `data.json` ฯลฯ | state files ของ pipeline | auto |

แดชบอร์ดสาขา RAMA2 อยู่ที่ repo [`rama2-talktime-dashboard`](https://github.com/KYPS88/rama2-talktime-dashboard) — หน้าแรกดึง `payload.json` ข้าม repo ผ่าน GitHub Pages (CORS เปิดให้อยู่แล้ว)

เมนูบนทุกหน้า: 🏠 ภาพรวม 2 สาขา · 🏢 HQ RAM · 🌊 RAMA2
