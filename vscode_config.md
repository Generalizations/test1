# vscode config
- [Installation](#Installation)
- [Config](#Config)
  - [Qt For Python config](#Qt-For-Python-config)
  - [Python config](#Python-config)
- [vscode在虚拟环境中运行py文件的两种方式](#vscode在虚拟环境中运行py文件的两种方式)
## Installation
在vscode安装以下两种插件：
- python
- QT for python
## Config
以下使用路径均为虚拟环境的路径，所以根据自己虚拟路径做相应调整。
### Qt For Python config
输入框路径是虚拟环境下的\Script文件夹下的文件
1. 打开设置面板，搜索qt for python<br>
![1](https://github.com/Generalizations/test1/assets/142973887/59e1ddb4-85d7-4d23-9e83-f64fd4be3bb7)
2. 配置Qt For Python>Designer.Path<br>
![2](https://github.com/Generalizations/test1/assets/142973887/6034b3c4-6853-45db-9df0-fb3faa5720c8)
3. 配置Qt For Python>Rcc Path<br>
![3](https://github.com/Generalizations/test1/assets/142973887/4e5e6765-a973-4316-abfa-cf2d89770556)
4. 配置 Qt For Python>Uic Path<br>
![4](https://github.com/Generalizations/test1/assets/142973887/b89a9fb5-9190-4ca5-aee6-b498ea895bf4)
## Python config
1. 设置面板搜索Python
2. 配置default interpreter Path选项，路径为虚拟路径Scripts\python.exe<br>
![5](https://github.com/Generalizations/test1/assets/142973887/3670ed2d-89b3-447e-a7b9-c285a7a2d6a6)
3. vscode右下角显示python版本及虚拟环境<br>
![6](https://github.com/Generalizations/test1/assets/142973887/b3702e6a-2253-4a98-ae13-b9c8e55ba8d7)
## vscode在虚拟环境中运行py文件的两种方式
- 在命令窗口输入 python  xx.py需要运行的文件<br>
![7](https://github.com/Generalizations/test1/assets/142973887/41a898c5-6ca8-4e34-a7d4-6ad5817ce748)
- 直接点击文件名那行右侧的三角按钮<br>
![8](https://github.com/Generalizations/test1/assets/142973887/4c556ecd-da39-4449-b73e-6cfa4d60dbb5)
