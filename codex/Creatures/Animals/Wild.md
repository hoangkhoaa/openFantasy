### OpenFantasy Core Combat Mechanics

This document outlines the core combat mechanics for OpenFantasy. These mechanics are designed to be modular and extensible, allowing for a wide variety of combat styles and scenarios.

#### Key Concepts

*   **Actor (Diễn viên):** Any entity that can participate in combat. This includes player characters, non-player characters, and even objects.
*   **Action (Hành động):** A discrete unit of activity that an Actor (Diễn viên) can perform during combat, such as attacking, defending, or casting a spell.
*   **Attribute (Thuộc tính):** A fundamental characteristic of an Actor (Diễn viên), such as Strength (Sức mạnh), Dexterity (Sự khéo léo), or Intelligence (Trí thông minh).
*   **Skill (Kỹ năng):** A learned ability that allows an Actor (Diễn viên) to perform specific Actions (Hành động) more effectively.
*   **Combat Round (Hiệp chiến đấu):** A discrete unit of time during which all Actors (Diễn viên) have an opportunity to perform an Action (Hành động).

#### Combat Sequence

1.  **Initiative (Khởi đầu):** At the start of each Combat Round (Hiệp chiến đấu), each Actor (Diễn viên) rolls Initiative (Khởi đầu). The order of Actors (Diễn viên) in the Combat Round (Hiệp chiến đấu) is determined by their Initiative (Khởi đầu) roll.
2.  **Action (Hành động):** Starting with the Actor (Diễn viên) with the highest Initiative (Khởi đầu), each Actor (Diễn viên) performs one Action (Hành động).
3.  **Resolution (Giải quyết):** The effects of each Action (Hành động) are resolved immediately after the Action (Hành động) is performed. This may involve rolling dice, comparing Attributes (Thuộc tính), or applying modifiers.
4.  **End of Round (Kết thúc hiệp):** Once all Actors (Diễn viên) have performed an Action (Hành động), the Combat Round (Hiệp chiến đấu) ends, and a new Combat Round (Hiệp chiến đấu) begins at step 1.

#### Actions

Actors (Diễn viên) can perform a variety of Actions (Hành động) during combat. Some common Actions (Hành động) include:

*   **Attack (Tấn công):** An attempt to harm another Actor (Diễn viên).
*   **Defend (Phòng thủ):** An attempt to protect oneself from an Attack (Tấn công).
*   **Cast Spell (Thi triển phép thuật):** An attempt to cast a magical spell.
*   **Move (Di chuyển):** An attempt to move to a different location.
*   **Use Item (Sử dụng vật phẩm):** An attempt to use an item, such as a potion or a weapon.

#### Example: Attack Action

When an Actor (Diễn viên) performs an Attack (Tấn công) Action (Hành động), the following steps occur:

1.  **Roll Attack (Tung xúc xắc tấn công):** The Actor (Diễn viên) rolls an Attack (Tấn công) roll, which is typically a d20 roll plus an Attack (Tấn công) bonus.
2.  **Compare to Defense (So sánh với phòng thủ):** The Attack (Tấn công) roll is compared to the target's Defense (Phòng thủ) score.
3.  **Determine Hit or Miss (Xác định trúng hay trượt):** If the Attack (Tấn công) roll is greater than or equal to the target's Defense (Phòng thủ) score, the Attack (Tấn công) hits. Otherwise, the Attack (Tấn công) misses.
4.  **Roll Damage (Tung xúc xắc sát thương):** If the Attack (Tấn công) hits, the Actor (Diễn viên) rolls a Damage (Sát thương) roll, which is determined by the weapon or spell being used.
5.  **Apply Damage (Áp dụng sát thương):** The Damage (Sát thương) roll is subtracted from the target's Hit Points (Điểm trúng đích).

#### Tables

##### Attribute Examples

| Attribute (Thuộc tính) | Description (Mô tả)                                                                 |
| ----------------------- | --------------------------------------------------------------------------------- |
| Strength (Sức mạnh)     | Measures physical power and ability to carry heavy objects.                        |
| Dexterity (Sự khéo léo)  | Measures agility, reflexes, and fine motor skills.                               |
| Intelligence (Trí thông minh) | Measures knowledge, reasoning, and problem-solving ability.                     |
| Wisdom (Sự khôn ngoan)   | Measures perception, insight, and common sense.                                 |
| Charisma (Sức lôi cuốn)  | Measures force of personality, persuasiveness, and leadership ability.           |

##### Skill Examples

| Skill (Kỹ năng)       | Attribute (Thuộc tính) | Description (Mô tả)                                                                        |
| ----------------------- | ----------------------- | ---------------------------------------------------------------------------------------- |
| Athletics (Điền kinh)   | Strength (Sức mạnh)     | Measures ability to perform feats of physical strength and endurance.                      |
| Acrobatics (Nhào lộn)  | Dexterity (Sự khéo léo)  | Measures ability to perform acrobatic maneuvers.                                         |
| Arcana (Bí thuật)     | Intelligence (Trí thông minh) | Measures knowledge of magic and magical phenomena.                                           |
| Perception (Tri giác)   | Wisdom (Sự khôn ngoan)   | Measures ability to notice details and perceive subtle cues.                               |
| Persuasion (Thuyết phục) | Charisma (Sức lôi cuốn)  | Measures ability to influence others through charm, reason, or intimidation.                 |

### Cơ Chế Chiến Đấu Cốt Lõi của OpenFantasy

Tài liệu này phác thảo cơ chế chiến đấu cốt lõi cho OpenFantasy. Các cơ chế này được thiết kế để có tính mô-đun và khả năng mở rộng, cho phép nhiều kiểu chiến đấu và tình huống khác nhau.

#### Các Khái Niệm Chính

*   **Actor (Diễn viên):** Bất kỳ thực thể nào có thể tham gia chiến đấu. Điều này bao gồm nhân vật người chơi, nhân vật không phải người chơi và thậm chí cả đồ vật.
*   **Action (Hành động):** Một đơn vị hoạt động riêng biệt mà Actor (Diễn viên) có thể thực hiện trong khi chiến đấu, chẳng hạn như tấn công, phòng thủ hoặc thi triển phép thuật.
*   **Attribute (Thuộc tính):** Một đặc điểm cơ bản của Actor (Diễn viên), chẳng hạn như Strength (Sức mạnh), Dexterity (Sự khéo léo) hoặc Intelligence (Trí thông minh).
*   **Skill (Kỹ năng):** Một khả năng đã học được cho phép Actor (Diễn viên) thực hiện các Action (Hành động) cụ thể hiệu quả hơn.
*   **Combat Round (Hiệp chiến đấu):** Một đơn vị thời gian riêng biệt trong đó tất cả Actors (Diễn viên) đều có cơ hội thực hiện một Action (Hành động).

#### Trình Tự Chiến Đấu

1.  **Initiative (Khởi đầu):** Khi bắt đầu mỗi Combat Round (Hiệp chiến đấu), mỗi Actor (Diễn viên) tung Initiative (Khởi đầu). Thứ tự của Actors (Diễn viên) trong Combat Round (Hiệp chiến đấu) được xác định bởi tung Initiative (Khởi đầu) của họ.
2.  **Action (Hành động):** Bắt đầu với Actor (Diễn viên) có Initiative (Khởi đầu) cao nhất, mỗi Actor (Diễn viên) thực hiện một Action (Hành động).
3.  **Resolution (Giải quyết):** Các hiệu ứng của mỗi Action (Hành động) được giải quyết ngay sau khi Action (Hành động) được thực hiện. Điều này có thể liên quan đến việc tung xúc xắc, so sánh Attributes (Thuộc tính) hoặc áp dụng các sửa đổi.
4.  **End of Round (Kết thúc hiệp):** Khi tất cả Actors (Diễn viên) đã thực hiện một Action (Hành động), Combat Round (Hiệp chiến đấu) kết thúc và một Combat Round (Hiệp chiến đấu) mới bắt đầu ở bước 1.

#### Các Hành Động

Actors (Diễn viên) có thể thực hiện nhiều Action (Hành động) khác nhau trong khi chiến đấu. Một số Action (Hành động) phổ biến bao gồm:

*   **Attack (Tấn công):** Một nỗ lực gây hại cho Actor (Diễn viên) khác.
*   **Defend (Phòng thủ):** Một nỗ lực để tự bảo vệ mình khỏi một Attack (Tấn công).
*   **Cast Spell (Thi triển phép thuật):** Một nỗ lực để thi triển một phép thuật.
*   **Move (Di chuyển):** Một nỗ lực để di chuyển đến một vị trí khác.
*   **Use Item (Sử dụng vật phẩm):** Một nỗ lực để sử dụng một vật phẩm, chẳng hạn như thuốc hoặc vũ khí.

#### Ví dụ: Hành Động Tấn Công

Khi một Actor (Diễn viên) thực hiện một Attack (Tấn công) Action (Hành động), các bước sau sẽ xảy ra:

1.  **Roll Attack (Tung xúc xắc tấn công):** Actor (Diễn viên) tung một tung xúc xắc Attack (Tấn công), thường là một tung xúc xắc d20 cộng với một tiền thưởng Attack (Tấn công).
2.  **Compare to Defense (So sánh với phòng thủ):** Tung xúc xắc Attack (Tấn công) được so sánh với điểm Defense (Phòng thủ) của mục tiêu.
3.  **Determine Hit or Miss (Xác định trúng hay trượt):** Nếu tung xúc xắc Attack (Tấn công) lớn hơn hoặc bằng điểm Defense (Phòng thủ) của mục tiêu, thì Attack (Tấn công) trúng. Nếu không, Attack (Tấn công) trượt.
4.  **Roll Damage (Tung xúc xắc sát thương):** Nếu Attack (Tấn công) trúng, Actor (Diễn viên) tung một tung xúc xắc Damage (Sát thương), được xác định bởi vũ khí hoặc phép thuật đang được sử dụng.
5.  **Apply Damage (Áp dụng sát thương):** Tung xúc xắc Damage (Sát thương) được trừ vào Hit Points (Điểm trúng đích) của mục tiêu.

#### Các Bảng

##### Ví Dụ về Thuộc Tính

| Attribute (Thuộc tính)     | Description (Mô tả)                                                                                    |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| Strength (Sức mạnh)       | Đo sức mạnh thể chất và khả năng mang vật nặng.                                                               |
| Dexterity (Sự khéo léo)    | Đo sự nhanh nhẹn, phản xạ và kỹ năng vận động tinh vi.                                                        |
| Intelligence (Trí thông minh) | Đo kiến thức, khả năng suy luận và giải quyết vấn đề.                                                            |
| Wisdom (Sự khôn ngoan)     | Đo khả năng nhận thức, sự thấu hiểu và lẽ thường.                                                              |
| Charisma (Sức lôi cuốn)    | Đo sức mạnh tính cách, khả năng thuyết phục và khả năng lãnh đạo.                                                  |

##### Ví Dụ về Kỹ Năng

| Skill (Kỹ năng)         | Attribute (Thuộc tính)     | Description (Mô tả)                                                                                         |
| -------------------------- | -------------------------- | --------------------------------------------------------------------------------------------------------- |
| Athletics (Điền kinh)     | Strength (Sức mạnh)       | Đo khả năng thực hiện các kỳ tích về sức mạnh thể chất và sức bền.                                                    |
| Acrobatics (Nhào lộn)    | Dexterity (Sự khéo léo)    | Đo khả năng thực hiện các thao tác nhào lộn.                                                                  |
| Arcana (Bí thuật)       | Intelligence (Trí thông minh) | Đo kiến thức về phép thuật và các hiện tượng huyền diệu.                                                              |
| Perception (Tri giác)     | Wisdom (Sự khôn ngoan)     | Đo khả năng nhận thấy các chi tiết và nhận biết các dấu hiệu tinh tế.                                                     |
| Persuasion (Thuyết phục)   | Charisma (Sức lôi cuốn)    | Đo khả năng gây ảnh hưởng đến người khác thông qua sự quyến rũ, lý lẽ hoặc đe dọa.                                          |


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._