# 工作日志
## 2024.7.1 - 2024.7.7
完成了项目初始化和基础角色构建，实现了玩家角色在场景中基于输入的的奔跑、行走、使用工具等行为，工作内容包括以下部分：
- 导入全部项目所需资产，编辑角色动画
- 使用cinemachine设置始终跟随玩家的摄像机，设置正确的画面尺寸
- 创建抽象类单例模式用于玩家组件、各种游戏管理器
- 使用发布订阅模式，创建委托、事件执行玩家的运动
- 使用动画组件和动画控制器设置全部玩家动画