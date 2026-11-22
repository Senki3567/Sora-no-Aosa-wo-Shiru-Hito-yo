# Hướng Dẫn & Danh Mục Tài Nguyên: Sora no Aosa wo Shiru Hito yo (Her Blue Sky)
Thư mục: `/media/cuongba956/Download/WIP - D/Sora no Aosa wo Shiru Hito yo`

---

## 1. Thư mục `1_Nguon_Typeset_TS/` (Các nguồn Typeset đáng tận dụng)
Tập hợp các file subtitle đại diện cho các trường phái Typesetting đỉnh cao trên thế giới:

1. **`01_Arid_ENG_3D_Perspective_Org_Anarchy_FBF.ass`**:
   - **Đặc trưng**: Bản TS tiếng Anh hoàn hảo nhất. Chứa 1,496 dòng TS, 635 thẻ 3D quang học `\org`, tích hợp sign FBF của Anarchy (`Stem-Medium`).
   - **Tận dụng**: Làm **bộ khung chuẩn (Baseline Frame)** để căn phụ đề tiếng Việt và thừa hưởng toàn bộ sign tracking không gian 3D.
2. **`02_Trix_FRE_Vector_Screen_Masking_5600Shapes.ass`**:
   - **Đặc trưng**: Bản tiếng Pháp với 5,661 thẻ vẽ vector `\p1`/`\p2` và 5,516 thẻ `\clip`.
   - **Tận dụng**: Lấy các layer **mask che phủ chữ gốc** (đặc biệt là tin nhắn điện thoại và bảng thông báo hội trường) nếu không muốn để lộ chữ tiếng Nhật phía dưới.
3. **`03_Beatrice-Raws_POL_Dense_FBF_18kEvents_KaraEffector.ass`**:
   - **Đặc trưng**: Bản Ba Lan với 20,264 events (18,421 dòng TS FBF từng frame 0.04s).
   - **Tận dụng**: Tham khảo kỹ thuật Kara Effector 3.5 hạt vỡ tam giác bay ở đoạn Ending.
4. **`04_Asahi_ARA_RTL_UI_Reconstruction_2000Shapes.ass`**:
   - **Đặc trưng**: Bản Ả Rập với hơn 2,000 vector Bézier tái tạo UI điện thoại theo hướng Right-to-Left.
5. **`05_Nekomoe_kissaten_CHS_JPN_Vertical_Typography.ass`**:
   - **Đặc trưng**: Bản song ngữ Trung-Nhật dùng style font dọc (`@` fonts) quay 270°.
6. **`06_DEC_TUR_Turkish_3D_Perspective.ass`**:
   - **Đặc trưng**: Bản Thổ Nhĩ Kỳ ứng dụng thẻ 3D `\org`.
7. **`07_Kaizoku_ENG_Base_SafranStyle.ass`**:
   - **Đặc trưng**: Bản base font Safran của Kaizoku (lưu ý: lệch time +42s so với Japanese BD).

---

## 2. Thư mục `2_Ban_Dich_Viet/` (Các bản dịch tiếng Việt)
Toàn bộ các bản Vietsub độc lập hiện có:

1. **`01_Olshiro-Fansub_[Vietsub]_CoSignTS_LoiCaHoi.ass`**:
   - Bản Vietsub duy nhất có Typeset sign (~40 sign), nhưng làm sơ sài, dùng ký tự lặp `gggg` làm khung, dính lỗi dịch "tuna -> cá hồi", sót ghi chú `{...}` tiếng Anh.
2. **`02_Subscene-2272610_DichChuan_FullSongLyrics_KanjiRomajiVI.ass`**:
   - **Bản dịch tốt nhất**: Lời thoại mượt mà, chính xác (*tảo bẹ*, *cá ngừ*).
   - **Đặc biệt**: Có đầy đủ lời bài hát insert song và ED theo format 3 dòng: **Kanji + Romaji + Lời dịch tiếng Việt**.
3. **`03_Subscene-2236639_ThoaiTho_KhongTS.ass`**:
   - Bản sub thô 1,418 dòng, font Geogrotesque Light cỡ 23, không có sign hay bài hát.
4. **`04_AnimeSubtitles_VCB-Studio_OlshiroSync.vi.ass`**:
   - Bản Olshiro được sync lại tên cho release của VCB-Studio trong kho AnimeSubtitles.

---

## 3. Thư mục `3_Sub_Nhat_Goc/` (Phụ đề tiếng Nhật chuẩn)
Dùng để đối chiếu ngữ nghĩa gốc và timing chuẩn theo giọng thoại diễn viên:

1. **`01_Official_Netflix_Japanese_ClosedCaptions.ja[cc].srt`**:
   - Phụ đề tiếng Nhật chính thức Closed Captions từ Netflix (có đầy đủ chú thích âm thanh, tiếng thở, tên nhân vật nói).
2. **`02_BD_Dialogue_Official_Japanese.ja.srt`**:
   - Phụ đề tiếng Nhật chuẩn thoại từ đĩa Blu-ray (nguồn DB / Kitsunekko).
3. **`03_Nekomoe_kissaten_Bilingual_Raw_Japanese_Text.JPSC.ass`**:
   - Chứa dòng tiếng Nhật gốc nguyên bản chạy song song cùng tiếng Trung trong từng cue thoại.

---

## 4. Thư mục `Fonts/` (Toàn bộ Font phục vụ Typeset và Vietsub)
Đã gom và kiểm định đủ 100% font cho phụ đề Typeset và phụ đề Việt:

1. **`Fonts_Typeset_TS/`** (6 thư mục font theo nhóm TS):
   - `Arid_Anarchy_ENG/`: Trọn bộ 35 font (`Safran-Bold`, `Safran-BoldItalic`, `Stem-Medium`, `Stem-Regular`, `Dom Casual`, `GaramondPremier-Bold` [CrapGPPB], `Set Fire to the Rain`, `KG HAPPY`, `KG Second Chances Solid`, `Inkfree`, `Boopee`, `BuiltTitling`, `HapolePencil`,...).
   - `Trix_FRE/`: 25 font phục vụ vector mask và typography Pháp (`Lato Black`, `Junicode`, `Set Fire to the Rain`,...).
   - `Beatrice_Raws_POL/`: 32 font phục vụ FBF và Kara Effector Ba Lan (`Althea`, `Gandhi Sans`, `Lora Bold`, `Handwritten Crystal`,...).
   - `Asahi_ARA/`: 24 font phục vụ bản Ả Rập.
   - `DEC_TUR/`: 27 font phục vụ bản Thổ Nhĩ Kỳ.
   - `Kaizoku_ENG/`: 27 font gốc của Kaizoku.
2. **`Fonts_Sub_Viet/`** (Font phục vụ phụ đề Việt):
   - `Olshiro_UVN_UTM/`: Đầy đủ toàn bộ các font UVN và UTM mà Olshiro sử dụng (`UVN Ai Cap Nang`, `UVN Bay Buom`, `UVN Bay Buom Hep`, `UVN Bay Buom Nang`, `UVN Mang Cau`, `UVN Van`, `UVN Banh Mi`, `UTM Americana`, `UTM Flavour`, `UTM Sarah`, `YuMincho-SemiBold`).
   - `Subscene_Geogrotesque/`: Font `Geogrotesque Light` cho bản Subscene 2236639.
   - `Local_VN_Fonts_ArialRounded_UVN/`: Bộ backup 518 font tiếng Việt và `Arial-Rounded MT` phục vụ bản Subscene 2272610.

---

## Khuyến Nghị Quy Trình Hoàn Thiện Vietsub Chuẩn Xưởng:
- **Bước 1**: Lấy file `1_Nguon_Typeset_TS/01_Arid_ENG_3D_Perspective_Org_Anarchy_FBF.ass` làm khung gốc (giữ nguyên toàn bộ Style, Signs 3D, Anarchy FBF, Gandhara, ED).
- **Bước 2**: Lấy lời thoại và bài hát từ `2_Ban_Dich_Viet/02_Subscene-2272610_...ass` căn (`softsub-align`) vào các cue thoại tiếng Anh của Arid.
- **Bước 3**: Đối chiếu các đoạn xưng hô mơ hồ với `3_Sub_Nhat_Goc/02_BD_Dialogue_Official_Japanese.ja.srt`.
- **Bước 4 (Tùy chọn nâng cao)**: Nếu muốn xóa hoàn toàn chữ Nhật gốc trên màn hình điện thoại mà không để lộ nền, copy các layer vector mask từ `1_Nguon_Typeset_TS/02_Trix_FRE_Vector_Screen_Masking_5600Shapes.ass` đặt vào layer dưới của sign Arid.
