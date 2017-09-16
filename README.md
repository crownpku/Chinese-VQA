# Chinese-VQA

Chinese Visual Question Answering 中文看图问答

## UNDER HEAVY DEVELOPMENT

### Downloads

Coco Pictures 2014: http://cocodataset.org/#download

VGG16 Model: https://www.cs.toronto.edu/~frossard/post/vgg16/

Chinese VQA Text Data: http://idl.baidu.com/FM-IQA.html


### Problems

1. This is a very difficult problem combining both image and NLP. 

2. We do have a good Chinese VQA dataset (FM-IQA from Baidu). However the data is "free-style" labeled by humans, making it kind of noisy for processing (welcome to the real world!)

3. Current models usually uses categorical results for answering questions, but natural language generation as a seq2seq way should be much natural.

4. No high-quality open-sourced VQA code on github yet. Most state-of-art algorithms are coded in pytorch instead of tensorflow. Anyway, should I learn pytorch now, which according to many posts is much cooler?


### Related github projects

https://github.com/Cadene/vqa.pytorch

https://github.com/paarthneekhara/neural-vqa-tensorflow

https://github.com/JamesChuanggg/VQA-tensorflow

https://github.com/JamesChuanggg/awesome-vqa

https://github.com/pdollar/coco

### Sample QA pairs in FM-IQA

```
他在玩水上漂吗？:是的。
床单是什么颜色？:白色。
这是什么地方？:卧室。
厨房台什么颜色的？:银色的。
远处水边的是什么？:大象。
这是什么标志？:这是标上停车标志。
树下有自行车吗？:有。
水面上有船吗？:水面上有船。
男人穿着什么颜色的衣服？:白色。
这是什么？:飞机。
这是什么动物？:羊！。
他在玩什么？:滑板。
树是绿色的么？:是的。
这里有人吗？:没有。
这花是什么颜色？:紫色。
汽车是什么颜色？:黄色。
这个人在玩具熊的什么地方？:他在玩具熊的左边。
这个人手里拿着什么？:这个人手里拿着一个滑板。
人的旁边有动物吗？:人的旁边有动物。
这是什么动物？:狗。
狗在哪里？:滑板上。
广场上是什么？:飞机。
这个人手里拿的什么东西？:拿的剪刀。
这个屋子的墙上有挂画作品吗？:有的。
盘子里是什么？:面包夹肠。
盘子是什么颜色的？:白色。
这是什么？:钟表。
这是谁？:卖香蕉的小贩。
人在干什么？:在玩电脑。
橱柜的颜色是什么？:白色。
这个人穿着什么颜色的衣服？:黑色。
这是一列火车吗？:是的。
筐子里是什么？:一些面包，。
这是什么？:长颈鹿。
这是什么？:香蕉。
美女在哪里？:美女坐在摩托车上。
这是什么？:大巴。
小宝宝身上穿的是白色衣服吗？:是的。
这是哪里？:浴室。
他穿什么颜色的外套？:紫色。
这是什么？:甜点。
他在干嘛？:滑雪。
路旁有什么？:有树。
这个人在干什么？:扔飞盘。
足球是什么颜色的？:黄色。
汽车是什么颜色的？:汽车是白色的。
戴礼帽的男子在做什么？:数钱。
图片中有电风扇吗？:有。
女士穿的是黑色衣服吗？:是的。
猫是什么颜色？？:黑色。
这是长颈鹿吗？:是的。
他们在干什么？:放风筝。
有红色的旗吗？:有。
这是在海边么？:是的。
盆子里有什么食物？:薯条,牛排西兰花面包。
这里有几个人？:这里有五个人。
图中运动员穿的什么颜色的上衣？:蓝色。
手机是什么颜色？:手机是黑色。
小狗在哪？:小狗在滑板上。
过道旁有几个男的？:3个。
他在干什么？:打网球。
这是在滑雪吗？:是的。
这是什么食物？:这是薯条。
盘子是什么颜色的？:白色。
这是什么动物？:大象。
两匹马拉着的是观光车吗？:是的。
这里有人吗？:有。
他在干涉么呢？:他在放风筝。
河面上有什么东西？:船。
这是一辆双层巴士吗？:是的。
大象后面的人手里拿着什么？:一个手提桶。
有动物吗？:有。
她是在刷牙吗？:是的。
这个人在干吗？:投棒球。
这是什么东西？:飞机。
她干嘛？:滑滑板。
他们在干什么？:他们在踢足球。
这个人在遛狗么？:是的。
这是一列火车吗？:是的。
那白色的的钟吗？:是的。
这里有几个人？:这里有两个人。
这个人在做什么？:这个人在煮玉米。
桥上是什么？:火车。
他干嘛？:滑板街头表演。
这里有什么呀？:电脑。
桌子上摆放的是什么食物呢？:是pizza。
这里有人玩滑板吗？:有。
他们在滑雪吗？:是的。
指示牌是什么颜色的？:指示牌是白色的。
这里有飞机吗？:有。
有刀子吗？:有。
这些人在干嘛？:他们在打棒球。
火车的主题颜色是什么色？:绿色。
那个人的上衣什么颜色？:黑色。
盘子里的是什么？:披萨。
这是架飞机吗？:这是架飞机。
这个人在干什么？:他在做饭。
盘子里有什么食物？:有三明治。
这里有人用手机吗？:有。
这是什么？:公共汽车。
```

