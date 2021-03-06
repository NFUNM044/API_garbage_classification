# API_garbage_classification
# 易扔APP产品需求文档
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| APP名称 | 易扔  |
| APP类别 | 生活、工具  |

# Powerpoint
[Powerpoint](https://v.qq.com/x/page/s3049zb53e3.html)
# ⭐一、PRD价值主张设计：
## 产品介绍：
- 易扔App是一款提供给用户，根据用户定位地点进行不同城市的垃圾分类要求，可通过语音、文字、图像识别垃圾的垃圾分类助手APP。致力于帮助用户轻松应对垃圾分类的难题。
## 价值宣言：
- 易扔是一款协助用户快速准确将垃圾分类的智能app。自2019年7月上海市实行严格垃圾分类措施,并且带有惩罚机制。短时间内在全国各城市掀起热潮，未来会延展到46个城市试点。市民们最困扰的是莫过于如何快速识别垃圾分类，避免认错垃圾而造成的罚款。而易扔app提供三种垃圾分类查询方式，拍照识别、语音搜索和文字搜索，简洁大方的界面，为用户提供方便快捷的服务。
## 核心价值（最小可行性产品）：
- 通过图像、语音、文字输入可智能识别出垃圾分类，并提供相应的投放建议。
## 核心价值与用户痛点：
- 用户在使用产品时，可快速查询到相关的垃圾分类知识，精准正确的投放垃圾分类。避免垃圾分错类的情况而造成的罚款，降低政策实施给用户带来新增成本。
## 人工智能概率性与用户痛点：
- 用户在使用文字识别和语音识别功能精准度是比较高的，方便用户找到最靠近的投放目的地，而在图像识别垃圾垃圾分类的部分，反而是有可能因为数据库资料不足或者是识别失误，对用户作出错误的答案，出现假阳性（false positive），但对用户的负面体验机率并不会高于正面影响。
## 需求列表与人工智能API加值：
| 使用场景 | 用户需求  |重要程度 |对应功能  | 使用的API  | 
|:-|:-: | :-: |:-:|:-:|
|垃圾太多分类， 无法确认垃圾的种类。|需要快速准确的垃圾分类 | 重 要 |垃圾识别(语音、图像)|[天行数据垃圾分类API](https://www.tianapi.com/apiview/97)  | 
|不同城市的垃圾分类标准要求不同|需要本城市垃圾分类标准，准确分类|重要  |用户定位  |[高德地图地理编码API](https://lbs.amap.com/api/webservice/guide/api/georegeo) | 
# ⭐二、原型设计
## 交互及界面设计：
- 1、启动页：用户引入眼帘的是一个垃圾桶和易扔APP的slogen。<br>  ![易扔APP启动页.png](https://upload-images.jianshu.io/upload_images/9509773-a37446ffe44d386d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



- 2、首页：用户进入易扔APP后，可选择不同垃圾识别功能。 ![易扔APP首页.png](https://upload-images.jianshu.io/upload_images/9509773-1ddfae2ae3282c30.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 3、文字搜索：用户可以进行文字搜索，可描述具体垃圾内容。![易扔APP 文字搜索.png](https://upload-images.jianshu.io/upload_images/9509773-f32861d36f6dc8a7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




- 4、拍照搜索：用户可进行拍照识别，快速准确查看垃圾分类。![易扔APP 拍照搜索.png](https://upload-images.jianshu.io/upload_images/9509773-54351a575b734b3e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





- 5、语音搜索：用户选择语音搜索，可节省打字的时间。![易扔APP 语音搜索.png](https://upload-images.jianshu.io/upload_images/9509773-1210f7dd597b4047.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 6、分类查看：用户可以点击查看垃圾分类知识，帮助用户分清垃圾类别。![易扔APP 分类查看.png](https://upload-images.jianshu.io/upload_images/9509773-ba5e7915d3e97039.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


- 7、历史搜索：用户可查看历史的搜索记录，省去再次输入垃圾名称。![易扔APP 历史搜索.png](https://upload-images.jianshu.io/upload_images/9509773-b1f07c319ba80a1e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




## 原型文档：
## [易扔APP可交互原型](https://nfunm044.github.io/prototype_download/.)  ← 可点击查看

## [原型文件，供下载](https://github.com/NFUNM044/prototype_download)  ← 可点击下载

## 信息设计：

- 产品结构图：
![易扔产品结构图.png](https://upload-images.jianshu.io/upload_images/9509773-d461a9298d8a8d5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





- 核心功能流程图：

![原型信息设计流程.jpg](https://upload-images.jianshu.io/upload_images/9509773-b963169699a21fdc.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# ⭐三、API 产品使用关键AI或机器学习之API的输出入展示

## 使用水平：
|功能| 输入  | 输出|使用API|
|:-:|:-:|:-:|:-:|
| * 文字搜索 | 垃圾名称  |垃圾分类、投放建议|天行数据垃圾识别（文本识别）|
| 拍照搜索 | 垃圾图片  |垃圾物体、垃圾分类、投放建议 |天行数据垃圾分类识别（图像识别）|
| 语音搜索 | 垃圾名称  |垃圾物体、垃圾分类、投放建议|天行数据垃圾分类识别（语音识别）|

#### 核心API：天行数据垃圾识别（文本识别）输入、输出展示：
- 代码输入值：
![输入值.png](https://upload-images.jianshu.io/upload_images/9509773-dfd20c9a48b6a009.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 代码输出值：
![输出值.png](https://upload-images.jianshu.io/upload_images/9509773-337614de046eae22.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 使用比较分析：
**选取文字搜索测试：**

- ##### 可查看→ **[jupyter文字搜索测试代码【HTML】](https://github.com/NFUNM044/API_garbage_classification/blob/master/garbage_classification_compared.html)**
- ##### 可查看→ **[jupyter文字搜索测试代码【IPYNB】](https://github.com/NFUNM044/API_garbage_classification/blob/master/garbage_classification_compared.ipynb)**
|API| 费用  |成熟度|性价比|选择|
|:-:|:-:|:-:|:-:|:-:|
| 天行数据垃圾分类API | 注册后赠送2000次，随后一元10000次 |成熟|高|√|
| 聚合数据垃圾分类API |首次赠送100次使用，随后0.002元/次|成熟|高||
| 京东垃圾分类API |免费 5000 次/日  |一般|中||

- 在jupyter文字搜索测试代码【IPYNB】里可以明显看出，京东的垃圾分类API，需要不断的更新timestamp，不太完善，对比聚合数据、天行数据，天行数据的占大优势，不仅成功识别出垃圾，且相关垃圾周边也列出，可以很好的帮助用户解决问题，并且费用不高，成熟度高，性价比高，因此选择天行数据垃圾分类。

## 使用后风险报告：
- 所使用的API类别：垃圾分类（图像识别、文字识别、语音识别）
- 未来发展性：国家在大力提倡垃圾分类行动，上海也实施试点工作，全国各地引发热潮，不久的未来，垃圾分类的需求会越来越大，因此前景是光明的。再结合线上线下的合作，如上门回收垃圾等功能，APP的商业价值会更高。

|类别| 选用API |竞争者|
|:-:|:-:|:-:|
|文字搜索| 天行数据垃圾分类API  |聚合数据、京东|
|语音搜索|  天行数据垃圾分类API  |聚合数据、京东|
|拍照搜索|  天行数据垃圾分类API  |聚合数据、京东|
|地理定位|  高德地图API  |百度地图|


<br>
网上资料：
1.[中国垃圾分类现状分析](http://huanbao.bjx.com.cn/news/20190930/1010776.shtml) <br>
2.  [2019年中国垃圾分类现状及发展趋势分析](http://www.huaon.com/story/444797)
