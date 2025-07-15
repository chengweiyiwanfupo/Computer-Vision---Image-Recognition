# Computer-Vision---Image-Recognition
计算机视觉-图像识别-语义分割
#环境配置
OpenMMLab内包含了许多可用于图片/视频语义分割的模型，完成环境配置后可快速实现图片/视频的语义分割，同时还可以对比不同模型的识别效果。
不过呢，环境配置是比较复杂的，因为需要根据电脑的配置安装特定版本的PyTorch+CUDA+mmcv+mmsegmentation
许多同学在这一步就已经难到了，在这里我提供我的电脑参数，你可以根据我的步骤进行修改。
需要注意的是：我所有的代码使用的python语言，在Jupyter Notebook内编写，建议新建一个虚拟环境。
#电脑参数
CPU：13代i7-13700KF散片
主板：华硕(ASUS)B760-AYW 支持DDR5
内存：金百达(KINGBANK)32GB(16Gx2)套装5600
固态：致态(ZhiTai)长江存储1TB SSD固态硬盘 NVMe M.2接口 Ti600系列
显卡：华硕(ASUS)DUAL GeForce RTX 4060 08G EVO
散热：雅俊 E3PRO
电源：长城(Great Wall)额定650W
机箱：长城侧透机箱 黑色机箱
ok，就是这些了，请查看并根据OpenMMlab环境配置.txt文件进行配置吧！

完成配置后，在虚拟环境内新建一个.ipynb文件，跟随我的步骤开始图像识别吧。
