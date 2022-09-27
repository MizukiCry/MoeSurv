Source Code 没了，只有 0.0.0 了（

---

### 前言

这是什么？

寒假闲着无聊做的小游戏，但是因为太颓没怎么学也做不了什么。

---

### 游戏目标

控制角色在场景中躲开生成的炸弹。

---

### 游戏教程

解压后打开```MoeSurv_P1.exe```运行游戏，~~```Alt+F4```退出游戏~~

WASD 控制角色前后左右移动

鼠标 控制视角

空格 跳跃

E/Q 向上/下飞（死亡状态）

E 开门（鼠标对准状态）

---

### 其他设定

游戏初始分辨率1280*720，帧率限制60FPS。

玩家初始HP100（上限），每0.2秒回复0.1HP。

玩家死亡后转入旁观者模式，可飞行，无法与场景进行互动，可穿墙，5秒后弹出菜单。

门的开/关冷却时间为3s，有操控距离限制。

按G受到20点伤害（Debug用）

- 炸弹
  
  场景中分布有固定的炸弹生成点，随机[5,15]秒后以30%的概率生成炸弹，3秒后爆炸，半径500，基础伤害120，随距离递减，不可穿透。
  
  <img title="" src="https://raw.githubusercontent.com/MizukiCry/ImageHosting/master/img/Moe_Bomb.gif" alt="Moe_Bomb.gif" style="zoom:50%;">

- 增益道具
  
  场景中分布有固定的道具生成点，随机[15,25]秒后以30%的概率生成任一道具，10秒后消失。
  
  - Healer
    
    将玩家HP回复至100
    
    <img title="" src="https://raw.githubusercontent.com/MizukiCry/ImageHosting/master/img/Moe_Healer.png" alt="Moe_Healer.png" style="zoom:25%;">
  
  - Shield
    
    给予玩家额外100点护盾值（上限100）
    
    <img title="" src="https://raw.githubusercontent.com/MizukiCry/ImageHosting/master/img/Moe_Shield.png" alt="Moe_Shield.png" style="zoom:25%;">
  
  - WalkBooster
    
    使玩家移动速度翻倍，持续15秒（可叠加）
    
    <img title="" src="https://raw.githubusercontent.com/MizukiCry/ImageHosting/master/img/Moe_WalkBooster.png" alt="Moe_WalkBooster.png" style="zoom:25%;">
  
  - JumpBooster
    
    使玩家跳跃高度翻倍，持续15秒（可叠加）
    
    <img title="" src="https://raw.githubusercontent.com/MizukiCry/ImageHosting/master/img/Moe_JumpBooster.png" alt="Moe_JumpBooster.png" style="zoom:25%;">

---

### 后记

目前Bug就是刚打开时会全屏黑一下，之后再修

以及其他想加的东西，以后再说（