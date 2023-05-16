# 环境配置

AI环境配置:
https://cloud.tencent.com/developer/article/1769983

pip镜像使用以及设置:
https://mirrors.tuna.tsinghua.edu.cn/help/pypi/

conda activate 报错"need to restart after 'conda init' "的windows解决：
https://blog.csdn.net/weixin_44683255/article/details/129288628

windows下pytorch的安装：
https://zhuanlan.zhihu.com/p/254947834#

# git并运行yolov5

1.直接去GitHub 找到对应项目  ，git到本地。

2.配置好虚拟环境，包括安装ultralytics库

> pip install ultralytics
>
> 由于最近ultralytics库才更新，目前清华镜像的版本不足以跑yolov5(2023.5.15  \\  22:17)
>
> 需要自己去 pypi 下载whl文件并 运行   '   pip install  (whl文件路径，不加括号)  '
>
> 下载网址: [ultralytics · PyPI](https://pypi.org/project/ultralytics/#files)

3.根据 readme.md 文件内的指导操作。（ 所以readme.md很重要 ）