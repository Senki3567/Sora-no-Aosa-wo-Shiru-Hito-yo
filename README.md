# Her Blue Sky (Sora no Aosa wo Shiru Hito yo - 2019)
### Kho Lưu Trữ Phụ Đề Chuẩn Xưởng & Dự Án Bản Dịch Tiếng Việt

Dự án tái lập và hoàn thiện bản phụ đề chuẩn xưởng cho movie anime **"Sora no Aosa wo Shiru Hito yo"** (2019).

---

## 📌 Thành Phần Dự Án

- **File Master Baseline**: [`Her.Blue.Sky.2019.1080p.BluRay.Dual-Audio.Opus.5.1.x265-YURASUKA.ass`](./Her.Blue.Sky.2019.1080p.BluRay.Dual-Audio.Opus.5.1.x265-YURASUKA.ass)
  - Phân vùng cấu trúc rõ ràng: `[THOẠI]` (1,471 dòng), `[SIGN]` (1,459 dòng), `[SONG]` (115 dòng).
  - Đã thẩm định và xác thực 100% người nói (`Actor`) khớp theo Netflix Closed Captions và kịch bản Blu-ray.
- **Tài liệu bàn giao Phase 2**: [`HANDOFF_VIETNAMESE_LOCALIZATION.md`](./HANDOFF_VIETNAMESE_LOCALIZATION.md) — Chi tiết ma trận xưng hô toàn bộ nhân vật, danh mục lỗi dịch cần tránh và quy chuẩn kỹ thuật.
- **Bảng đối soát dữ liệu**: [`thoai_full_alignment.tsv`](./thoai_full_alignment.tsv) — Bảng đối soát 1:1 từng dòng cue tiếng Anh, tiếng Nhật gốc, nhãn người nói và thời gian.
- **Bộ công cụ & Skill kiểm định**: [`ass-studio-skill.zip`](./ass-studio-skill.zip) — Gói skill ASS Studio hoàn chỉnh chứa các script kiểm toán tự động (`ass_tools.py lint-tags`, `timing-qc`, `motion_studio.py`, v.v.).
- **Thư viện nguồn phụ đề**:
  - `1_Nguon_Typeset_TS/`: 7 bản phụ đề đại diện cho các trường phái Typeset 3D, FBF, vector mask.
  - `2_Ban_Dich_Viet/`: 4 bản dịch tiếng Việt tham chiếu.
  - `3_Sub_Nhat_Goc/`: Kịch bản Blu-ray và Closed Captions tiếng Nhật chính thức.
- **Hướng dẫn tài nguyên**: [`README_WIP.md`](./README_WIP.md).

---

## 🚀 Kế Hoạch Tiếp Theo (Phase 2)
Biên tập bản dịch tiếng Việt chuẩn xác ngữ nghĩa, kế thừa lời thoại mượt mà từ Subscene-2272610, đối soát kịch bản Nhật, áp dụng ma trận xưng hô chuẩn cho từng diễn viên.
