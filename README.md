AltiumDesigner_PcbLibrary
=========================
[![GitHub release](https://img.shields.io/github/release/KitSprout/AltiumDesigner_PcbLibrary.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v2.18-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v2.18)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v1.9-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v1.9)
[![GitHub pcb library](https://img.shields.io/badge/pcb%20library-%20v0.12-yellow.svg)](https://github.com/KitSprout/AltiumDesigner_PcbLibrary/releases/tag/v0.12)

![image](https://github.com/TiWeZhang/AltiumDesigner_PcbLibrary/assets/34831082/6d084574-9d42-4df9-b866-fbf846ac0166)
![image](https://github.com/TiWeZhang/AltiumDesigner_PcbLibrary/assets/34831082/8371212e-be64-4714-8387-12ea8089a8d6)

Mechanical 13 用于摆放3D结构。  
Mechanical 14、Mechanical 15 用來表示上层元件货下层元件，两者预设为 Pairs，在元件翻面时自动切换。  


-- Origin Author -- 
v3 版本主要調整內容 :  
1. 在元件庫中加入更多的資訊，像是封裝、數值... 等等，方便更有效率生成 BOM。  
2. 使用的字體主要改用 consolas，consolas 字體的每個字元距離固定，表示上比較清楚。  
3. footprints 中加入 .designator 讓元件自動編號，不需要再手動調整(在 .PcbDoc 裡，透過 CTRL + D -> View Options -> Display Options -> 啟用 Convert Special Strings 後，可以自動轉換成編號)  。
