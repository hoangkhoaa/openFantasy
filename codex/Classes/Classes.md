# Các Lớp Nhân Vật OpenFantasy

> *"Trong thế giới của OpenFantasy, các lớp nhân vật đại diện cho những con đường sức mạnh và chuyên môn hóa khác nhau mà các cá nhân có thể theo đuổi."*

## Tham Khảo Nhanh

- [Cấu Trúc Lớp](#cau-truc-lop)
- [Các Lớp Chính](#cac-lop-chinh)
- [Tiến Trình Lớp](#tien-trinh-lop)
- [Đa Lớp](#da-lop)
- [Tương Tác Lớp-Chủng Tộc](#tuong-tac-lop-chung-toc)

## Tổng Quan

Mỗi lớp nhân vật trong OpenFantasy đại diện cho sự hài hòa độc đáo giữa [**Exanthis**](/codex/Basic/Exanthis.md), [**Souls**](/codex/Basic/Soul.md) và **Mana Capacity**, tạo ra một bản giao hưởng các khả năng xác định vai trò của họ trong thế giới.

## Cấu Trúc Lớp

Các lớp được tổ chức thành các danh mục chính, mỗi danh mục có nhiều lớp con hoặc con đường sự nghiệp phân nhánh từ lớp cốt lõi. Các lớp con này đại diện cho các ứng dụng chuyên biệt của các khả năng cơ bản của lớp, giống như các biến thể của một chủ đề âm nhạc.

## Các Lớp Chính

### [**Warrior**](/codex/Classes/Warrior/Warrior.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Chiến đấu vật lý và sức mạnh quân sự |
| **Primary Element** | [**Exanthis**](/codex/Basic/Exanthis.md) |
| **Metaphor** | Một cái trống mạnh mẽ thúc đẩy nhịp điệu của trận chiến |

**Subclasses:**
- [**Guardian**](/codex/Classes/Warrior/Guardian.md) - Chuyên gia phòng thủ xuất sắc trong việc bảo vệ người khác
- [**Berserker**](/codex/Classes/Warrior/Berserker.md) - Chuyên gia tấn công bước vào cơn thịnh nộ trong trận chiến
- [**Duelist**](/codex/Classes/Warrior/Duelist.md) - Chiến binh chính xác xuất sắc trong chiến đấu một đối một
- [**Commander**](/codex/Classes/Warrior/Commander.md) - Nhà lãnh đạo chiến thuật điều phối các nỗ lực của nhóm
- [**Weaponmaster**](/codex/Classes/Warrior/Weaponmaster.md) - Bậc thầy về nhiều loại vũ khí và phong cách chiến đấu

### [**Mage**](/codex/Classes/Mage/Mage.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Khả năng phép thuật và niệm chú |
| **Primary Element** | **Mana Capacity** |
| **Metaphor** | Một người chỉ huy dàn dựng các nguyên tố |

**Subclasses:**
- [**Elementalist**](/codex/Classes/Mage/Elementalist.md) - Bậc thầy về ma thuật nguyên tố (lửa, nước, đất, không khí)
- [**Necromancer**](/codex/Classes/Mage/Necromancer.md) - Người thực hành ma thuật linh hồn và cái chết
- [**Illusionist**](/codex/Classes/Mage/Illusionist.md) - Người tạo ra các hiệu ứng ma thuật lừa dối
- [**Diviner**](/codex/Classes/Mage/Diviner.md) - Người tìm kiếm kiến ​​thức thông qua các phương tiện ma thuật
- [**Warlock**](/codex/Classes/Mage/Warlock.md) - Người giao dịch với các thực thể siêu nhiên để có sức mạnh

### [**Rogue**](/codex/Classes/Rogue/Rogue.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Tàng hình, chính xác và xảo quyệt |
| **Primary Element** | [**Soul**](/codex/Basic/Soul.md) |
| **Metaphor** | Một cây sáo tinh tế di chuyển vô hình |

**Subclasses:**
- [**Assassin**](/codex/Classes/Rogue/Assassin.md) - Kẻ giết người thầm lặng loại bỏ mục tiêu mà không bị phát hiện
- [**Scout**](/codex/Classes/Rogue/Scout.md) - Nhà thám hiểm xuất sắc trong việc thu thập thông tin
- [**Trickster**](/codex/Classes/Rogue/Trickster.md) - Kẻ lừa dối sử dụng sự đánh lạc hướng và ảo ảnh
- [**Shadowblade**](/codex/Classes/Rogue/Shadowblade.md) - Chiến binh tàng hình kết hợp chiến đấu với ngụy trang
- [**Spy**](/codex/Classes/Rogue/Spy.md) - Kẻ xâm nhập thu thập thông tin tình báo từ trong hàng ngũ kẻ thù

### [**Cleric**](/codex/Classes/Cleric/Cleric.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Ma thuật thiêng liêng và chữa bệnh |
| **Primary Elements** | [**Soul**](/codex/Basic/Soul.md) và **Mana Capacity** |
| **Metaphor** | Một dàn hợp xướng kết nối giữa phàm trần và thần thánh |

**Subclasses:**
- [**Healer**](/codex/Classes/Cleric/Healer.md) - Chuyên gia về ma thuật phục hồi và chữa bệnh
- [**Paladin**](/codex/Classes/Cleric/Paladin.md) - Chiến binh thánh kết hợp ma thuật thiêng liêng với chiến đấu
- [**Oracle**](/codex/Classes/Cleric/Oracle.md) - Người nhận những khải tượng và lời tiên tri thiêng liêng
- [**Inquisitor**](/codex/Classes/Cleric/Inquisitor.md) - Thợ săn dị giáo và các mối đe dọa siêu nhiên
- [**Shaman**](/codex/Classes/Cleric/Shaman.md) - Người giao tiếp với các linh hồn tự nhiên và tổ tiên

### [**Ranger**](/codex/Classes/Ranger/Ranger.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Sinh tồn và chiến đấu trong tự nhiên hoang dã |
| **Primary Elements** | [**Exanthis**](/codex/Basic/Exanthis.md) và [**Soul**](/codex/Basic/Soul.md) |
| **Metaphor** | Một nhạc cụ hơi gỗ vang vọng âm thanh của khu rừng |

**Subclasses:**
- [**Beastmaster**](/codex/Classes/Ranger/Beastmaster.md) - Người bạn đồng hành của động vật chiến đấu bên cạnh họ
- [**Hunter**](/codex/Classes/Ranger/Hunter.md) - Người theo dõi xuất sắc trong việc tìm kiếm và loại bỏ mục tiêu
- [**Warden**](/codex/Classes/Ranger/Warden.md) - Người bảo vệ các địa điểm tự nhiên và cư dân của chúng
- [**Scout**](/codex/Classes/Ranger/Scout.md) - Nhà thám hiểm xuất sắc trong việc điều hướng các lãnh thổ chưa biết
- [**Survivalist**](/codex/Classes/Ranger/Survivalist.md) - Bậc thầy về sinh tồn và tài nguyên trong tự nhiên hoang dã

### [**Artificer**](/codex/Classes/Artificer/Artificer.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Tạo ra các vật phẩm và thiết bị ma thuật |
| **Primary Element** | **Mana Capacity** |
| **Metaphor** | Một thợ thủ công tạo ra các công cụ sức mạnh |

**Subclasses:**
- [**Enchanter**](/codex/Classes/Artificer/Enchanter.md) - Người tạo ra các cải tiến ma thuật cho các vật phẩm
- [**Alchemist**](/codex/Classes/Artificer/Alchemist.md) - Người pha chế thuốc và các chất ma thuật
- [**Engineer**](/codex/Classes/Artificer/Engineer.md) - Người xây dựng các thiết bị cơ khí với các thành phần ma thuật
- [**Runemaster**](/codex/Classes/Artificer/Runemaster.md) - Người chế tạo các biểu tượng và chữ khắc ma thuật
- [**Tinkerer**](/codex/Classes/Artificer/Tinkerer.md) - Nhà phát minh các công cụ và tiện ích ma thuật nhỏ

### [**Bard**](/codex/Classes/Bard/Bard.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Biểu diễn và truyền cảm hứng |
| **Primary Elements** | [**Soul**](/codex/Basic/Soul.md) và **Mana Capacity** |
| **Metaphor** | Nhạc sĩ dệt ma thuật thông qua các buổi biểu diễn của họ |

**Subclasses:**
- [**College of Eloquence**](/codex/Classes/Bard/Colleges/Eloquence.md) - Bậc thầy về thuyết phục bằng lời nói và hùng biện hoàn hảo
- [**College of Glamour**](/codex/Classes/Bard/Colleges/Glamour.md) - Người biểu diễn truyền tải ma thuật mê hoặc fey
- [**College of Lore**](/codex/Classes/Bard/Colleges/Lore.md) - Người thu thập kiến ​​thức và bí mật
- [**College of Spirits**](/codex/Classes/Bard/Colleges/Spirits.md) - Người kể chuyện truyền tải các thực thể siêu nhiên
- [**College of Swords**](/codex/Classes/Bard/Colleges/Swords.md) - Vũ công lưỡi kiếm kết hợp chiến đấu với biểu diễn
- [**College of Valor**](/codex/Classes/Bard/Colleges/Valor.md) - Người biểu diễn chiến đấu truyền cảm hứng can đảm và chủ nghĩa anh hùng
- [**College of Whispers**](/codex/Classes/Bard/Colleges/Whispers.md) - Kẻ thao túng nỗi sợ hãi và bí mật
- [**College of Creation**](/codex/Classes/Bard/Colleges/Creation.md) - Nghệ sĩ tạo ra các đối tượng vật lý thông qua biểu diễn

### [**Druid**](/codex/Classes/Druid/Druid.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Ma thuật tự nhiên và biến hình |
| **Primary Elements** | [**Soul**](/codex/Basic/Soul.md) và **Mana Capacity** |
| **Metaphor** | Một con tắc kè hoa thích nghi với môi trường xung quanh |

**Subclasses:**
- [**Circle of the Land**](/codex/Classes/Druid/Land.md) - Người bảo vệ các vùng lãnh thổ tự nhiên
- [**Circle of the Moon**](/codex/Classes/Druid/Moon.md) - Bậc thầy về biến hình hoang dã
- [**Circle of Dreams**](/codex/Classes/Druid/Dreams.md) - Người kết nối với các cõi fey của tự nhiên
- [**Circle of the Shepherd**](/codex/Classes/Druid/Shepherd.md) - Người bảo vệ động vật và triệu hồi linh hồn tự nhiên
- [**Circle of Spores**](/codex/Classes/Druid/Spores.md) - Người kiểm soát chu kỳ sinh tử

### [**Monk**](/codex/Classes/Monk/Monk.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Sức mạnh và kỷ luật bên trong |
| **Primary Elements** | [**Exanthis**](/codex/Basic/Exanthis.md) và [**Soul**](/codex/Basic/Soul.md) |
| **Metaphor** | Một võ sĩ đã làm chủ được dòng chảy năng lượng |

**Subclasses:**
- [**Way of the Open Hand**](/codex/Classes/Monk/OpenHand.md) - Bậc thầy về kỹ thuật chiến đấu tay không
- [**Way of Shadow**](/codex/Classes/Monk/Shadow.md) - Chiến binh tàng hình thao túng bóng tối
- [**Way of the Four Elements**](/codex/Classes/Monk/FourElements.md) - Người kiểm soát năng lượng nguyên tố
- [**Way of the Kensei**](/codex/Classes/Monk/Kensei.md) - Bậc thầy vũ khí mở rộng tinh thần của họ vào vũ khí của họ
- [**Way of Tranquility**](/codex/Classes/Monk/Tranquility.md) - Người hòa giải hòa bình chữa lành và bảo vệ

### [**Warlock**](/codex/Classes/Warlock/Warlock.md)

| Aspect | Details |
|--------|---------|
| **Focus** | Hiệp ước với các thực thể siêu nhiên |
| **Primary Elements** | [**Soul**](/codex/Basic/Soul.md) và **Mana Capacity** |
| **Metaphor** | Một nhạc sĩ đã bán linh hồn của mình để có tài năng |

**Subclasses:**
- [**The Fiend**](/codex/Classes/Warlock/Fiend.md) - Hiệp ước với các thực thể quỷ dữ
- [**The Archfey**](/codex/Classes/Warlock/Archfey.md) - Hiệp ước với các sinh vật fey mạnh mẽ
- [**The Great Old One**](/codex/Classes/Warlock/GreatOldOne.md) - Hiệp ước với các thực thể vũ trụ cổ đại
- [**The Celestial**](/codex/Classes/Warlock/Celestial.md) - Hiệp ước với các thần thánh
- [**The Hexblade**](/codex/Classes/Warlock/Hexblade.md) - Hiệp ước với một vũ khí có tri giác hoặc thực thể bóng tối

## Tiến Trình Lớp

Các lớp trong OpenFantasy tuân theo một hệ thống tiến trình cho phép các cá nhân phát triển khả năng của họ theo thời gian. Tiến trình này được thể hiện bằng các cấp độ, mỗi cấp độ cấp quyền truy cập vào các khả năng và sức mạnh mới, giống như một nhạc sĩ học các bản nhạc ngày càng phức tạp.

### Bậc Cấp Độ

| Tier | Levels | Description |
|------|--------|-------------|
| **Novice** | 1-5 | Người mới bắt đầu học những điều cơ bản |
| **Adept** | 6-10 | Bậc thầy về những điều cơ bản phát triển chuyên môn hóa |
| **Expert** | 11-15 | Chuyên gia với các khả năng được mài giũa cao |
| **Master** | 16-20 | Những người đã đạt đến sự làm chủ thực sự |
| **Legendary** | 21+ | Cá nhân vượt qua những giới hạn thông thường |

## Đa Lớp

Một số cá nhân chọn theo đuổi nhiều lớp, kết hợp các khả năng từ các con đường khác nhau để tạo ra các kết hợp độc đáo. Thực hành này, được gọi là đa lớp, cho phép linh hoạt hơn nhưng có thể hạn chế độ sâu của chuyên môn hóa trong bất kỳ một lớp nào, giống như một nhạc sĩ chơi nhiều nhạc cụ nhưng có thể không thành thạo bất kỳ nhạc cụ nào.

## Tương Tác Lớp-Chủng Tộc

Các chủng tộc khác nhau có mối liên hệ tự nhiên với một số lớp nhất định dựa trên thành phần nguyên tố của chúng:

| Species | Natural Class Affinities |
|---------|--------------------------|
| **Humans** | Sự liên hệ cân bằng cho tất cả các lớp |
| **Elves** | Mối liên hệ mạnh mẽ với các lớp Mage, Ranger và Bard |
| **Dark Elves** | Mối liên hệ mạnh mẽ với các lớp Mage, Rogue và Warlock |
| **Dwarves** | Mối liên hệ mạnh mẽ với các lớp Warrior, Artificer và Cleric |
| **Beastfolk** | Mối liên hệ mạnh mẽ với các lớp Ranger, Druid và Warrior |
| **Dragonkin** | Mối liên hệ mạnh mẽ với các lớp Warrior, Mage và Warlock |
| **Fae** | Mối liên hệ mạnh mẽ với các lớp Bard, Druid và Mage |
| **Golems** | Mối liên hệ mạnh mẽ với các lớp Artificer và Warrior |
| **Sirens** | Mối liên hệ mạnh mẽ với các lớp Bard và Mage |
| **Shadowfolk** | Mối liên hệ mạnh mẽ với các lớp Rogue, Warlock và Mage |
| **Giants** | Mối liên hệ mạnh mẽ với các lớp Warrior và Druid |

---

> Hiểu bản chất của các lớp cung cấp cái nhìn sâu sắc về những con đường sức mạnh đa dạng trong thế giới **OpenFantasy**, giống như lắng nghe những giai điệu khác nhau tạo nên bản giao hưởng vĩ đại của sự tồn tại.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._