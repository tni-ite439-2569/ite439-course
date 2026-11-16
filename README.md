# ITE-439 Mobile Application Development (Flutter)

ภาคเรียนที่ 2/2569 · คณะเทคโนโลยีสารสนเทศ หลักสูตรเทคโนโลยีสารสนเทศทางธุรกิจ

เรียนการพัฒนาแอปมือถือด้วย Flutter และ Dart 14 สัปดาห์ สัปดาห์ละ 3 ชั่วโมงในห้องปฏิบัติการ (นักศึกษา 1 คน : 1 เครื่อง) ฝึก Lab รายบุคคลทุกสัปดาห์ และทำโครงงานแอปเพื่อสังคมเป็นกลุ่มตลอดเทอม พร้อมฝึกใช้ AI เป็นผู้ช่วยเขียนโค้ดอย่างเข้าใจและตรวจสอบได้

> ประกาศ ตารางเรียน และการส่งงานทั้งหมดอยู่ใน **Microsoft Teams** ของรายวิชา repo นี้รวมเอกสารและลิงก์ที่ใช้บ่อย

## เริ่มต้นสัปดาห์ที่ 1

1. **ติดตั้งเครื่องมือ** ตาม [คู่มือติดตั้ง Flutter บน Windows](docs/ITE439_Flutter_Setup_Guide_Windows.pdf)
2. **สร้าง repo Lab ของตัวเอง** ชื่อ `ite439-labs-<รหัสนักศึกษา>` แบบ Public และติ๊ก Add a README file
3. **ดาวน์โหลด `week01-starter.zip`** จาก Teams › Files แล้วทำตามขั้นที่ 3 ในคู่มือ
4. **ส่ง L01** ใน Teams › Assignments ด้วยลิงก์ repo และลิงก์ commit

## Repo ของรายวิชา

| Repo | ใช้ทำอะไร |
| --- | --- |
| [ite439-course](https://github.com/tni-ite439-2569/ite439-course) | หน้านี้: ภาพรวมวิชา คู่มือ และกติกา |
| [ite439-starters](https://github.com/tni-ite439-2569/ite439-starters) | ไฟล์ starter รายสัปดาห์ ดาวน์โหลดได้ที่ **Releases** |
| [ite439-demos](https://github.com/tni-ite439-2569/ite439-demos) | โค้ดที่อาจารย์เขียนสดในคาบ แยกตาม tag `week01`, `week02` … |
| [ite439-project-template](https://github.com/tni-ite439-2569/ite439-project-template) | แม่แบบ repo โครงงานกลุ่ม (Lead กด **Use this template**) |

## รายการ Lab (รายบุคคล)

| Lab | สัปดาห์ | หัวข้อ |
| --- | --- | --- |
| L01 | 1 | ติดตั้งเครื่องมือและ Dart พื้นฐาน |
| L02 | 2 | Dart OOP และ async |
| L03 | 3 | Widget และ layout |
| L04 | 4 | Form และ validation |
| L05 | 5 | List, model และค้นหา |
| L06 | 6 | Navigation และข้อมูลข้ามหน้า |
| L07 | 8 | State management |
| L08 | 9 | อ่าน REST API |
| L09 | 10 | JSON, Service และ CRUD |
| L10 | 11 | Local storage |
| L11 | 12 | Firebase Authentication |
| L12 | 13 | Firestore, สิทธิ์ และ APK |

เลขสัปดาห์คือครั้งที่สอน วันเรียนจริงและกำหนดส่งดูในตารางเรียนบน Teams

## การส่งงาน

| งาน | Repo | ส่งอะไรใน Teams |
| --- | --- | --- |
| Lab รายบุคคล | `ite439-labs-<รหัส>` แยกโฟลเดอร์ `L01/` … `L12/` | ลิงก์ repo + ลิงก์ commit ของ Lab นั้น |
| โครงงานกลุ่ม | `ite439-gNN-ชื่อแอป` (Lead สร้างจาก template แล้วเชิญสมาชิกเป็น Collaborator) | ลิงก์ tag `midterm`, `api-checkin`, `final` ตามรอบส่ง (ตัวแทนกลุ่มส่งครั้งเดียว) |

## การใช้ AI

| ระดับ | ขอบเขต |
| --- | --- |
| AI-0 | ทำด้วยตนเอง ห้ามใช้ AI (สอบปลายภาคและ Quiz ตรวจพื้นฐาน) |
| AI-1 | ให้ AI อธิบาย หาสาเหตุ error หรือสร้างข้อมูลจำลอง โค้ดคำตอบต้องเขียนเอง |
| AI-2 | ให้ AI ช่วยเขียนโค้ดได้ แต่ต้องอ่าน ปรับ และทดสอบเอง |
| AI-3 | ให้ AI ช่วยร่างเอกสาร ปรับ UI และเสนอ test สำหรับงานต่อยอด |

ระดับที่อนุญาตของแต่ละงานระบุในใบงาน Lab เดี่ยวบันทึกการใช้ AI ใน `README.md` ของ Lab นั้น ส่วนงานกลุ่มบันทึกใน `AI_LOG.md` ทุกครั้งที่ใช้ ต้องอธิบายโค้ดที่ส่งได้เสมอ

## กติกา

- repo ที่ส่งงานต้องเป็น **Public** อาจารย์จึงเปิดดูได้
- commit บ่อยๆ ข้อความบอกว่าทำอะไร (`update` หรือ `final` ไม่นับ) อาจารย์ดู commit history ตอนตรวจ
- **ห้าม** commit รหัสผ่าน token API key หรือไฟล์ `google-services.json` ลงใน repo
- คำถามและปัญหาการติดตั้ง ถามในแชนเนล Teams ของรายวิชา (repo นี้ปิด Issues ไว้)
