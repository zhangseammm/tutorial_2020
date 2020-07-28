## 基础考核 - 第二周（9.23-9.29）

### 必学内容：

1. 入门 OpenCV。
2. 使用 `makefile`。
3. 掌握基本的 Markdown 语法。

### 选修内容：

1. 多旋翼无人机飞行操控。
   队伍会提供 [DJI Flight Simulator](https://www.dji.com/cn/simulator) 飞行模拟器，如果你在学校有空余时间，可以来实验室的模拟器上练习。训练飞行器操控技巧的一个重要目的在于：避免损失贵重的无人机。无人机在调试或实际飞行时可能遇到意外情况或者失控，如果没有良好的飞行器操控技巧我们不会冒险让你使用无人机。
2. 习惯阅读英文文档以及官方文档。

### 本周任务：

1. 编写一个**多文件**的 C++ 程序，用 OpenCV 写一个视频背景还原器。具体要求请阅读[详细说明](https://github.com/SYSU-AERO-SWIFT/tutorial_2019/blob/master/tasks/week2/background_recovery.md)。并阅读[团队代码规范](https://github.com/SYSU-AERO-SWIFT/tutorial_2019/wiki/%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C%E8%A7%84%E8%8C%83)，按照相应规范编写该程序。
2. 为上述工程写一个 `makefile` 文件并编译运行通过。
3. 使用 Markdown，按照团队代码规范写一份说明文档。
4. 完成[程序设计能力练习](https://github.com/SYSU-AERO-SWIFT/tutorial_2019/blob/master/tasks/week2/programming_exercise.md)第二周题目链表加法，使用 `g++` 编译。
5. 完成 [Shell 练习题](https://github.com/SYSU-AERO-SWIFT/tutorial_2019/blob/master/tasks/week2/shell_exercise.md)。可参考[菜鸟教程](http://www.runoob.com/linux/linux-shell.html)或者 [Shell Scripting Tutorial](https://www.shellscript.sh/) 等，掌握基础命令即可。

### 评分标准：

| 评分项                       | 积分值   |
| ---------------------------- | -------- |
| 成功还原 `video0.mp4` 背景图 | 35分     |
| 成功还原 `video1.mp4` 背景图 | 20分     |
| 成功还原 `video2.mp4` 背景图 | 55分     |
| 输出程序运行计时             | 5分      |
| 算法速度优秀                 | 额外加分 |
| 使用 `makefile` 成功编译运行 | 10分     |
| 编写说明文档                 | 10分     |
| 完成第二周程序设计题         | 15分     |