# API_garbage_classification
# 易扔APP产品需求文档
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| APP名称 | 易扔  |
| APP类别 | 生活、工具  |
# PRD价值主张设计：
## 产品介绍：
- 易扔App是一款提供给用户，根据用户定位地点进行不同城市的垃圾分类要求，可通过语音、文字、图像识别垃圾的垃圾分类助手APP。致力于帮助用户轻松应对垃圾分类的难题。
## 价值宣言：
- 随着上海率先实行垃圾分类试点，各地垃圾分类的浪潮不断兴起，人们对环境环保意识的需求，但不懂如何分类而造成的罚款痛点。易扔APP不仅可以多模态（拍照，文字，语音）搜索，为用户提供优质的产品服务的同时，也能对保护社会环境、地球资源出一份力。
## 核心价值（最小可行性产品）：
- 通过图像、语音、文字输入可智能识别出垃圾分类，并提供相应的投放建议。
## 核心价值与用户痛点：
- 用户在使用产品时，可快速查询到相关的垃圾分类知识，精准正确的投放垃圾分类。避免垃圾分错类的情况而造成的罚款，降低政策实施给用户带来新增成本。
## 人工智能概率性与用户痛点：
- 用户在使用文字识别和语音识别功能精准度是比较高的，方便用户找到最靠近的投放目的地，而在图像识别垃圾垃圾分类的部分，反而是有可能因为数据库资料不足或者是识别失误，对用户作出错误的答案，出现假阳性（false positive），但对用户的负面体验机率并不会高于正面影响。
## 需求列表与人工智能API加值：
| 使用场景 | 用户需求  |重要程度 |对应功能  | 使用的API  | 
|:-|:-: | :-: |:-:|:-:|
|垃圾太多分类， 无法确认垃圾的种类。|需要快速准确的垃圾分类 | 重 要 |垃圾识别(语音、图像)|[京东人工智能垃圾分类API](http://neuhub.jd.com/ai/api/image/garbageClassify)  | 
|不同城市的垃圾分类标准要求不同|需要本城市垃圾分类标准，准确分类|重要  |用户定位  |[高德地图地理编码API](https://lbs.amap.com/api/webservice/guide/api/georegeo) | 
# 二、原型设计
## 交互及界面设计：
- 1、首页：用户进入易扔APP后，可选择不同垃圾识别功能。![易扔APP首页.png](https://upload-images.jianshu.io/upload_images/9509773-4e181359820072f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 2、文字搜索：用户可以进行文字搜索，可描述具体垃圾内容。![易扔APP 文字搜索.png](https://upload-images.jianshu.io/upload_images/9509773-a2492aa984719123.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 3、拍照搜索：用户可进行拍照识别，快速准确查看垃圾分类。![易扔APP 拍照搜索.png](https://upload-images.jianshu.io/upload_images/9509773-1d628d5bf048411f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 4、语音搜索：用户选择语音搜索，可节省打字的时间。![易扔APP 语音搜索.png](https://upload-images.jianshu.io/upload_images/9509773-afdac1f2a8eb5471.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 信息设计：![原型信息设计流程.jpg](https://upload-images.jianshu.io/upload_images/9509773-75f277e121519c6e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 原型文档：
# 三、API 产品使用关键AI或机器学习之API的输出入展示
## 使用水平：
## 使用比较分析：
## 使用后风险报告：
