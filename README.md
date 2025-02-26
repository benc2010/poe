在《流亡黯道》（Path of Exile）中，物品過濾器是一個強大的工具，允許玩家自定義顯示在地面上的物品。以下是所有物品類型及其語法的列表，包括英文和繁體中文的對應翻譯。

### 物品類型（Item Types）
1. **普通物品（Normal）**
2. **魔法物品（Magic）**
3. **稀有物品（Rare）**
4. **獨特物品（Unique）**
5. **基礎類型（Base Type）**
6. **貨幣（Currency）**
7. **地圖（Maps）**
8. **寶石（Gems）**
9. **裝備（Equipment）**
10. **集群珠寶（Cluster Jewels）**

### 語法（Syntax）
- **顯示（Show）**: 如果所有條件匹配，顯示物品。
  - 例子: `Show Rarity >= Rare`
  
- **隱藏（Hide）**: 如果所有條件匹配，隱藏物品。
  - 例子: `Hide BaseType "Scroll of Wisdom"`
  
- **最小化（Minimal）**: 匹配的物品將其標籤設置為最小大小，僅在殘酷模式下使用。
  - 例子: `Minimal BaseType "Scroll of Wisdom"`
  
- **繼續（Continue）**: 表示當物品匹配此區塊時，過濾規則匹配不應停止。
  - 例子: `Hide ItemLevel < 85 Continue Show ItemLevel > 80 Sockets 6 PlayEffect Blue`

### 條件（Conditions）
- **Rarity**: 物品的稀有度（Normal, Magic, Rare, Unique）
- **BaseType**: 基礎類型名稱
- **ItemLevel**: 物品等級
- **Quality**: 物品的品質
- **AreaLevel**: 物品掉落的區域等級

### 操作符（Operators）
- `=`: 等於
- `!=`: 不等於
- `<`: 小於
- `<=`: 小於或等於
- `>`: 大於
- `>=`: 大於或等於
- `==`: 精確匹配

這些語法和條件可以組合使用，以創建自定義的物品過濾器，幫助玩家更有效地管理他們的物品。對於想要深入了解的玩家，可以參考官方的物品過濾器指南以獲取更多信息和範例 [[1]](https://pathofexile.fandom.com/wiki/Guide:Item_filter)[[2]](https://www.pathofexile.com/item-filter/about).

---
Learn more:
1. [Guide:Item filter - Path of Exile Wiki](https://pathofexile.fandom.com/wiki/Guide:Item_filter)
2. [Path of Exile](https://www.pathofexile.com/item-filter/about)
3. [Highlighting items :: Path of Exile General Discussions](https://steamcommunity.com/app/238960/discussions/0/535152511346975102/)
