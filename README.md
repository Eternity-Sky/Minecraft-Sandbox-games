# Minecraft

#### 介绍
一款仿制我的世界的沙盒游戏

#### 软件架构
软件架构说明


#### 运行截图

![img](https://img.jbzj.com/file_images/article/202111/2021110909230214.jpg)

#### 使用说明

1.  运行main.py即可
2.  我的世界小游戏使用方法：

    移动

    前进：W，后退：S，向左：A，向右：D，环顾四周:鼠标，跳起：空格键，切换飞行模式:Tab;

    选择建筑材料

    砖：1，草：2，沙子：3，删除建筑：鼠标左键单击，创建建筑块：鼠标右键单击

    ESC退出程序。
4.  如果出现错误提示：
 `NameError: name 'GL_FOG' is not defined`
请降级你的Pyglet模块至1.5.27版本
`pip install pyglet==1.5.27`
