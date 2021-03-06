# Minesweeper

## 1.开始界面说明

​    主界面有四个选项，“1.新兵”、“2.普通”、“3.老兵”、“查看纪录”，鼠标移动到上面时会有颜色变化提醒。
​    左击“1.新兵”，会进入9×9的扫雷游戏地图，玩家需要根据数字提示找出10个地雷。普通模式为16×16的地图，共40个地雷。老兵模式提供给具有相当丰富的游戏经验的玩家选择，为30*16的地图，共99个地雷。
​    左击“查看纪录”，会在下方显示以前的玩家留下的游戏纪录。

## 2.游戏主界面说明

​    游戏主界面有三大模块：时间模块、标记模块和雷区。
​    左上角显示时间，通过模拟线程方式显示了从玩家点击第一个未知区域开始到当前经历的秒数。需要玩家注意的是，由于是模拟线程，当玩家的鼠标不移动、不点击时时间仍在纪录但是不会显示变化，这不会影响最终的成绩判定。请玩家注意，游戏胜利必须在999秒内完成，否则成绩将得不到系统的认可。
​    右上角显示标记数目。标记的数目等于雷的数目。
​    中央是雷区，关于雷区的点击方法在下文介绍。
​    右下角有“退出游戏”选项，玩家随时可以通过点击该按钮退出游戏。

## 3.雷区点击说明

​    左键点击代表“踩踏”未知区域，如果您不幸踩到的是地雷，那么游戏结束。如果您将地图上所有的非雷（即安全）区域踩开，则游戏胜利。
​    右键为辅助功能，为了避免您在识别出地雷后误触，您可以右击您识别出的雷区进行标记，标记上红旗以后该区域在被左击不会爆炸。如果您发现标记得有疑问，可以再次右击，这时显示为问号，即疑问区域。如果您确认标记得不对，再次右击问号即可取消一切标记，该区域又变回未知区域

## 4.纪录系统说明

​    玩家每一次游戏胜利后，所经历的时间若是小于从前玩家留下的纪录，即认为打破纪录。