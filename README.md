# RPS-BattleRoyale
By Nyaro
RPS - BattleRoyale游戏说明
 
简介
 
RPS - BattleRoyale是一款基于经典剪刀石头布游戏概念开发的趣味网页游戏。在游戏中，玩家从剪刀、石头、布中选择其一，大量随机分布在页面上的相应元素会相互竞争，根据剪刀石头布的规则决定胜负，最终决出唯一的胜者，玩家需猜测该胜者以判断输赢。
 
游戏玩法
 
选择元素：玩家点击“选择✂️”“选择🪨”或“选择🧻”按钮，选定自己猜测会获胜的元素。
元素竞争：游戏会根据设定的数量生成剪刀、石头、布元素，它们在页面上随机分布并自动寻找最近的“敌人”（相克元素）移动。当两个相克元素距离足够近时，按照剪刀石头布规则决定胜负，胜者会“同化”败者。
游戏结束判断：当页面上仅剩下一种元素时，游戏结束。若玩家选择的元素与最终胜者相同，则玩家猜对获胜；否则失败。
重新开始游戏：游戏结束后，点击“RESTART”按钮可重新开始游戏，页面会重置，元素重新生成。
调整元素数量：通过页面下方的“+”和“-”按钮，玩家可以增加或减少每次游戏生成的元素数量，范围为大于1的整数。
 
技术实现
 
前端技术：使用HTML构建页面结构，CSS进行样式设计，JavaScript实现游戏逻辑，包括元素创建、移动、碰撞检测、胜负判断以及游戏状态管理等功能。
性能优化：通过 requestAnimationFrame 和 setInterval 结合的方式控制元素移动频率，计算并显示当前游戏帧率（FPS），确保游戏流畅运行。同时，利用 will - change 属性提升动画性能。
浏览器识别：获取浏览器的 userAgent 字符串，识别玩家使用的浏览器类型，并显示在页面底部。
 
开发者信息
 
本游戏由Nyakawa开发，项目仓库地址：https://gitee.com/nyakawa。
 
贡献与反馈
 
欢迎大家对本项目提出宝贵的意见和建议，如有问题或想要贡献代码，请在仓库中提交issue或发起pull request。
 
RPS - BattleRoyale Game Instructions
 
Introduction
 
RPS - BattleRoyale is a fun web - based game developed based on the concept of the classic Rock - Paper - Scissors game. In the game, players choose one of rock, paper, or scissors. A large number of corresponding elements randomly distributed on the page will compete with each other. The winner is determined according to the rules of Rock - Paper - Scissors, and players need to guess the winner to determine whether they win or lose.
 
Gameplay
 
Select an Element: Players click the "Choose ✂️", "Choose 🪨", or "Choose 🧻" button to select the element they guess will win.
Element Competition: The game generates rock, paper, and scissors elements based on the set quantity. These elements are randomly distributed on the page and automatically move to find the nearest "enemy" (the相克 element). When two相克 elements are close enough, the winner is determined according to the rules of Rock - Paper - Scissors, and the winner will "assimilate" the loser.
Game Over Judgment: When there is only one type of element left on the page, the game ends. If the element selected by the player is the same as the final winner, the player wins; otherwise, the player loses.
Restart the Game: After the game ends, click the "RESTART" button to start a new game. The page will be reset, and new elements will be generated.
Adjust Element Quantity: Players can increase or decrease the number of elements generated in each game by using the "+" and "-" buttons at the bottom of the page. The number of elements must be an integer greater than 1.
 
Technical Implementation
 
Front - end Technology: HTML is used to build the page structure, CSS for styling, and JavaScript to implement the game logic, including element creation, movement, collision detection, win - loss judgment, and game state management.
Performance Optimization: The  requestAnimationFrame  and  setInterval  are combined to control the movement frequency of elements. The current game frame rate (FPS) is calculated and displayed to ensure smooth game operation. At the same time, the  will - change  property is used to improve animation performance.
Browser Identification: The  userAgent  string of the browser is obtained to identify the browser type used by the player, and it is displayed at the bottom of the page.
 
Developer Information
 
This game is developed by Nyakawa. The project repository address is: https://gitee.com/nyakawa.
 
Contribution and Feedback
 
Everyone is welcome to provide valuable suggestions and feedback on this project. If you have any questions or want to contribute code, please submit an issue or initiate a pull request in the repository.
