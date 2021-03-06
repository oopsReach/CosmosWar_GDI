# Cosmos War
> 使用GDI编写的 宇宙机器人大战

## 游戏信息

##### 游戏名：Cosmos War

##### 作者：Coder_murphy

##### 运行环境：.NET Framework 4.8

##### 游戏类型：单机 战棋 Player VS Computer

##### 背景：亚顿（你）与坦兹（敌人）的机械化部队在宇宙的各个角落展开了一场争夺权力的战争

##### 彩蛋：玩过SD敢达，超级机器人大战的人不陌生（致敬外星科技），吸取了两款游戏的灵感制作出的一款轻游戏。

## 游戏玩法：

移动战斗单位，建造战斗单位，拦截敌人战斗单位，攻下敌方AI主机（图标为G）的字样即可胜利

## 术语：

* Attack：攻击值
* Move：每回合能移动的格子数
* HP：当前单位耐久，耐久为0单位死亡
* EXSkill：单位必杀技，能提供额外的远程特性攻击，但攻击结束单位会挂E。
* Lv：单位等级（单位图标左上角显示），等级越高对单位自身属性加成越高，单位等级会通过场景预置或杀伤提升的方式升级。（PS：升级进度：杀死1个敌方单位即可升1级（最高25级））
* 挂E：就是单位图标右下角有一个字母E，提示玩家该单位本回合已经行动过了。

## 单位类型：

* Tank型：高HP，高防御，但机动性差，Move值与攻击值低。
* 突击型：低HP，低防御，但机动性强，Move值高，攻击值中等。
* 综合型：一般HP，中等防御，机动性一般，Move值中等，攻击值中等。
* 杀伤型：比综合型单位HP高，中等防御，机动性强，Move值高，攻击高，但造价昂贵。
* 炮塔型：高HP，高防御，机动性极差，Move值低，但攻击力很高。
* GB（战场中图标为GB的一个圆形）：工厂，可以提供单位生产，可以消耗金钱制造高级的机甲，但一回合只能使用一次。
* 主机（战场中图标为方形的G）：主机，占领敌方的主机可获得胜利，反之，我方主机被占领则游戏失败。

## 操作：

### 游戏界面：

***F：***切换选项/切换地图。
***Esc：***回退。
***Enter：***确认选项。

### 游戏场景：

***↑/←/↓/→*****：**向上/向左/向下/向右移动选择框。
***W/A/S/D*****：**向上/向左/向下/向右移动选择框。
***K/Num2*****：**选择单位。
***J/Num1*****：**取消工厂建造。
***←/→*****：**工厂模式下切换建造单位（建造时需要看窗口左下角钱够不够）

#### Respect！ good game！good luck！