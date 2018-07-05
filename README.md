# Start
- 在该文件夹目录下调出`shell`(`Windows`下调出`cmd`或`Powershell`)输入以下内容后回车。
```shell
python app.py
```
- 程序启动会比较慢，请耐心等待，如有`FutureWarning`或`UserWarning`等可忽视。等到出现

```shell
Input the path and image name:
```
![](https://user-images.githubusercontent.com/36038861/42327278-efe7dcc0-809d-11e8-8ee0-4fdd1c62cc73.png)

- 这时即可输入要识别的图片所在目录，或者把图片拖进`shell`里回车即可。初次运行时间较长，请耐心等候，之后的结果就几乎是秒出了。每识别一张图片成功会弹出两个`Matplotlib`窗口显示输入的图片及预测结果，例如下图所示

![](https://user-images.githubusercontent.com/36038861/42327606-b4d4159e-809e-11e8-943e-d972cb18e944.png)

- 叉掉之后可进行下一次的识别，这时仍会在`shell`显示

```shell
Input the path and image name:
```
![](https://user-images.githubusercontent.com/36038861/42327821-4a46e23c-809f-11e8-8a4f-af630c9b1164.png)

此时若输入`0`即可停止运行。



#### 注：
1. 本程序修改自北京大学曹健老师的`MOOC` [人工智能实践：Tensorflow笔记
](https://www.icourse163.org/learn/PKU-1002536002?tid=1002700003#/learn/announce)中的第八讲导学部分提供的代码，版权归原作所有。
![](https://user-images.githubusercontent.com/36038861/42328162-31b4f7f8-80a0-11e8-95af-60baffecb1e4.png)

2. 本`GitHub`项目未包含VGG16的神经网络权重文件`vgg16.npy`，需要的可在下文链接下载，下载后复制到该项目根目录即可

3. 本文的完整代码`Baiduyun` [链接在此](https://pan.baidu.com/s/1IbVqAwi8rUf84E7cYsqQMg) 密码 `hby5`
