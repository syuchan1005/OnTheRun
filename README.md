# OnTheRun
 逃走中
 
# 仕様
## 基本概念
- Area
  - ゲーム全体の範囲
- Jail
  - PlayerがHunterに捕まると入る
  - アスレ, 謎解き等での復活も検討
---
- Player
  - Hunterから逃げるものMissionの対象, Itemの配布
- Hunter
  - Playerを追いかけ捕まえるもの
---
- Mission
  - Playerが受けるもの, 報酬等必要(?)
  - Hunter放出などもあり(?)
- Item
  - PlayerがHunterから逃げるときに使うもの
  - Missionの報酬, Area内配置などもあり(?)

## ファイル構造
>[PluginDataFolder]/  
>    ├ config.yml  
>    ├ items/  
>    │   │   ︙  
>    │   └  [ItemName].yml  
>    ├ missions/  
>    │   │   ︙  
>    │   └  [Mission].yml  
>    ├ games/  
>    │   │   ︙  
>    │   └  [GameName].yml  
  

        
