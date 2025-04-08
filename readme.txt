运行步骤
1 下载数据集
2 运行code/data_prepare，该步骤主要目的是生成parquet文件，运行速度快
3 运行code/recall_sort，这个代码里面包含召回和排序两部分

一些依赖的包需要自行安装一下
pandas
numpy
lightgbm
pyarrow
pickle
tdqm

运行需要内存较大，建议64G内存
