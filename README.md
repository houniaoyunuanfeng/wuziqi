# 五子棋游戏

一款功能完善的五子棋游戏，具有标准对战模式和经典残局闯关模式。

## 特性

- **标准对战模式**：与AI对战，提供5个难度等级
  - 入门：适合初学者
  - 初级：提供基础挑战
  - 中级：更具挑战性
  - 高级：需要良好的五子棋技巧
  - 专家：极具挑战性，AI会使用高级策略

- **残局闯关模式**：100个精心设计的残局挑战，难度从简单到复杂
  - 每20关解锁一个新的难度区域
  - 已完成的关卡会被标记
  - 提供分页浏览

- **游戏功能**
  - 悔棋：可以撤销棋步
  - 提示：AI会提示你可能的最佳落子位置
  - 高亮显示最后一步棋

## 技术实现

- 纯JavaScript实现，无需任何外部库
- 使用Canvas绘制棋盘和棋子
- 不同难度的AI算法实现
  - 随机策略
  - 基础评估
  - 中等评估
  - 高级评估（使用Minimax算法）
  - 专家评估（使用Alpha-Beta剪枝的Minimax算法）

## 如何使用

1. 打开`index.html`文件即可开始游戏
2. 在主菜单中选择游戏模式：
   - 标准模式：选择难度后开始对战
   - 残局闯关：选择关卡进行挑战

## 未来功能

- 多人在线对战
- 游戏设置选项
- 棋局回放
- 更多残局挑战
- 自定义棋盘主题

## 开发者

这款游戏是由AI辅助开发的，基于HTML5、CSS3和原生JavaScript。

## 许可

MIT License 