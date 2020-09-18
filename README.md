
# 一、项目介绍 
深度学习在 多目标任务 的ctr预估等场景中的应用，使用tensorflow estimator进行封装，包括esmm、mmoe模型

该项目针对多目标任务，这里给出单目标工程链接：https://github.com/R-Stalker/RSDeepModel

# 二、代码目录

##1.主函数

    local_run_esmm.py
    local_run_mmoe.py
    local_run_test.py——用于本地测试


##2.utils——工具函数文件夹

    utils/my_utils.py——一些基础共用函数
    utils/data_loader.py——加载tfrecord数据
    utils/model_layer.py——模型共用的内部模块，如自定义网络层，多值特征处理等
    utils/model_op.py——模型共用的训练、预测模块


##3.models——即深度学习模型文件，包括模型构建、训练、预测等

    models/esmm.py——esmm模型
    models/mmoe.py——mmoe模型
