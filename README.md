# โหมดแชทเร็ว · Fast Chat Mode

A Claude Code skill for **Lovable-style UI iteration in any project**: you type a change, Claude makes it and you see it in the preview pane right away. Claude also proposes better approaches and fixes small issues it spots — and always tells you. Nothing is fully checked or shipped until you say **"จบรอบ"** (end round); then everything is verified once and shipped as a single PR.

สกิลสำหรับ Claude Code — แก้หน้าจอแบบ Lovable ในโปรเจคไหนก็ได้: พิมพ์สั่งแก้ทีละข้อ ดูผลในพาแนลทันที Claude ช่วยคิด เสนอ และทำเพิ่มได้ (บอกเสมอ) ตรวจเต็มและขึ้นเว็บทีเดียวตอนพิมพ์ "จบรอบ"

## ใช้ยังไง · Usage

| คุณพิมพ์ · You type | เกิดอะไร · What happens |
|---|---|
| `เริ่มโหมดแชทเร็ว` / `fast chat mode` | เริ่มรอบ: อ่านกติกาโปรเจค · แตก branch · เปิดพรีวิว · จดขนาดพาแนลของคุณ |
| สั่งแก้ทีละข้อ · any change | แก้ → typecheck สั้น ๆ → ดูที่ขนาดพาแนลจริง → commit ทีละเรื่อง (ยังไม่ PR) |
| — | ~10 เรื่อง / ครึ่งวัน: Claude **แนะนำ**ให้ปิดรอบ (ไม่ปิดเอง) |
| `จบรอบ` / `end round` | ตรวจเต็ม (จอคุณ + มือถือ · สว่าง/มืด · ความต่างสี · เทสต์) → จดคำเคาะทีเดียว → PR เดียว → ขึ้นเว็บ → สรุป |

## ติดตั้ง · Install

```bash
git clone https://github.com/trin-zenityx/fast-chat-mode ~/.claude/skills/fast-chat-mode
```

Project-specific details (check commands, PR flow, decision log, write guards) are read from each project's own `CLAUDE.md` / memory — the skill stays generic.

From ZenityX — จับมือทำจริง ใช้ได้จริง · Hands-on AI. Real results.
