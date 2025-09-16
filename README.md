# 贪吃蛇游戏 (Java)

这是一个使用 Java Swing 编写的桌面贪吃蛇游戏示例。玩家可以使用方向键控制蛇的移动，吃到食物会变长，撞到自己或边界则游戏结束。按下 Enter 键可以在游戏结束后重新开始。

## 运行方式

1. 确保已安装 JDK 8 或更高版本。
2. 在项目根目录下编译：
   ```bash
   javac -d out $(find src -name "*.java")
   ```
3. 运行游戏：
   ```bash
   java -cp out com.example.snake.SnakeGame
   ```

运行后会弹出一个 600x600 的窗口，即可开始游戏。
