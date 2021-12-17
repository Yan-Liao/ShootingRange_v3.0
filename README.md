# ShootingRange_v3.0
  My third homework.  
  本次作业提供了 Windows 平台的打包游戏和源代码。  

# 本次作业实现的内容：（所有作业三的要求均已实现）
  1. 加入了局域网联机模式，最多支持5名玩家同时在线；  
  2. 加入联机大厅功能的UI，玩家可以在大厅创建、搜索游戏，并且能够在大厅聊天；  
  3. 添加了人形AI敌人，AI能够寻敌、移动、开火；  
  4. 实现了AI不同个性设计，当AI血量较低时，AI有几率会逃跑，部分AI会硬刚；  
  5. AI死亡时，AI的枪支会掉落，玩家可以拾取。  

# 游戏联机的方法
  参考项目中的演示视频  
*联机中有以下几点需要注意：  
1. 只有主机(server)在游戏中可以暂停游戏，重新开始游戏和返回大厅，客户端(client)会跟随主机(server)做以上动作；  
2. 游戏中若主机(server)断开服务或退出，客户端(client)会返回大厅。
  
# 目前游戏中未解决的小问题
  1. 主机(server)退出游戏后，客户端会回到大厅，但无法加入到新游戏或创建新游戏，必须重启客户端。这个是由于主机退出时没能让客户端关闭session导致的，此部分做了一些处理，但目前仍有bug需要处理。  

