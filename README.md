# Neural Style 
风格迁移tensorflow版

7分钟让你成为模仿高手


## 使用方法

### 本地的使用方法

#### 依赖
```
opencv >=3.0
tensorflow >= 1.0
[imagenet-vgg-verydeep-19.mat](http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat)
jupyter notebook
```

#### 操作过程
```
git clone https://github.com/RussellCloud/Neural_Style.git
cd Neural_Style
mkdir input
cp /path_to_imagenet-vgg-verydeep-19.mat /input/
jupyter notebook
```

### 简单快捷的RussellCloud
**省去复杂的Opencv和Tensorflow配置过程**
#### Step 1 
搞定一个平台账号，[点我](http://russellcloud.com/welcome)，创建名为`Neural_Style`的项目。

```
pip install -U russell-cli

```

#### Step 2
克隆复现

```
git clone https://github.com/RussellCloud/Neural_Style.git
cd Neural_Style
russell login
russell init --name Neural_Style
russell run --gpu --mode jupyter --data d2235ba6c9f94d519539d111d789e659
```

## Tips
- 修改jupyter内的风格图位置，可生成专属的风格。
- 在RussellCloud的帮助下，7分钟即可完成迁移。

