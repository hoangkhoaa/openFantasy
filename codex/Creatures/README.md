# OpenFantasy Creatures Codex

> *"Thế giới ngân vang với tiếng nói của vô số sinh vật, mỗi sinh vật đều đóng vai trò của mình trong bản giao hưởng vĩ đại của sự tồn tại."*

## Tổng quan

Chào mừng bạn đến với tài liệu OpenFantasy Creatures. Kho lưu trữ này chứa thông tin toàn diện về các sinh vật khác nhau sinh sống trong thế giới OpenFantasy, bao gồm các loài có tri giác, động vật, quái vật, thực vật và các thực thể khác.

## Cấu trúc thư mục

```
/Creatures
├── README.md                # Tài liệu tổng quan này
├── Creatures.md             # Các nguyên tắc cốt lõi và thành phần nguyên tố
├── template_species.md      # Mẫu để tạo các mục loài mới
├── /Sentient                # Loài thông minh, hình thành nền văn minh
│   ├── README.md            # Tổng quan về các loài có tri giác
│   ├── Humans.md
│   ├── Elves.md
│   ├── DarkElves.md
│   ├── Dwarves.md
│   └── ...
├── /Magical                 # Chủ yếu là các sinh vật phép thuật hoặc fae
│   ├── README.md            # Tổng quan về các sinh vật phép thuật
│   ├── Fae.md
│   ├── Golems.md
│   ├── Elementals.md
│   └── ...
├── /Animals                 # Động vật tự nhiên không có tri giác
│   ├── README.md            # Tổng quan về động vật
│   ├── Domesticated.md
│   ├── Wild.md
│   ├── Aquatic.md
│   └── ...
├── /Monsters                # Sinh vật nguy hiểm hoặc bất thường
│   ├── README.md            # Tổng quan về quái vật
│   ├── Aberrations.md
│   ├── Undead.md
│   ├── Corrupted.md
│   └── ...
├── /Plants                  # Thực vật có đặc tính độc đáo
│   ├── README.md            # Tổng quan về thực vật phép thuật và trần tục
│   ├── Magical.md
│   ├── Medicinal.md
│   ├── Poisonous.md
│   └── ...
└── /Hybrid                  # Sinh vật đa hạng mục
    ├── README.md            # Tổng quan về các sinh vật lai
    ├── Centaurs.md
    ├── Merfolk.md
    └── ...
```

## Điều hướng nhanh

- [Các khái niệm cốt lõi](#core-concepts)
- [Loài có tri giác](#sentient-species)
- [Sinh vật phép thuật](#magical-beings)
- [Động vật](#animals)
- [Quái vật](#monsters)
- [Thực vật](#plants)
- [Sinh vật lai](#hybrid-beings)

## Các khái niệm cốt lõi

Tất cả các sinh vật trong OpenFantasy đều được cấu tạo từ ba yếu tố cơ bản, quyết định bản chất và khả năng của chúng:

| Thành phần | Chức năng | Ảnh hưởng |
|-----------|----------|-----------|
| **Exanthis** | Nền tảng vật lý | Sức mạnh, độ bền, độ cứng |
| **Soul** | Ý thức và bản sắc | Ý chí, khả năng sáng tạo, nhận thức |
| **Mana Capacity** | Tiềm năng ma thuật | Khả năng thi triển phép thuật, kháng phép thuật, thanh lọc mana |

Để biết thông tin chi tiết về các nguyên tắc này, hãy xem [tổng quan về Creatures](/codex/Creatures/Creatures.md).

## Loài có tri giác

Những sinh vật thông minh có khả năng hình thành nền văn minh, tạo ra văn hóa và sử dụng phép thuật thông qua nỗ lực có ý thức:

| Loài | Tổng quan | Cân bằng nguyên tố |
|---------|----------|-------------------|
| [Humans](/codex/Creatures/Sentient/Humans.md) | Có khả năng thích ứng và đổi mới với thành phần cân bằng | E: 20-55%, S: 15-45%, M: 15-60% |
| [Elves](/codex/Creatures/Sentient/Elves.md) | Bậc thầy phép thuật sống lâu năm với sự điều chỉnh mana cao | E: 5-25%, S: 5-15%, M: 50-80% |
| [Dark Elves](/codex/Creatures/Sentient/DarkElves.md) | Biến thể elven điều chỉnh bóng tối với khả năng độc đáo | E: 5-25%, S: 10-20%, M: 50-80% |
| [Dwarves](/codex/Creatures/Sentient/Dwarves.md) | Thợ thủ công chắc chắn với nồng độ Exanthis cao | E: 50-70%, S: 20-35%, M: 5-25% |
| [Beastfolk](/codex/Creatures/Sentient/Beastfolk.md) | Những sinh vật đa dạng có thuộc tính giống động vật | E: 35-70%, S: 15-35%, M: 15-40% |
| [Gnomes](/codex/Creatures/Sentient/Gnomes.md) | Sinh vật nhỏ bé, có óc sáng tạo với năng khiếu kỹ thuật | E: 30-50%, S: 30-50%, M: 15-30% |

## Sinh vật phép thuật

Sinh vật được cấu tạo chủ yếu từ năng lượng ma thuật hoặc được tạo ra thông qua các quy trình ma thuật:

| Sinh vật | Tổng quan | Cân bằng nguyên tố |
|-------|----------|-------------------|
| [Fae](/codex/Creatures/Magical/Fae.md) | Những sinh vật siêu phàm của phép thuật gần như thuần khiết | E: 2-10%, S: 15-35%, M: 50-80% |
| [Golems](/codex/Creatures/Magical/Golems.md) | Sinh vật được xây dựng với linh hồn nhân tạo | E: 70-90%, S: 5-15%, M: 5-15% |
| [Shadowfolk](/codex/Creatures/Magical/Shadowfolk.md) | Sinh vật sinh ra từ bóng tối với khả năng thao túng bóng tối | E: 10-30%, S: 20-40%, M: 40-70% |
| [Elementals](/codex/Creatures/Magical/Elementals.md) | Hiện thân thuần túy của các lực lượng nguyên tố | E: 15-30%, S: 5-15%, M: 60-85% |
| [Dragonkin](/codex/Creatures/Magical/Dragonkin.md) | Hậu duệ của rồng với sự tương đồng ma thuật tự nhiên | E: 55-75%, S: 5-15%, M: 20-35% |

## Động vật

Động vật không có tri giác với mức độ thông minh và sự tương đồng ma thuật khác nhau:

| Loại | Mô tả | Ví dụ |
|----------|-------------|----------|
| [Domesticated](/codex/Creatures/Animals/Domesticated.md) | Động vật được lai tạo để sử dụng cho con người | Ngựa, gia súc, chó, mèo, gia cầm |
| [Wild](/codex/Creatures/Animals/Wild.md) | Động vật tự nhiên của các quần xã sinh vật khác nhau | Sói, gấu, đại bàng, hươu |
| [Aquatic](/codex/Creatures/Animals/Aquatic.md) | Sinh vật biển và nước ngọt | Cá, cá voi, bạch tuộc, sinh vật sông |
| [Magical](/codex/Creatures/Animals/Magical.md) | Động vật có thuộc tính ma thuật bẩm sinh | Phượng hoàng, sư tử đầu chim, kỳ lân |

## Quái vật

Những sinh vật nguy hiểm hoặc bất thường gây ra mối đe dọa cho các khu vực văn minh:

| Loại | Mô tả | Ví dụ |
|----------|-------------|----------|
| [Aberrations](/codex/Creatures/Monsters/Aberrations.md) | Sinh vật bất thường với giải phẫu kỳ dị | Mimics, beholders, mind flayers |
| [Undead](/codex/Creatures/Monsters/Undead.md) | Những sinh vật từng sống được hoạt hóa bởi các thế lực đen tối | Zombies, skeletons, spectres |
| [Corrupted](/codex/Creatures/Monsters/Corrupted.md) | Những sinh vật bị biến dạng bởi sự tha hóa ma thuật | Động vật tàn lụi, elementals bị ô uế |
| [Giants](/codex/Creatures/Monsters/Giants.md) | Những sinh vật khổng lồ có sức mạnh phi thường | Stone giants, frost giants, ogres |

## Thực vật

Thực vật có đặc tính độc đáo, cả ma thuật và trần tục:

| Loại | Mô tả | Ví dụ |
|----------|-------------|----------|
| [Magical](/codex/Creatures/Plants/Magical.md) | Thực vật có thuộc tính ma thuật vốn có | Glowroot, dreamleaf, arcane fungi |
| [Medicinal](/codex/Creatures/Plants/Medicinal.md) | Thực vật có đặc tính chữa bệnh | Healer's herb, bloodstop moss, vitality flowers |
| [Poisonous](/codex/Creatures/Plants/Poisonous.md) | Thực vật có đặc tính độc hại | Nightshade, death cap, venom vine |
| [Sentient](/codex/Creatures/Plants/Sentient.md) | Thực vật có ý thức | Treants, whispering willows, mindmoss |

## Sinh vật lai

Những sinh vật kết nối nhiều loại thông qua các cơ chế sinh lý độc đáo:

| Sinh vật | Tổng quan | Cân bằng nguyên tố |
|-------|----------|-------------------|
| [Centaurs](/codex/Creatures/Hybrid/Centaurs.md) | Con lai ngựa-người với trí tuệ tự nhiên | E: 50-70%, S: 20-40%, M: 10-25% |
| [Merfolk](/codex/Creatures/Hybrid/Merfolk.md) | Người cá thủy sinh với sự tương đồng với nước | E: 30-50%, S: 15-35%, M: 25-45% |
| [Sirens](/codex/Creatures/Hybrid/Sirens.md) | Nữ phù thủy thanh nhạc với phép thuật dựa trên âm thanh | E: 15-30%, S: 30-45%, M: 40-60% |

## Đóng góp

Để thêm sinh vật mới vào codex:

1. Xác định loại phù hợp cho sinh vật
2. Sử dụng mẫu liên quan cho danh mục đó
3. Duy trì tính nhất quán với các nguyên tắc thành phần nguyên tố hiện có
4. Bao gồm bối cảnh văn hóa, lịch sử và sinh thái nếu có

---

> *"Để hiểu các sinh vật của thế giới chúng ta là hiểu chính thế giới đó, bởi vì chúng là hiện thân sống động của các năng lượng đa dạng của nó."* — Archsage Lyria Thornheart


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._