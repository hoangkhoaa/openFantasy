# Các Lớp Nhân Vật OpenFantasy

> *"Mỗi linh hồn tìm thấy giai điệu riêng của mình trong bản giao hưởng của sức mạnh."*

## Tổng quan

Chào mừng đến với tài liệu về Các Lớp Nhân Vật OpenFantasy. Kho lưu trữ này chứa thông tin toàn diện về các con đường sức mạnh và chuyên môn hóa khác nhau dành cho nhân vật trong thế giới OpenFantasy.

## Điều Hướng Nhanh

- [Các Nguyên Tắc Cơ Bản về Lớp](#cac-nguyen-tac-co-ban-ve-lop)
- [Các Lớp Chính](#cac-lop-chinh)
- [Tiến Trình Nhân Vật](#tien-trinh-nhan-vat)
- [Đa Lớp](#da-lop)
- [Sự Gần Gũi của Chủng Tộc](#su-gan-gui-cua-chung-toc)
- [Cấu Trúc Tài Liệu](#cau-truc-tai-lieu)

## Các Nguyên Tắc Cơ Bản về Lớp

Các lớp (Classes) trong OpenFantasy đại diện cho các con đường chuyên biệt khai thác và phát triển khả năng bẩm sinh của nhân vật:

| Khái Niệm (Concept) | Mô Tả (Description) |
|---------|-------------|
| **Cấu Trúc Lớp (Class Structure)** | Tổ chức các khả năng và chuyên môn hóa |
| **Thành Phần Nguyên Tố (Elemental Composition)** | Sự cân bằng của Exanthis, Soul (Linh hồn) và Mana Capacity (Dung lượng Mana) |
| **Phân Lớp (Subclasses)** | Các nhánh chuyên biệt của mỗi lớp cốt lõi |
| **Tiến Trình Lớp (Class Progression)** | Con đường phát triển cho các khả năng của lớp |
| **Trang Bị (Equipment)** | Công cụ và vật phẩm giúp tăng cường khả năng của lớp |

## Các Lớp Chính

OpenFantasy có mười lớp chính (primary classes), mỗi lớp có chuyên môn hóa riêng:

| Lớp (Class) | Tập Trung Cốt Lõi (Core Focus) | Thuộc Tính Chính (Primary Attribute) | Thư Mục Lớp (Class Directory) |
|-------|------------|-------------------|----------------|
| **Warrior (Chiến binh)** | Chiến đấu vật lý | Exanthis | [Warrior/](Warrior/) |
| **Mage (Pháp sư)** | Triệu hồi phép thuật | Mana Capacity (Dung lượng Mana) | [Mage/](Mage/) |
| **Rogue (Đạo tặc)** | Lén lút và chính xác | Soul (Linh hồn) | [Rogue/](Rogue/) |
| **Cleric (Giáo sĩ)** | Ma thuật thần thánh | Soul (Linh hồn)/Mana | [Cleric/](Cleric/) |
| **Ranger (Cung thủ)** | Hoang dã và theo dõi | Exanthis/Soul (Linh hồn) | [Ranger/](Ranger/) |
| **Artificer (Thợ rèn)** | Sáng tạo ma thuật | Mana Capacity (Dung lượng Mana) | [Artificer/](Artificer/) |
| **Bard (Nhà thơ)** | Ma thuật biểu diễn | Soul (Linh hồn)/Mana | [Bard/](Bard/) |
| **Druid (Thầy tu)** | Ma thuật tự nhiên | Soul (Linh hồn)/Mana | [Druid/](Druid/) |
| **Monk (Tu sĩ)** | Năng lượng bên trong | Exanthis/Soul (Linh hồn) | [Monk/](Monk/) |
| **Warlock (Phù thủy)** | Ma thuật khế ước | Soul (Linh hồn)/Mana | [Warlock/](Warlock/) |

→ Xem [Tổng quan về các lớp](Classes.md) để biết thông tin chi tiết về từng lớp.

## Tiến Trình Nhân Vật

Sự tiến bộ của nhân vật tuân theo một hệ thống tiến trình theo cấp bậc:

### Bậc Cấp Độ

| Bậc (Tier) | Cấp Độ (Levels) | Mô Tả (Description) |
|------|--------|-------------|
| **Người Mới (Novice)** | 1-5 | Học các nguyên tắc cơ bản của lớp |
| **Người Lành Nghề (Adept)** | 6-10 | Nắm vững kiến thức cơ bản và phát triển chuyên môn |
| **Chuyên Gia (Expert)** | 11-15 | Trau dồi khả năng đến mức cao |
| **Bậc Thầy (Master)** | 16-20 | Đạt được sự làm chủ con đường đã chọn |
| **Huyền Thoại (Legendary)** | 21+ | Vượt qua những giới hạn bình thường |

## Đa Lớp

Nhân vật có thể theo đuổi nhiều con đường lớp cùng một lúc, tạo ra sự kết hợp độc đáo của các khả năng. Sự linh hoạt này phải trả giá bằng sự tinh thông chuyên môn trong bất kỳ kỷ luật đơn lẻ nào.

### Các Tổ Hợp Đa Lớp Phổ Biến

| Tổ Hợp (Combination) | Hiệp Lực (Synergy) |
|-------------|---------|
| Warrior (Chiến binh)/Mage (Pháp sư) | Chiến đấu vật lý được tăng cường bằng khả năng phép thuật |
| Cleric (Giáo sĩ)/Warrior (Chiến binh) | Ma thuật thần thánh với sức mạnh chiến đấu |
| Rogue (Đạo tặc)/Ranger (Cung thủ) | Lén lút kết hợp với chuyên môn hoang dã |
| Bard (Nhà thơ)/Warlock (Phù thủy) | Ma thuật biểu diễn được tăng cường bằng khả năng khế ước |
| Druid (Thầy tu)/Monk (Tu sĩ) | Ma thuật tự nhiên kết hợp với kỷ luật thể chất |

## Sự Gần Gũi của Chủng Tộc

Các chủng tộc khác nhau có sự gần gũi tự nhiên với các lớp nhất định dựa trên thành phần nguyên tố của chúng:

| Chủng Tộc (Species) | Sự Gần Gũi Tự Nhiên với Các Lớp (Natural Class Affinities) |
|---------|--------------------------|
| **Humans (Con người)** | Sự gần gũi cân bằng với tất cả các lớp |
| **Elves (Tiên tộc)** | Mage (Pháp sư), Ranger (Cung thủ), Bard (Nhà thơ) |
| **Dark Elves (Hắc Tiên)** | Mage (Pháp sư), Rogue (Đạo tặc), Warlock (Phù thủy) |
| **Dwarves (Người lùn)** | Warrior (Chiến binh), Artificer (Thợ rèn), Cleric (Giáo sĩ) |
| **Beastfolk (Người thú)** | Ranger (Cung thủ), Druid (Thầy tu), Warrior (Chiến binh) |
| **Dragonkin (Hậu duệ rồng)** | Warrior (Chiến binh), Mage (Pháp sư), Warlock (Phù thủy) |
| **Fae (Thần tiên)** | Bard (Nhà thơ), Druid (Thầy tu), Mage (Pháp sư) |
| **Golems (Người máy)** | Artificer (Thợ rèn), Warrior (Chiến binh) |
| **Sirens (Nàng tiên cá)** | Bard (Nhà thơ), Mage (Pháp sư) |
| **Shadowfolk (Người bóng tối)** | Rogue (Đạo tặc), Warlock (Phù thủy), Mage (Pháp sư) |
| **Giants (Người khổng lồ)** | Warrior (Chiến binh), Druid (Thầy tu) |

## Thành Phần Nguyên Tố

Mỗi lớp có một thành phần nguyên tố đặc trưng định hình khả năng của họ:

| Lớp (Class) | Exanthis | Soul (Linh hồn) | Mana Capacity (Dung lượng Mana) | Sự Gần Gũi Ma Thuật Chính (Primary Magical Affinity) |
|-------|----------|------|---------------|--------------------------|
| **Warrior (Chiến binh)** | 50-70% | 20-35% | 10-20% | Terramana (Sự ổn định), Base Mana (Sức mạnh) |
| **Mage (Pháp sư)** | 10-25% | 15-35% | 50-70% | Thay đổi theo chuyên môn hóa |
| **Rogue (Đạo tặc)** | 30-45% | 40-60% | 10-25% | Umbramana (Sự che giấu), Aeromana (Tính di động) |
| **Cleric (Giáo sĩ)** | 20-35% | 30-50% | 25-45% | Luxmana (Ánh sáng), Vitamana (Chữa lành) |
| **Ranger (Cung thủ)** | 35-55% | 30-45% | 15-30% | Vitamana (Thiên nhiên), Aeromana (Di chuyển) |
| **Artificer (Thợ rèn)** | 25-40% | 20-35% | 35-55% | Crystallmana (Cấu trúc), Terramana (Độ vững chắc) |
| **Bard (Nhà thơ)** | 15-30% | 35-55% | 25-45% | Fulgumana (Âm thanh), Aeromana (Giao tiếp) |
| **Druid (Thầy tu)** | 20-35% | 30-45% | 30-50% | Vitamana (Sự tăng trưởng), Terramana (Đất) |
| **Monk (Tu sĩ)** | 40-55% | 30-50% | 10-25% | Base Mana (Năng lượng bên trong), Aeromana (Di chuyển) |
| **Warlock (Phù thủy)** | 15-30% | 25-40% | 40-60% | Aetheramana (Hư không), Thay đổi theo khế ước |

Sự cân bằng nguyên tố này ảnh hưởng trực tiếp đến sự gần gũi tự nhiên của một lớp đối với các hình thức ma thuật chuyên biệt nhất định và khả năng ma thuật tổng thể của họ:

- **Hiệu Quả Chuyên Môn Hóa (Specialization Efficiency)**: Các lớp có Mana Capacity (Dung lượng Mana) cao hơn thường đạt được tỷ lệ chuyên môn hóa nguyên tố tốt hơn
- **Thanh Lọc Mana (Mana Purification)**: Tỷ lệ Soul (Linh hồn) trên Mana Capacity (Dung lượng Mana) ảnh hưởng đến khả năng của một lớp trong việc thanh lọc Wild Mana thành Base Mana
- **Thể Lực Ma Thuật (Magical Stamina)**: Exanthis cao hơn cung cấp sức bền thể chất tốt hơn nhưng thường làm giảm hiệu quả ma thuật
- **Tiềm Năng Lai (Hybrid Potential)**: Các lớp có thành phần cân bằng hơn thường vượt trội trong việc kết hợp các loại nguyên tố khác nhau

## Cấu Trúc Tài Liệu

Thư mục Classes được tổ chức như sau:

```
codex/Classes/
├── README.md                # Tài liệu tổng quan này
├── Classes.md               # Tài liệu về các lớp chính với mô tả chi tiết
├── template_README.md       # Mẫu để tạo tệp README thư mục lớp
├── Warrior/                 # Ví dụ thư mục lớp
│   ├── README.md            # Tổng quan dành riêng cho lớp
│   ├── Warrior.md           # Thông tin chi tiết về lớp
│   ├── Guardian.md          # Tài liệu về phân lớp
│   ├── Berserker.md         # Tài liệu về phân lớp
│   └── ...                  # Các tài liệu phân lớp khác
└── ...                      # Các thư mục lớp khác
```

### Sử Dụng Mẫu

Để tạo một README lớp mới, hãy sao chép tệp [template_README.md](template_README.md) và thay thế các giá trị giữ chỗ bằng thông tin dành riêng cho lớp:

1. Thay thế `[CLASS_NAME]` bằng tên của lớp
2. Điền vào phạm vi và mô tả thành phần
3. Liệt kê các phân lớp với các lĩnh vực và chuyên môn tập trung của chúng
4. Tài liệu về khả năng cốt lõi, trang bị và sự gần gũi của loài
5. Mô tả điểm mạnh và thách thức của lớp

---

> **Cấu Trúc Kho Lưu Trữ**: Tài liệu này sử dụng định dạng Markdown được tối ưu hóa để xem trên các nền tảng Git. 


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._