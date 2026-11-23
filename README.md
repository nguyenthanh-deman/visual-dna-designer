# Visual DNA Designer

Skill cho Claude giúp thiết kế **DNA visual nhận diện** cho một kênh content (TikTok, Reels, Shorts...). Skill chọn 9 yếu tố hình thức cố định để mọi video trong kênh đều có dấu ấn riêng:

1. Phong cách tổng thể
2. Góc quay
3. Ngôn ngữ và caption
4. Màu sắc và ánh sáng
5. Font chữ và cách hiện text
6. Âm thanh và giọng
7. Tương tác với người xem
8. Nhịp dựng và hiệu ứng
9. Cách nhân vật xuất hiện

Sau đó chọn một **signature** lặp lại ở mọi video (âm thanh, hình ảnh, câu nói hoặc mascot). Kết quả là một trang `visual-dna.html` gồm 9 thẻ lựa chọn, bảng màu, font, kênh tham khảo, checklist tuân thủ và SOP cho team.

## Cấu trúc

| File | Nội dung |
|---|---|
| `SKILL.md` | Quy trình 4 bước và hướng dẫn cho AI |
| `references/9-yeu-to-visual.md` | Chi tiết các lựa chọn của 9 yếu tố |
| `templates/visual-dna.html` | Mẫu board nhận diện để render kết quả |

## Cài đặt

**Claude Code:** chép thư mục này vào `~/.claude/skills/visual-dna-designer/`.

**Claude.ai:** nén thư mục thành `.zip` rồi tải lên ở Settings → Capabilities → Skills.

Gọi skill bằng cách nói "thiết kế DNA visual cho kênh..." hoặc "9 yếu tố visual".

---

Deman AI Lab · [demanlab.ai](https://www.demanlab.ai)
