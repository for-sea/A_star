# A_star

广度优先算法(BFS)、深度优先算法(DFS)、A\*算法分别解决十五码问题
BFS算法、DFS算法、A\*算法解决十五码问题

文件：
A_star.py:                      A\*算法运行脚本；
BFS.py:                         BFS算法运行脚本；
DFS_max_deepth.py:              DFS算法运行脚本；
report_A_star_E.txt:            初始状态1，欧氏距离-A\*算法运行结果输出文件；
report_A_star_M.txt:            初始状态1，曼哈顿距离-A\*算法运行结果输出文件；
report_A_star_E_new.txt:        初始状态2，欧氏距离-A\*算法运行结果输出文件；
report_A_star_M_new.txt:        初始状态2，曼哈顿距离-A\*算法运行结果输出文件；
report_DFS_max_deepth.txt:      DFS算法运行结果输出文件；
report_BFS.txt:                 BFS算法运行结果输出文件。


程序运行方法：

1. 所有程序均在Python 3环境下运行；
2. 在项目文件夹中通过命令行输入：
   1. python A_star.py -m cal_E_distence > report_A_star_E.txt
      即可通过欧氏距离的计算方法计算启发函数，并且输出结果保存在report_A_star_E.txt文件中。
   2. python A_star.py -m cal_M_distence > report_A_star_M.txt
      即可通过曼哈顿距离的计算方法计算启发函数，并且输出结果保存在report_A_star_M.txt文件中。
   3. python DFS_max_deepth.py > report_DFS_max_depth.txt
      即可通过深度优先算法，并且输出结果保存在report_DFS_max_deepth.txt文件中。
   4. python BFS.py > report_BFS.txt
      即可通过广度优先算法，并且输出结果保存在report_BFS.txt文件中。
3. 在.py 文件中修改初始状态4*4的列表(S0)，即可看到不同情况下的输出结果。
