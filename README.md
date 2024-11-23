# 脚本(Scripts)
## 为什么收录脚本？(Why?)
Mac os端不能使用ArcgisMap、ArcgisPro，处理地理信息数据的最好软件就是QGIS，但是在使用的过程中发现有些功能目前仍存在缺失，部分目的没有实现，作为中文母语者，在一堆英文插件中找到匹配需求的又比较难，
庆幸的是QGIS提供了`Python`工作区，因此可以利用Python编写一些脚本来满足数据处理的需求。
> ArcgisMap and ArcgisPro cannot be used on Mac os, so QGIS is the best software for processing geographic information data. However, it is found that some functions are still missing in the process of use, and some purposes have not been realized. As a Chinese native speaker, it is difficult to find matching requirements among a bunch of English plug-ins.
Fortunately, QGIS provides a Python workspace, so you can use Python to write some scripts to meet the needs of data processing.
## 脚本内容(Contents)
1. osm_to_shp:批量的将`osm`文件转化成`shp`文件，只需要设置输出路径，该脚本即可自动获取窗口目录下所有`osm`图层。其他格式的文件尚未测试。
> osm to shp: Batch 'osm' files into 'shp' files, only need to set the output path, the script can automatically get all the 'osm' layers in the window directory.
> Files in other formats have not yet been tested.
