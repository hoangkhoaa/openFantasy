# Các Lớp Nhân Vật OpenFantasy

> *"Trong thế giới OpenFantasy, các lớp nhân vật đại diện cho nhiều con đường sức mạnh và chuyên môn hóa khác nhau mà các cá nhân có thể theo đuổi."*

## Tham Khảo Nhanh

- [Cấu Trúc Lớp Nhân Vật](#cau-truc-lop-nhan-vat)
- [Các Lớp Nhân Vật Chính](#cac-lop-nhan-vat-chinh)
- [Tiến Trình Lớp Nhân Vật](#tien-trinh-lop-nhan-vat)
- [Đa Lớp](#da-lop)
- [Tương Tác Giữa Lớp Nhân Vật và Chủng Tộc](#tuong-tac-giua-lop-nhan-vat-va-chung-toc)

## Tổng Quan

Mỗi lớp nhân vật trong OpenFantasy đại diện cho một sự hài hòa độc đáo giữa [**Exanthis**](/codex/Basic/Exanthis.md), [**Souls**](/codex/Basic/Soul.md) (Linh Hồn), và **Mana Capacity** (Dung Lượng Mana), tạo ra một bản giao hưởng các khả năng xác định vai trò của họ trong thế giới.

## Cấu Trúc Lớp Nhân Vật

Các lớp nhân vật được tổ chức thành các danh mục chính, mỗi danh mục có nhiều lớp con hoặc con đường sự nghiệp khác nhau, phát triển từ lớp nhân vật cốt lõi. Các lớp con này đại diện cho các ứng dụng chuyên biệt của các khả năng cơ bản của lớp nhân vật, giống như các biến thể của một chủ đề âm nhạc.

## Các Lớp Nhân Vật Chính

### [**Warrior**](/codex/Classes/Warrior/Warrior.md) (Chiến Binh)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Chiến đấu vật lý và sức mạnh quân sự |
| **Primary Element** (Nguyên Tố Chính) | [**Exanthis**](/codex/Basic/Exanthis.md) |
| **Metaphor** (Ẩn Dụ) | Một chiếc trống mạnh mẽ thúc đẩy nhịp điệu của trận chiến |

**Subclasses:**
- [**Guardian**](/codex/Classes/Warrior/Guardian.md) (Hộ Vệ) - Chuyên gia phòng thủ, người giỏi bảo vệ người khác
- [**Berserker**](/codex/Classes/Warrior/Berserker.md) (Cuồng Chiến Binh) - Chuyên gia tấn công, người bước vào cơn thịnh nộ trong trận chiến
- [**Duelist**](/codex/Classes/Warrior/Duelist.md) (Đấu Sĩ) - Chiến binh chính xác, người giỏi trong chiến đấu một đối một
- [**Commander**](/codex/Classes/Warrior/Commander.md) (Chỉ Huy) - Nhà lãnh đạo chiến thuật, người điều phối các nỗ lực của nhóm
- [**Weaponmaster**](/codex/Classes/Warrior/Weaponmaster.md) (Bậc Thầy Vũ Khí) - Bậc thầy về nhiều loại vũ khí và phong cách chiến đấu

### [**Mage**](/codex/Classes/Mage/Mage.md) (Pháp Sư)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Khả năng phép thuật và sử dụng phép thuật |
| **Primary Element** (Nguyên Tố Chính) | **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Một nhạc trưởng điều khiển các nguyên tố |

**Subclasses:**
- [**Elementalist**](/codex/Classes/Mage/Elementalist.md) (Thuật Sĩ Nguyên Tố) - Bậc thầy về phép thuật nguyên tố (lửa, nước, đất, không khí)
- [**Necromancer**](/codex/Classes/Mage/Necromancer.md) (Pháp Sư Gọi Hồn) - Người thực hành phép thuật chết chóc và linh hồn
- [**Illusionist**](/codex/Classes/Mage/Illusionist.md) (Ảo Thuật Gia) - Người tạo ra các hiệu ứng phép thuật lừa dối
- [**Diviner**](/codex/Classes/Mage/Diviner.md) (Nhà Tiên Tri) - Người tìm kiếm kiến thức thông qua các phương tiện phép thuật
- [**Warlock**](/codex/Classes/Mage/Warlock.md) (Chiến Binh Phép Thuật) - Người giao dịch với các thực thể siêu nhiên để có sức mạnh

### [**Rogue**](/codex/Classes/Rogue/Rogue.md) (Đạo Tặc)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Tàng hình, độ chính xác và sự xảo quyệt |
| **Primary Element** (Nguyên Tố Chính) | [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) |
| **Metaphor** (Ẩn Dụ) | Một cây sáo tinh tế di chuyển vô hình |

**Subclasses:**
- [**Assassin**](/codex/Classes/Rogue/Assassin.md) (Sát Thủ) - Kẻ giết người thầm lặng, người loại bỏ mục tiêu mà không bị phát hiện
- [**Scout**](/codex/Classes/Rogue/Scout.md) (Trinh Sát) - Nhà thám hiểm, người giỏi thu thập thông tin
- [**Trickster**](/codex/Classes/Rogue/Trickster.md) (Kẻ Lừa Bịp) - Kẻ lừa dối sử dụng sự đánh lạc hướng và ảo ảnh
- [**Shadowblade**](/codex/Classes/Rogue/Shadowblade.md) (Kiếm Sĩ Bóng Tối) - Chiến binh tàng hình kết hợp chiến đấu với ngụy trang
- [**Spy**](/codex/Classes/Rogue/Spy.md) (Gián Điệp) - Kẻ xâm nhập thu thập thông tin tình báo từ trong hàng ngũ kẻ thù

### [**Cleric**](/codex/Classes/Cleric/Cleric.md) (Giáo Sĩ)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Phép thuật thần thánh và chữa bệnh |
| **Primary Elements** (Nguyên Tố Chính) | [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) và **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Một dàn hợp xướng kết nối giữa phàm trần và thần thánh |

**Subclasses:**
- [**Healer**](/codex/Classes/Cleric/Healer.md) (Người Chữa Lành) - Chuyên gia về phép thuật phục hồi và chữa bệnh
- [**Paladin**](/codex/Classes/Cleric/Paladin.md) (Hiệp Sĩ) - Chiến binh thánh kết hợp phép thuật thần thánh với chiến đấu
- [**Oracle**](/codex/Classes/Cleric/Oracle.md) (Nhà Tiên Tri) - Người nhận được những tầm nhìn và lời tiên tri thần thánh
- [**Inquisitor**](/codex/Classes/Cleric/Inquisitor.md) (Người Thẩm Vấn) - Người săn lùng dị giáo và các mối đe dọa siêu nhiên
- [**Shaman**](/codex/Classes/Cleric/Shaman.md) (Pháp Sư) - Người giao tiếp với các linh hồn tự nhiên và tổ tiên

### [**Ranger**](/codex/Classes/Ranger/Ranger.md) (Cung Thủ)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Sinh tồn và chiến đấu trong vùng hoang dã |
| **Primary Elements** (Nguyên Tố Chính) | [**Exanthis**](/codex/Basic/Exanthis.md) và [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) |
| **Metaphor** (Ẩn Dụ) | Một nhạc cụ hơi gỗ vang vọng âm thanh của khu rừng |

**Subclasses:**
- [**Beastmaster**](/codex/Classes/Ranger/Beastmaster.md) (Bậc Thầy Thú) - Bạn đồng hành của động vật chiến đấu bên cạnh họ
- [**Hunter**](/codex/Classes/Ranger/Hunter.md) (Thợ Săn) - Người theo dõi giỏi tìm và loại bỏ mục tiêu
- [**Warden**](/codex/Classes/Ranger/Warden.md) (Người Bảo Vệ) - Người bảo vệ các địa điểm tự nhiên và cư dân của chúng
- [**Scout**](/codex/Classes/Ranger/Scout.md) (Trinh Sát) - Nhà thám hiểm giỏi điều hướng các lãnh thổ chưa biết
- [**Survivalist**](/codex/Classes/Ranger/Survivalist.md) (Người Sinh Tồn) - Bậc thầy về sinh tồn trong vùng hoang dã và tháo vát

### [**Artificer**](/codex/Classes/Artificer/Artificer.md) (Thợ Rèn Phép Thuật)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Tạo ra các vật phẩm và thiết bị phép thuật |
| **Primary Element** (Nguyên Tố Chính) | **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Một người thợ thủ công tạo ra các công cụ quyền lực |

**Subclasses:**
- [**Enchanter**](/codex/Classes/Artificer/Enchanter.md) (Người Yểm Bùa) - Người tạo ra các cải tiến phép thuật cho vật phẩm
- [**Alchemist**](/codex/Classes/Artificer/Alchemist.md) (Nhà Giả Kim) - Người pha chế thuốc và các chất phép thuật
- [**Engineer**](/codex/Classes/Artificer/Engineer.md) (Kỹ Sư) - Người xây dựng các thiết bị cơ khí với các thành phần phép thuật
- [**Runemaster**](/codex/Classes/Artificer/Runemaster.md) (Bậc Thầy Chữ Cổ) - Người chế tạo các biểu tượng và chữ khắc phép thuật
- [**Tinkerer**](/codex/Classes/Artificer/Tinkerer.md) (Người Sửa Chữa) - Nhà phát minh các tiện ích và công cụ phép thuật nhỏ

### [**Bard**](/codex/Classes/Bard/Bard.md) (Nhà Thơ)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Trình diễn và truyền cảm hứng |
| **Primary Elements** (Nguyên Tố Chính) | [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) và **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Nhạc sĩ dệt nên phép thuật thông qua các buổi biểu diễn của họ |

**Subclasses:**
- [**College of Eloquence**](/codex/Classes/Bard/Colleges/Eloquence.md) (Hội Khoa Ngôn Ngữ) - Bậc thầy về thuyết phục bằng lời nói và hùng biện hoàn hảo
- [**College of Glamour**](/codex/Classes/Bard/Colleges/Glamour.md) (Hội Hào Nhoáng) - Người biểu diễn kênh phép thuật mê hoặc fey
- [**College of Lore**](/codex/Classes/Bard/Colleges/Lore.md) (Hội Tri Thức) - Người sưu tập kiến thức và bí mật
- [**College of Spirits**](/codex/Classes/Bard/Colleges/Spirits.md) (Hội Linh Hồn) - Người kể chuyện kênh các thực thể siêu nhiên
- [**College of Swords**](/codex/Classes/Bard/Colleges/Swords.md) (Hội Kiếm Sĩ) - Vũ công lưỡi kiếm kết hợp chiến đấu với biểu diễn
- [**College of Valor**](/codex/Classes/Bard/Colleges/Valor.md) (Hội Dũng Cảm) - Người biểu diễn chiến đấu truyền cảm hứng cho lòng dũng cảm và chủ nghĩa anh hùng
- [**College of Whispers**](/codex/Classes/Bard/Colleges/Whispers.md) (Hội Thì Thầm) - Người thao túng nỗi sợ hãi và bí mật
- [**College of Creation**](/codex/Classes/Bard/Colleges/Creation.md) (Hội Sáng Tạo) - Nghệ sĩ tạo ra các đối tượng vật lý thông qua trình diễn

### [**Druid**](/codex/Classes/Druid/Druid.md) (Pháp Sư Tự Nhiên)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Phép thuật tự nhiên và biến hình |
| **Primary Elements** (Nguyên Tố Chính) | [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) và **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Một con tắc kè hoa thích nghi với môi trường xung quanh |

**Subclasses:**
- [**Circle of the Land**](/codex/Classes/Druid/Land.md) (Vòng Tròn Đất) - Người bảo vệ các lãnh thổ tự nhiên
- [**Circle of the Moon**](/codex/Classes/Druid/Moon.md) (Vòng Tròn Mặt Trăng) - Bậc thầy về biến hình hoang dã
- [**Circle of Dreams**](/codex/Classes/Druid/Dreams.md) (Vòng Tròn Giấc Mơ) - Người kết nối với các cõi fey của tự nhiên
- [**Circle of the Shepherd**](/codex/Classes/Druid/Shepherd.md) (Vòng Tròn Người Chăn) - Người bảo vệ động vật và triệu hồi các linh hồn tự nhiên
- [**Circle of Spores**](/codex/Classes/Druid/Spores.md) (Vòng Tròn Bào Tử) - Người kiểm soát chu kỳ sinh tử

### [**Monk**](/codex/Classes/Monk/Monk.md) (Tu Sĩ)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Sức mạnh và kỷ luật bên trong |
| **Primary Elements** (Nguyên Tố Chính) | [**Exanthis**](/codex/Basic/Exanthis.md) và [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) |
| **Metaphor** (Ẩn Dụ) | Một võ sĩ đã làm chủ dòng chảy năng lượng |

**Subclasses:**
- [**Way of the Open Hand**](/codex/Classes/Monk/OpenHand.md) (Đường Tay Không) - Bậc thầy về các kỹ thuật chiến đấu tay không
- [**Way of Shadow**](/codex/Classes/Monk/Shadow.md) (Đường Bóng Tối) - Chiến binh lén lút thao túng bóng tối
- [**Way of the Four Elements**](/codex/Classes/Monk/FourElements.md) (Đường Bốn Nguyên Tố) - Người kiểm soát năng lượng nguyên tố
- [**Way of the Kensei**](/codex/Classes/Monk/Kensei.md) (Đường Kiếm Sĩ) - Bậc thầy vũ khí mở rộng tinh thần của họ vào vũ khí của họ
- [**Way of Tranquility**](/codex/Classes/Monk/Tranquility.md) (Đường Thanh Thản) - Người hòa giải hòa bình chữa lành và bảo vệ

### [**Warlock**](/codex/Classes/Warlock/Warlock.md) (Chiến Binh Phép Thuật)

| Aspect (Khía Cạnh) | Details (Chi Tiết) |
|--------|---------|
| **Focus** (Tập Trung) | Hiệp ước với các thực thể siêu nhiên |
| **Primary Elements** (Nguyên Tố Chính) | [**Soul**](/codex/Basic/Soul.md) (Linh Hồn) và **Mana Capacity** (Dung Lượng Mana) |
| **Metaphor** (Ẩn Dụ) | Một nhạc sĩ đã bán linh hồn của mình để có tài năng |

**Subclasses:**
- [**The Fiend**](/codex/Classes/Warlock/Fiend.md) (Ác Quỷ) - Hiệp ước với các thực thể quỷ dữ
- [**The Archfey**](/codex/Classes/Warlock/Archfey.md) (Đại Tiên) - Hiệp ước với các sinh vật fey mạnh mẽ
- [**The Great Old One**](/codex/Classes/Warlock/GreatOldOne.md) (Thượng Cổ Thần) - Hiệp ước với các thực thể vũ trụ cổ đại
- [**The Celestial**](/codex/Classes/Warlock/Celestial.md) (Thiên Thần) - Hiệp ước với các đấng thần thánh
- [**The Hexblade**](/codex/Classes/Warlock/Hexblade.md) (Lưỡi Kiếm Yểm) - Hiệp ước với một vũ khí tri giác hoặc thực thể bóng tối

## Tiến Trình Lớp Nhân Vật

Các lớp nhân vật trong OpenFantasy tuân theo một hệ thống tiến trình cho phép các cá nhân phát triển khả năng của họ theo thời gian. Sự tiến triển này được thể hiện bằng các cấp độ, mỗi cấp độ cho phép truy cập vào các khả năng và sức mạnh mới, giống như một nhạc sĩ học các bản nhạc ngày càng phức tạp.

### Bậc Cấp Độ

| Tier (Bậc) | Levels (Cấp Độ) | Description (Mô Tả) |
|------|--------|-------------|
| **Novice** (Người Mới Bắt Đầu) | 1-5 | Người mới bắt đầu học các nguyên tắc cơ bản |
| **Adept** (Người Thành Thạo) | 6-10 | Bậc thầy về các kiến thức cơ bản phát triển chuyên môn hóa |
| **Expert** (Chuyên Gia) | 11-15 | Chuyên gia với các khả năng được mài giũa cao |
| **Master** (Bậc Thầy) | 16-20 | Những người đã đạt được sự thành thạo thực sự |
| **Legendary** (Huyền Thoại) | 21+ | Cá nhân vượt qua các giới hạn bình thường |

## Đa Lớp

Một số cá nhân chọn theo đuổi nhiều lớp nhân vật, kết hợp các khả năng từ các con đường khác nhau để tạo ra các tổ hợp độc đáo. Thực tiễn này, được gọi là đa lớp, cho phép tính linh hoạt cao hơn nhưng có thể hạn chế chiều sâu của chuyên môn hóa ở bất kỳ lớp nhân vật đơn lẻ nào, giống như một nhạc sĩ chơi nhiều nhạc cụ nhưng có thể không thành thạo bất kỳ nhạc cụ nào.

## Tương Tác Giữa Lớp Nhân Vật và Chủng Tộc

Các chủng tộc khác nhau có mối liên hệ tự nhiên với các lớp nhân vật nhất định dựa trên thành phần nguyên tố của chúng:

| Species (Chủng Tộc) | Natural Class Affinities (Liên Kết Lớp Nhân Vật Tự Nhiên) |
|---------|--------------------------|
| **Humans** (Loài Người) | Cân bằng liên kết cho tất cả các lớp nhân vật |
| **Elves** (Tiên) | Liên kết mạnh mẽ với các lớp Mage (Pháp Sư), Ranger (Cung Thủ) và Bard (Nhà Thơ) |
| **Dark Elves** (Hắc Tiên) | Liên kết mạnh mẽ với các lớp Mage (Pháp Sư), Rogue (Đạo Tặc) và Warlock (Chiến Binh Phép Thuật) |
| **Dwarves** (Người Lùn) | Liên kết mạnh mẽ với các lớp Warrior (Chiến Binh), Artificer (Thợ Rèn Phép Thuật) và Cleric (Giáo Sĩ) |
| **Beastfolk** (Người Thú) | Liên kết mạnh mẽ với các lớp Ranger (Cung Thủ), Druid (Pháp Sư Tự Nhiên) và Warrior (Chiến Binh) |
| **Dragonkin** (Long Tộc) | Liên kết mạnh mẽ với các lớp Warrior (Chiến Binh), Mage (Pháp Sư) và Warlock (Chiến Binh Phép Thuật) |
| **Fae** (Tiên Nữ) | Liên kết mạnh mẽ với các lớp Bard (Nhà Thơ), Druid (Pháp Sư Tự Nhiên) và Mage (Pháp Sư) |
| **Golems** (Người Máy) | Liên kết mạnh mẽ với các lớp Artificer (Thợ Rèn Phép Thuật) và Warrior (Chiến Binh) |
| **Sirens** (Nàng Tiên Cá) | Liên kết mạnh mẽ với các lớp Bard (Nhà Thơ) và Mage (Pháp Sư) |
| **Shadowfolk** (Người Bóng Tối) | Liên kết mạnh mẽ với các lớp Rogue (Đạo Tặc), Warlock (Chiến Binh Phép Thuật) và Mage (Pháp Sư) |
| **Giants** (Người Khổng Lồ) | Liên kết mạnh mẽ với các lớp Warrior (Chiến Binh) và Druid (Pháp Sư Tự Nhiên) |

---

> Hiểu được bản chất của các lớp nhân vật cung cấp cái nhìn sâu sắc về các con đường sức mạnh đa dạng trong thế giới OpenFantasy, giống như lắng nghe các giai điệu khác nhau tạo nên bản giao hưởng vĩ đại của sự tồn tại.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._