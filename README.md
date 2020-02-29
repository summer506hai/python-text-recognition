# python-text-recognition
PyQt5做界面，使用百度文字识别API接口来实现识别图片中的文字，可以采用截图和浏览图片文件方式进行，

截图功能使用github的位作者的开源项目https://github.com/SeptemberHX/screenshot

## Prerequisite
1. PyQt5，使用pip install -U pyqt5 -i https://pypi.tuna.tsinghua.edu.cn/simple更新安装，其中 "-i https://pypi.tuna.tsinghua.edu.cn/simple"是使用清华源，加速下载
2. 百度aip，pip安装
`pip install -U baidu-aip`

## Simple Tutorial
下载整个软件包后进入src目录，执行
`python baidu-api.py`

1. 可以选择选取图片来识别图中的文字，选取后点击“转换”
2. 可以点击“截图”截取想要识别的内容，默认保存截图到目录"./temp/temp.png"，然后再
	选择"浏览文件"选择刚才的截图，最后点击“转换图片为文字”

## 2月29号更新  （BY SUMMER）
- 1.appid，apikey，screet key 可以自行填写；
- 2.添加错误判断，未填写appid，apikey，screet key时弹出对话框提示错误；
未选中图片或无截图时弹出对话框提示错误；
appid，apikey，screet key不正确时，弹出对话框提示错误
