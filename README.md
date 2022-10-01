## 介紹 : 這是程式設計課程中製作的戰鬥機類型遊戲，遊戲功能包含角色選擇、角色升級、背景音樂、按鍵配樂、進度永久存檔、顯示我方敵方血量等。<p>
## 實作 : 使用C & Allegro寫，code皆寫在Fighter_game.cbp，其中包括很多function，如game_initial(初始化)、game_update(遊戲進行時不斷更新)、game_draw(編輯圖檔音樂檔)等，雖然Allegro不比Unity普及與實用，不過還是讓我學到很多coding知識
1. menu : 點選右上角會進入market，點選已滿18歲則進入play
2. market : 利用自己賺的skill point購買三種技能，包含增加自身血量、增加自身攻擊力、增加自身攻擊速度，且可以選取自己喜歡的角色
3. play : 我方按space即可發射子彈，上下左右控制方向，按WASD可以瞬間移動。敵方會不定時發射子彈，且敵人數愈來愈多
4. win : 當我方擊敗8位敵人，即勝利，並賺取大量skill point。按enter返回menu
5. lose : 當我方無法擊敗8位敵人，即失敗，不過仍能賺取少量skill point。按enter返回menu
## 附件
以下提供Fighter_game.cbp及遊戲畫面
