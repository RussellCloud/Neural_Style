# Neural Style 
风格迁移tensorflow版

1分钟让你成为模仿高手


## 使用方法

### 本地的使用方法

#### 依赖
下载预训练权重
- [imagenet-vgg-verydeep-19.mat](http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat)
```
opencv >=3.0
tensorflow >= 1.0
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
搞定一个平台账号，[点我](http://russellcloud.com/welcome)，创建名为`Neural_Style`的`tensorflow-1.0:py2`项目。

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
russell run "bash stylize_image.sh ./image_input/lion.jpg ./styles/kandinsky.jpg" --gpu  --data bf9f524a384c4a69a021f0cf122815ec:model 
```

## Tips
- 修改 `bash stylize_image.sh <path_to_content_image> <path_to_style_image>`，可生成专属于你的风格。


---
参考资料
[cysmith/neural-style-tf](https://github.com/cysmith/neural-style-tf)

