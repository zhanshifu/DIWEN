### DWEN开发问题

### ①：图片名错乱

问题简介：在导入底图时候发生了导入图片的文件名相同，扩展名不同却可以同时导入的情况，这样会导致在制作ICL文件的时候发生文件名错误，但在更改文件名之后再DGUS设计软件中就无法成功预览文件

问题解决：DGUS设计软件的预览效果仅供参考，将错误的文件的文件名更改正确后上机即可解决问题，但DGUS设计软件无法预览会大大降低开发效率，所以在准备以及导入素材前应检查文件名是否有重复，或许软件开发者会在后续解决这个问题

### ②文本录入键盘不显示

问题简介：在使用文本录入功能时，经常会遇到触控后无法唤出键盘的情况

问题解决：检查一下三项键盘设置是否正确

![image](https://github.com/zhanshifu/My-own-liittle-program/tree/main/pictures/1.png)
![image](https://github.com/zhanshifu/My-own-liittle-program/tree/main/pictures/2.png)
![image](https://github.com/zhanshifu/My-own-liittle-program/tree/main/pictures/3.png)


### ③上机花屏

问题简介：在烧录之后上机，会导致花屏

问题解决：检查背景图更新之后是否重新生成了ICL文件（默认为32号）

或者检查各个ICL文件是否有冲突，（单个序号储存空间只能保存固定的文件大小（128K），多余文件向后自动下载，一储存空间无法保存多个序号，下一个序号必须向后命名）根据文件大小确定命名
