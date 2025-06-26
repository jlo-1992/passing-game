# 🏐 排球接扣遊戲 passing game
[Click here](<https://jlo-1992.github.io/passing-game/volleyball.html>) to play the game.

這是一款互動式的網頁小遊戲，靈感來自排球接球訓練，玩家需在限時內操控角色接住不斷掉落的排球，獲得高分即可進入排行榜！  
## 🎮 遊戲功能特色    
✅ 多難度選擇：提供 Beginner / Intermediate / Professional 三種模式，影響球速、重力、數量與生成頻率。  
✅ 倒數計時挑戰：每局時間有限，考驗玩家的反應與操作精準度。  
✅ 排行榜系統：結束後若得分進入前五名，可輸入名稱記錄排名（支援 LocalStorage 記憶）。  
✅ 動態分數顯示：即時更新得分、最高分與時間。  
✅ 視覺特效：擊中排球時顯示「NICE UP」動畫，進榜時則有閃爍動畫提示。  
## 🛠 技術架構說明    
HTML + CSS：使用純 HTML 結構與 CSS 排版，實作桌機版遊戲畫面。  
jQuery：簡化 DOM 操作與事件綁定流程，提升開發效率。  
GSAP (GreenSock Animation Platform)：製作動畫效果，如排行榜新進名次的閃爍、放大縮小特效。  
SweetAlert2：用於分數結算時的互動式輸入框。  
LocalStorage：儲存排行榜資料，關閉瀏覽器後仍能保留玩家紀錄。  
