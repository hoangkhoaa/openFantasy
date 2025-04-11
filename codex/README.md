# OpenFantasy World Codex

> *"Một thế giới của phép thuật và kỳ diệu đang chờ đợi, nơi mỗi linh hồn đóng góp vào bản giao hưởng vĩ đại của sự tồn tại."*

## Tổng quan

Chào mừng đến với OpenFantasy World Codex, một kho lưu trữ kiến thức toàn diện về vũ trụ OpenFantasy. Codex này chứa thông tin chi tiết về các nguyên tắc cơ bản, cư dân, hệ thống ma thuật, địa điểm, vật phẩm và nhiều thứ khác của thế giới.

## Điều hướng nhanh

- [Nguyên tắc cơ bản của thế giới](#world-fundamentals)
- [Sinh vật và loài](#creatures-and-species)
- [Hệ thống ma thuật](#magic-system)
- [Lớp nhân vật](#character-classes)
- [Địa lý thế giới](#world-geography)
- [Vật phẩm và cổ vật](#items-and-artifacts)
- [Cấu trúc kho lưu trữ](#repository-structure)

## Nguyên tắc cơ bản của thế giới

OpenFantasy được xây dựng dựa trên các nguyên tắc cốt lõi chi phối cách thế giới hoạt động:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [Basic/](Basic/) | Các khái niệm cơ bản | Các khối xây dựng của thực tế trong OpenFantasy |

Các khái niệm chính bao gồm:

- **Exanthis**: Nền tảng vật lý cung cấp cấu trúc và hình thức
- **Soul**: Tia lửa ý thức cung cấp ý chí và bản sắc
- **Mana**: Năng lượng ma thuật chảy qua mọi thứ
- **Elemental Balance**: Sự tương tác giữa các lực cơ bản

## Sinh vật và loài

Thế giới có nhiều loài sinh sống với các đặc điểm độc đáo:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [Creatures/](Creatures/) | Tài liệu về loài | Thông tin về các sinh vật khác nhau sinh sống trên thế giới |

Các loại loài chính bao gồm:

- **Primary Species**: Humans, Elves, Dwarves, Beastfolk, etc.
- **Magical Species**: Fae, Golems, Sirens, Shadowfolk, etc.
- **Other Notable Species**: Dark Elves, Centaurs, Gnomes, Merfolk, etc.

→ Xem [Creatures README](Creatures/README.md) để biết thông tin chi tiết.

## Hệ thống ma thuật

Ma thuật trong OpenFantasy tuân theo các quy tắc và nguyên tắc có hệ thống:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [Magics/](Magics/) | Hệ thống ma thuật, phép thuật | Các quy tắc và biểu hiện của năng lượng ma thuật |

Các khái niệm ma thuật chính bao gồm:

- **Elemental Magic**: Thao túng tám nguyên tố chính
- **Mana Purity**: Sự tinh chế năng lượng ma thuật
- **Spell Structure**: Các mẫu định hình các hiệu ứng ma thuật
- **Enhancement Buffs**: Các hiệu ứng ma thuật giúp tăng cường khả năng

→ Xem [Magics README](Magics/README.md) để biết thông tin chi tiết.

## Lớp nhân vật

Các nhân vật trong OpenFantasy đi theo những con đường phát triển chuyên biệt:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [Classes/](Classes/) | Thông tin lớp, chuyên môn hóa | Các con đường khác nhau của sức mạnh và chuyên môn hóa |

Các loại lớp chính bao gồm:

- **Martial Classes**: Warrior, Monk, Ranger
- **Magical Classes**: Mage, Warlock, Druid
- **Hybrid Classes**: Cleric, Bard, Artificer
- **Specialized Classes**: Rogue and subclasses

→ Xem [Classes README](Classes/README.md) để biết thông tin chi tiết.

## Địa lý thế giới

Thế giới của OpenFantasy chứa nhiều khu vực và địa điểm đa dạng:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [World/](World/) | Địa điểm, địa lý, lịch sử | Cảnh quan vật chất và văn hóa của thế giới |

Các khu vực đáng chú ý bao gồm:

- **Eastern Veldrassil**: Các khu rừng ma thuật và trung tâm học thuật
- **Western Veldrassil**: Dãy núi và hoạt động khai thác mỏ
- **Central Plains**: Vùng đất nông nghiệp và các thành phố lớn
- **Northern Reaches**: Vùng đất hoang tàn đóng băng và tàn tích cổ
- **Southern Isles**: Quần đảo nhiệt đới và văn hóa hàng hải

## Vật phẩm và cổ vật

Thế giới chứa vô số vật thể có sức mạnh và ý nghĩa:

| Thư mục | Nội dung | Mô tả |
|-----------|----------|-------------|
| [Items/](Items/) | Thiết bị, cổ vật, vật liệu | Các vật thể có sức mạnh và tiện ích |

Các loại vật phẩm bao gồm:

- **Magical Equipment**: Vũ khí, áo giáp và phụ kiện có đặc tính ma thuật
- **Alchemical Substances**: Thuốc, thuốc tiên và thuốc thử ma thuật
- **Artifacts**: Các vật thể cổ xưa có sức mạnh đáng kể
- **Everyday Items**: Vật thể trần tục có ý nghĩa văn hóa

## Cấu trúc kho lưu trữ

OpenFantasy Codex được tổ chức với một cấu trúc nhất quán:

```
codex/
├── README.md                # Tài liệu tổng quan này
├── Basic/                   # Các khái niệm cơ bản
├── Creatures/               # Tài liệu về loài
│   ├── README.md            # Tổng quan về sinh vật
│   ├── Creatures.md         # Thông tin chung về loài
│   ├── Human.md             # Tài liệu về từng loài
│   └── ...                  # Tài liệu về các loài khác
├── Magics/                  # Hệ thống ma thuật
│   ├── README.md            # Tổng quan về ma thuật
│   ├── Spells/              # Tài liệu về phép thuật
│   └── ...                  # Tài liệu về hệ thống ma thuật
├── Classes/                 # Lớp nhân vật
│   ├── README.md            # Tổng quan về lớp
│   ├── Warrior/             # Thư mục dành riêng cho lớp
│   └── ...                  # Các thư mục lớp khác
├── World/                   # Địa lý và địa điểm
│   ├── README.md            # Tổng quan về thế giới
│   └── ...                  # Tài liệu về khu vực và địa điểm
└── Items/                   # Thiết bị và cổ vật
    ├── README.md            # Tổng quan về vật phẩm
    └── ...                  # Tài liệu về danh mục vật phẩm
```

### Tiêu chuẩn tài liệu

Tất cả các tài liệu trong kho lưu trữ này tuân theo định dạng nhất quán:

- **README.md files** cung cấp tổng quan và điều hướng
- **Quick Reference sections** ở đầu tài liệu
- **Tables** cho thông tin so sánh
- **Consistent headers** cho thông tin tương tự trên các tài liệu
- **Cross-references** đến nội dung liên quan
- **Git-optimized markdown** để có trải nghiệm xem tốt hơn

---

> **Lưu ý**: Codex này là một tài liệu sống có thể được mở rộng và tinh chỉnh theo thời gian. Tất cả nội dung tuân theo phép ẩn dụ âm nhạc định nghĩa thế giới OpenFantasy.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._