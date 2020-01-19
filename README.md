# adao_roller
A岛跑团所用骰娘

使用方法：将cookies中替换为作为骰娘的饼干（用微信扫描饼干二维码得到字符串填入），将adao_roller.py中的thread_id全局变量修改为跑团所在串编号。last_post_id全局变量修改为所在串当前最后一个发言编号。（默认last_post_id之前的roll点不做反应）

骰点方法：@Roll(2000)结果为0~1999之间任意一个整数
