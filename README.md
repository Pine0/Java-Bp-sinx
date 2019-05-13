# Java-Bp-FittingFunction
使用Java语言实现Bp算法拟合函数，包含f(x1,x2) = x1 + x2、f(x) = sin(x)、f(x) = x^2函数。
# 运行
1、将lib文件夹下的jar包导入，此包用来绘制图像。
2、配置src/conf/network.properties文件，本程序已将各个函数配置好了，想运行那个函数只需将函数下的注释取消。
3、打开src/Function文件，运行main函数。
# 图像输出
本程序图像输出在运行完程序自动跳出。
# 数据输出
本程序数据输出在data文件夹下，分别为函数名.txt、函数名_Fit.txt、函数名_Loss.txt,
--------函数名.txt-------
这个文件存的为自变量值和正确函数值，1行为自变量值，2行为正确函数值。
------函数名_Fit.txt-----
这个文件存的为每次拟合的数据，奇数行为自变量值，偶数行为每次拟合的函数值，所以假设拟合10000次，这个文件中就有20000行。
-----函数名_Loss.txt-----
这个文件中存的为每次拟合的loss值，多少次拟合就有多少行数据。
# 说明
本程序拟合f(x1,x2) = x1 + x2函数时，由于这个图像显示不了，为了让图像显示，我给模型喂的数据为x1 = x2。于是输出的像f(x) = 2x，其实你可以想象成这样，z = x + y这个三维图像用x = y这个平面切了一刀输出的图像。
