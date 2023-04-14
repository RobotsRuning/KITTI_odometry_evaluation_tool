将要评价的轨迹放到`data`文件夹中

评价`data`文件夹中的单个轨迹，例如 `03_pred.txt` and `10_pred.txt` :

        python evaluation.py --result_dir=./data/ --eva_seqs=03_pred,10_pred 

评价 `data` 文件夹中的所有轨迹:

        python evaluation.py --result_dir=./data/ --eva_seqs=* 

本工具包含了A-LOAM 00-09的轨迹

包含了在Camera坐标系下的真值和LiDAR坐标系下的真值！根据自己算法情况选取。
