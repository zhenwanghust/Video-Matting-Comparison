# Video-Matting-Comparison
华中科技大学视觉认知工程结课作业（第三题）

##题目要求：
请选择一部电影并从中截取一段5秒长度的浅景深视频片段（前景聚焦背景虚化或中景聚集前背景虚化）要求所选视频中，聚焦主体应有一定的运动变化。
*利用 PhotoShop 逐帧标注聚焦主体的 alpha 蒙版（PhotoShop 可辅助实现半自动的标注），但需要注意检查细节（30’）；
*基于预训练的 In-Context Matting 模型（https://github.com/tiny-smart/in-context-matting），以截取视频第一帧的 alpha 蒙版为输入提示，预测剩余帧的 alpha蒙版（15’）；
*在所有预测剩余帧上计算视频抠图的 5 个相关指标（具体指标参考论文https://arxiv.org/pdf/2108.11515.pdf），并与 Robust Video Matting （https://github.com/PeterL1n/RobustVideoMatting）进行对比（25’）；
*将数据标注过程和实验结果整理成报告，根据定性和定量结果讨论 In-Context Matting 和Robust Video Matting 在所选视频上的优劣，并思考可能的原因。提交报告和标注的视频数据，相关代码提交到GitHub，并在报告中附上代码链接，在ReadMe中写清代码运行说明（可参照https://github.com/poppinace/indexnet_matting 的格式），代码运行结果应与报告中结果保持一致（30’）。

##代码运行说明
待更新
