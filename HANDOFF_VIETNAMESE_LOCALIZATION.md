# Tài Liệu Bàn Giao: Biên Tập Bản Dịch Tiếng Việt Phụ Đề "Her Blue Sky"
*(Sora no Aosa wo Shiru Hito yo - 2019)*

---

## 1. Tổng Quan & Trạng Thái Dự Án Hiện Tại

- **File Master Baseline**: `Her.Blue.Sky.2019.1080p.BluRay.Dual-Audio.Opus.5.1.x265-YURASUKA.ass`
- **Cấu trúc sự kiện (3,045 sự kiện `Dialogue`)**:
  - `[THOẠI]`: 1,471 dòng — **Đã thẩm định 100% trường `Actor`**, khớp danh tính người nói theo Netflix CC, kịch bản Blu-ray và Ending Credits.
  - `[SIGN]`: 1,459 dòng — Giữ nguyên bộ khung Typeset 3D quang học `\org`, tracking và FBF đỉnh cao từ bản Arid.
  - `[SONG]`: 115 dòng — Gồm bài hát mở đầu Gandhara và bài hát kết phim Sora no Aosa wo Shiru Hito yo.
- **File Alignment Đối Soát**: `thoai_full_alignment.tsv` (khớp 1:1 từng cue EN với Actor, tiếng Nhật BD và Closed Captions Netflix).

---

## 2. Danh Mục Tài Nguyên & Vai Trò

| Thư mục / File | Mô tả | Vai trò trong Phase 2 |
|:---|:---|:---|
| `Her.Blue.Sky...YURASUKA.ass` | File master đã audit Actor | **File làm việc chính**, dịch đè text tiếng Việt vào trường Text của `[THOẠI]`. |
| `thoai_full_alignment.tsv` | Bảng tra cứu 1,471 cue thoại | Cung cấp ngữ cảnh đối chiếu EN vs JP vs Actor cho từng câu. |
| `2_Ban_Dich_Viet/02_Subscene-2272610...ass` | Bản dịch Việt tốt nhất | **Nguồn tham khảo văn phong chính**: Lời dịch trau chuốt, chính xác, có đầy đủ 3 dòng Kanji/Romaji/Việt cho bài hát. |
| `2_Ban_Dich_Viet/01_Olshiro-Fansub...ass` | Bản Vietsub của Olshiro | Tham khảo thêm cách dùng từ; cần lọc bỏ các lỗi dịch máy móc. |
| `3_Sub_Nhat_Goc/02_BD_Dialogue...ja.srt` | Kịch bản BD tiếng Nhật | **Thẩm quyền tối cao về ngữ nghĩa** khi EN và VI có sự sai lệch hoặc mơ hồ. |
| `3_Sub_Nhat_Goc/01_Official_Netflix...ja[cc].srt` | Phụ đề Closed Captions Nhật | Xác thực sắc thái cảm xúc, âm thanh nền và đối soát người nói. |

---

## 3. Ma Trận Xưng Hô Chi Tiết Theo Cặp Nhân Vật

Việc xác định `Actor` chính xác giúp thiết lập hệ thống xưng hô tự nhiên, giữ trọn vẹn văn phong anime và tình cảm nhân vật:

```
+-----------------------------------------------------------------------------------+
|                              MA TRẬN XƯNG HÔ TOÀN PHIM                            |
+-------------------+-------------------+--------------------+----------------------+
| Cặp nhân vật      | Nhân vật A gọi B  | Nhân vật B gọi A   | Sắc thái & Ghi chú   |
+-------------------+-------------------+--------------------+----------------------+
| Aoi <-> Akane     | Em - Chị          | Chị - Em           | Aoi gọi "chị Akane"  |
|                   | (Chị Akane)       | (Ao / Aoi)         | (あか姉 - Akane)     |
+-------------------+-------------------+--------------------+----------------------+
| Shinno <-> Aoi    | Tao - Mày / Anh-Em| Nhóc - Tôi / Anh-Em| Shinno gọi "nhóc Ao" |
|                   | (Nhóc Ao / Ao)    | (Shinno)           | Xưng hô suồng sã     |
+-------------------+-------------------+--------------------+----------------------+
| Shinno <-> Akane  | Tôi - Em / Anh-Em | Em - Anh           | Tình đầu 13 năm trước|
|                   | (Akane)           | (Shinno)           | Ngượng ngùng, sâu sắc|
+-------------------+-------------------+--------------------+----------------------+
| Shinnosuke <-> Aoi| Tôi - Nhóc / Anh-Em| Ông chú / Anh - Tôi| Ban đầu đối nghịch,  |
|                   | (Nhóc con / Ao)   | (Shinnosuke-san)   | sau thấu hiểu nhau   |
+-------------------+-------------------+--------------------+----------------------+
| Shinnosuke <->    | Tôi - Em / Anh-Em | Em - Anh           | Tái ngộ tuổi 31,     |
| Akane             | (Akane)           | (Shinnosuke-kun)   | vừa quen vừa xa lạ   |
+-------------------+-------------------+--------------------+----------------------+
| Masamichi <->     | Tôi - Bà / Tớ-Cậu | Bà - Tôi / Cậu-Tớ  | Bạn học cùng lớp,    |
| Akane             | (Akane)           | (Michinko)         | Masamichi thầm thích |
+-------------------+-------------------+--------------------+----------------------+
| Tsugu <->         | Con - Bố          | Bố - Con           | Tsugu gọi "bố"       |
| Masamichi         | (Bố / Michinko)   | (Tsugu)            | hoặc "bố Michinko"   |
+-------------------+-------------------+--------------------+----------------------+
| Tsugu <-> Aoi     | Em - Chị          | Chị - Em           | Tsugu gọi "chị Ao",  |
|                   | (Chị Ao)          | (Tsugu)            | rất thân với Aoi     |
+-------------------+-------------------+--------------------+----------------------+
| Chika <-> Aoi     | Mày - Tao / Cậu-Tớ| Mày - Tao / Cậu-Tớ | Bạn thân cùng lớp    |
|                   | (Ao)              | (Chika)            | Năng động, thoải mái |
+-------------------+-------------------+--------------------+----------------------+
| Nitobe Dankichi   | Ta / Tôi          | Thầy / Bác Nitobe  | Ca sĩ Enka tiền bối, |
|                   | (Các cậu / Chú em)| (Nitobe-sensei)    | hào sảng, trịch thượng|
+-------------------+-------------------+--------------------+----------------------+
| Abo <-> Bạn bè    | Tao - Mày         | Mày - Tao          | Bạn ban nhạc cấp 3,  |
|                   | (Shinno / Michinko| (Abo)              | bình dân, vui vẻ     |
+-------------------+-------------------+--------------------+----------------------+
```

---

## 4. Các Lỗi Dịch Cần Khắc Phục Triệt Để

1. **Cơm nắm nhân cá ngừ mayonnaise (`ツナマヨ`) vs Tảo bẹ (`昆布` Kombu)**:
   - *Bối cảnh*: Xuyên suốt phim, Shinno luôn đòi ăn cơm nắm nhân "cá ngừ mayonnaise" (tuna mayo), nhưng Akane luôn làm nhân "tảo bẹ" (kombu) vì Aoi thích ăn tảo bẹ.
   - *Lỗi cũ của Olshiro*: Dịch nhầm `tuna` thành "cá hồi", làm mất ý nghĩa đối lập và chi tiết cao trào ở cuối phim khi Akane nói sẽ thử làm cơm nắm cá ngừ mayo.
   - *Yêu cầu*: Thống nhất dịch chuẩn là **cá ngừ sốt mayo** (hoặc cá ngừ mayo) vs **tảo bẹ**.

2. **Thành ngữ tựa phim (`井の中の蛙大海を知らず、されど空の青さを知る`)**:
   - Câu gốc: *"Ếch ngồi đáy giếng tuy chẳng hay biển rộng, nhưng thấu rõ trời xanh."*
   - *Lỗi cũ*: Dịch thành "coi trời bằng vung".
   - *Yêu cầu*: Dịch chuẩn ý nghĩa thơ ca và triết lý: Dù không bước ra thế giới bao la bên ngoài, người ở lại vẫn có thể thấu hiểu vẻ đẹp và giá trị sâu sắc nơi mình gắn bó.

3. **Biệt danh của Aoi (`目玉スター` - Medama Star)**:
   - Shinno thời trẻ đặt cho Aoi bé vì mắt cô bé to tròn xoe.
   - *Yêu cầu*: Dịch là **"Ngôi sao Mắt Tròn"** hoặc **"Mắt Biếc Ngôi Sao"** (tránh dịch thô "ngôi sao mắt lồi").

4. **Cây đàn của Shinnosuke (`あかねスペシャル` - Akane Special)**:
   - Cây guitar bass/lead được Shinno đặt theo tên Akane.
   - *Yêu cầu*: Giữ nguyên cụm từ **"Akane Special"**.

---

## 5. Quy Trình Kỹ Thuật Khi Thực Hiện Phase 2

1. **Giữ nguyên bộ khung (Cue Invariance)**:
   - Giữ nguyên 100% timecode Start/End của file master baseline.
   - Giữ nguyên cấu trúc phân vùng `[THOẠI]`, `[SIGN]`, `[SONG]`.
2. **Ngắt dòng phù hợp chiều rộng libass (`\N`)**:
   - Không để dòng phụ đề dài quá 40 ký tự tiếng Việt trên một hàng.
   - Dùng `\N` ngắt dòng tự nhiên theo cụm ngữ pháp, tránh để mồ côi một từ ở dòng dưới.
3. **Kiểm toán chất lượng (Quality Control)**:
   - Chạy `ass_tools.py lint-tags` kiểm tra cú pháp tag.
   - Chạy `ass_tools.py timing-qc` để giám sát CPS (Characters Per Second).
   - Kiểm tra font hiển thị tiếng Việt đảm bảo không lỗi glyph/ô vuông.
