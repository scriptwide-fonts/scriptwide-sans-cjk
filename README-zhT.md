# Scriptwide Sans CJK

基於思源黑體及其衍生字體的泛中日韓字體

![FontForge](https://github.com/user-attachments/assets/f1d600e7-22b2-49cb-a39e-4fef99c6e883)

*你已經可以看到這些字造得多麽的爛。*

此字體使用OFL授權。

## 描述

基於思源黑體及其衍生字體，合併後加上若干字型的字體。

請注意，字體未經微調，因此在低解析度下的效果不太理想。因此建議先使用思源黑體，並使用Scriptwide Sans CJK作為後備。

若然漢字必須採用黑體，則應使用[落塵無襯](https://github.com/Losketch/LorchinSans)作為第二後備字體。

字形不一定遵循任何來源，但大多數應該遵循國標（G源）或韓國（K源）（作為結合國標的遍黑體以及韓國標準（不完全是越南標準）𦁣夕源的結果）。

我計劃將所有字形大致上轉換為 `K→J→S→V→H→M→T→U→G→P` 來源，但這可能永遠不會發生。

Scriptwide Sans CJK 由三個字體組成，以支援大量中日韓文字。

## 關於映射問題

我不太想直接聯絡遍黑體團隊，但`U+26979 𦥹`的字符應映射到`U+22C93 𢲓`。此將於下一個Scriptwide Sans CJK-B版本中修復。

以下為[字統網](zi.tools)的相關圖片。

`U+22C93`: ![Screenshot 2025-01-18 214611](https://github.com/user-attachments/assets/a77f84eb-4d74-4d55-b328-9113b651c11f)

`U+26979`: ![Screenshot 2025-01-18 214556](https://github.com/user-attachments/assets/4698276e-ec09-43f4-859b-ed967e0be0b0)

## Coverage

![ScriptwideA](ScriptwideA.png)

![ScriptwideB](ScriptwideB.png)

![ScriptwideC](ScriptwideC.png)

以上為<https://github.com/NightFurySL2001/CJK-character-count>的截圖。

此外，遍黑體亦提供了暫定J區的字，但萬國碼可能會發生變化。

## 問題

1. 為什麼 Scriptwide Sans CJK 由三個字體組成？
  * Scriptwide Sans CJK-A涵蓋BMP，Scriptwide Sans CJK-B涵蓋B區，Scriptwide Sans CJK-C則涵蓋其他區域。一個字體只支援65535個字形，因此必須拆分字體。
2. 那兩個字體呢？
  * 那真是個好問題
3. 為什麽不將整個落塵無襯字體整合到字體內？
  * 較複雜的字形直接整合了落塵無襯的一些字形。然而，落塵無襯的字形通常不符合思源黑體的外貌。
4. 那為什麽某些字形還是直接從落塵無襯採用？
  * 由於「技術問題」（意思是我太懶了），我無法繪製某些部首的字形。在這些情況下，落塵無襯的字形必定會比我所做的更美觀。
5. 為什麼有些字形看起來很糟？
  * 由於某些字形比較複雜，有些字形會直接繪製並加粗。
6. 我可以擴展這個字體嗎？
  * 可以，但你的字體必須符合OFL授權。
7. 你寫的這些問題有什麽用處？
  * 沒用處。

## 免責聲明

這不是專業字體。

字形不一定遵循任何來源。

對於因誤用此字體而造成的任何損害，或在任何場景中使用時可能產生的任何誤解，本人一概不負責。

如果某些字形不準確，請建立議題（Issue）。

## 授權

這些字體根據OFL授權。詳細資訊請參閱 [許可證文件](LICENSE) 或 [OFL 網站](https://openfontlicense.org/)。

此內容部分取自[遍黑體](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project/blob/main/README.en.md#license)以及OFL網站。

以下內容不能取代法律建議。請參閱OFL以了解更多詳細資訊。

### 你可以：

* 安裝此字體。
* 修改此字體。
* 轉發此字體。（請確保修改後的字體符合OFL授權，並且不使用任何OFL保留名稱。Scriptwide 本身並非保留名稱，但為了避免混淆，我不建議在任何衍生字體中使用“Scriptwide”名稱。）
* 免費使用這些字體進行各種設計工作，包括商業和非商業用途，無需事先通知。
* 不需作出鳴謝，使用這些字體。（但是如果有的話我會非常感激。）

### 你不可以：

* 自行出售字體檔案的任何部分。
  * 據稱有許多網路商家（通常在淘寶上）非法轉售 OFL 字體。請不要從他們那裡購買，因為這嚴重地侵犯OFL授權。
* 在非 OFL 許可下重新發布這些字體。
* 將這些字體用於非法用途或危害電腦系統正常運作的用途。
 
## 鳴謝

| 字體 | 描述 | 版權 |
| --- | --- | --- |
| [思源黑體](https://github.com/adobe-fonts/source-han-sans) | 原始字體 | Google, Adobe |
| [遍黑體](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project) | 大部分字形 | Fitzgerald Porthmouth Koenigsegg [et. al.](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project?tab=readme-ov-file#%E8%B4%A1%E7%8C%AE%E8%80%85) |
| [Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode) | 遍黑體變更 | MY1L |
| [𦁣夕源](https://github.com/TKYKmori/Gothic-Nguyen) | 漢喃字 | TKYKmori, Han-Nom Revival Committee of Vietnam |
| [間隙黑體](https://oppekebekkanko.booth.pm/items/2117070) | 部分字形 | (booth.pm) oppekebekkanko |
| [Yuu黑體](https://github.com/Steve-Yuu/Yuu-Gothic) | 部分字形 | Steve-Yuu |
| [落塵無襯](https://github.com/Losketch/LorchinSans) | 部分零件、字形 | Losketch |
| [昭源黑體](https://github.com/chiron-fonts/chiron-hei-hk) | 部分字形 | chiron-fonts 