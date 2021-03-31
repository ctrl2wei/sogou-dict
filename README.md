# Rime 鼠须管输入法｜搜狗词库和转换方法

### 已转换好词库

包含[搜狗](https://pinyin.sogou.com/dict/cate/index/167?rf=dictindex&pos=dict_rcmd)十二个分类，约 150 万个词典。

城市信息、自然科学、社会科学、工程应用、农林渔畜、医学医药

电子游戏、艺术设计、生活百科、运动休闲、人文科学、娱乐休闲

> 注：`★十二分类集合版★` 为上面十二个分类集合在一起。 

### 转换方法（如果图片无法显示，请开代理）

打开[搜狗词库](https://pinyin.sogou.com/dict/cate/index/167?rf=dictindex&pos=dict_rcmd)下载 `.scel` 文件。

![02](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/02.png)

下载深蓝词库转换工具 [imewlconverter_Windows.zip](https://github.com/studyzy/imewlconverter/releases) 并打开。

![03](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/03.png)

点击 `…` 选择下载好的词库（可多选），再点击**打开**。

> 注意：如果不显示词库，将右下角改为`所有格式`。

![04](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/04.png)

转出项选择【Rime中州韵】或【无拼音纯汉字】。

![08](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/08.png)

编码类型选择 **拼音** 和 **MacOS**，点击**确定**。

> 注意：如果转出项选择【无拼音纯汉字】则没有此步操作。

![05](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/05.png)

点击**转换**。

![06](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/06.png)

点击**是**保存在本地。

![07](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/07.png)

保存时自定义命名，生成一个 `.txt` 文件。

![09](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/09.png)

打开文件，将下面代码粘贴在文本最上方（`...` 下面空一行），修改词库名（以 sogou 为示例）并保存。

```
# 可以将包含哪些词库写在此处，方便日后查看是否有重复。

---
name: luna_pinyin.sogou            # 词库名自定义
version: "0.9"               
sort: by_weight              
use_preset_vocabulary: false
...

```

![2021-03-31-01.03.24.@2x](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/2021-03-31-01.03.24.@2x.png)

将文件重命名。

![01](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/01.png)

以 `.dict.yaml` 为后缀，命名为 `luna_pinyin.sogou.dict.yaml` 完成词库转换。

> 注意：名称一定要和文件内 `name` 相同。

![2021-03-31-01.04.41.@2x](https://raw.githubusercontent.com/liuour/tuchuang/master/pic/2021-03-31-01.04.41.@2x.png)

---

延伸：[Rime 鼠须管朙月拼音·简化字配置方案](https://github.com/liuour/rime)